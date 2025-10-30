- [介绍](#介绍)
- [humaneval](#humaneval)
  - [指标分析总表](#指标分析总表)
  - [对比基准: `deepseek1.3b-original-data-25-sft`](#对比基准-deepseek13b-original-data-25-sft)
- [mbpp](#mbpp)
  - [指标分析总表](#指标分析总表-1)
  - [对比基准: `deepseek1.3b-original-data-25-sft`](#对比基准-deepseek13b-original-data-25-sft-1)
- [总结](#总结)



## 介绍
>以下的基准指的是 sft-codedpo sft-optimise codedpo optimise  四个模型在效率和准确率方面的最优值

* sft-codedpo  是在基础模型上进行微调之后进行的codedpo训练
* codedpo      是在基础模型上进行的codedpo训练
## humaneval
### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色</span>: 该列中的最差值。
* 🥇: 该列中的最佳值 (Pass@1 越高越好, 时间越低越好)。
* 🥈: 该列中的第二佳值。
* 🥉: 该列中的第三佳值。

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | 194417.38 | 🥉0.2448 |
| deepseek1.3b-original-data-dpo-pvf-qfs | 🥉186222.36 | 0.1894 |
| deepseek1.3b-original-data-25-sft-dpo-qfs | 191076.53 | 🥈0.2630 |
| deepseek1.3b-original-data-dpo-codedpo | 193981.23 | <font color="#E33D30">0.1613</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | 🥈186205.32 | 0.1827 |
| deepseek1.3b-original-data-dpo-all | 192680.75 | 0.1633 |
| deepseek1.3b-original-data-dpo-pvf-qsl | 193000.81 | 0.1668 |
| deepseek1.3b-original-data-dpo-pvf-qts | 192541.73 | 0.1666 |
| deepseek1.3b-original-data-sft-1 | 196712.15 | 0.1996 |
| deepseek1.3b-original-data-25-sft-dpo-qsl | 189617.27 | 0.2212 |
| deepseek1.3b-original-data-25-sft-dpo-all | 190873.82 | 0.1810 |
| deepseek1.3b-original-data-25-sft-dpo-qts | 194376.93 | 0.2061 |
| deepseek1.3b-original-data-25-sft | 194101.90 | 0.1976 |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">203001.69</font> | 0.1659 |
| deepseek1.3b-original-data-25-sft-dpo-qra | 🥇174924.23 | 🥇0.2646 |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | 196676.58 | 0.1766 |
| deepseek1.3b-original-data-dpo-qfs | 199536.91 | 0.2025 |

> 优于基准的有

`pvf-qfs`

`pvf-qra`

`sft-qsl`

`sft-qra`

### 对比基准: `deepseek1.3b-original-data-25-sft`

> **基准值: { 平均时间 (avg_time): 194101.90, Pass@1: 0.1976 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+315.48</font> | 1.00x | <font color="#1ABD76">+0.0472</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-7879.54</font> | <font color="#1ABD76">1.04x</font> | <font color="#E33D30">-0.0082</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-3025.37</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0654</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#1ABD76">-120.67</font> | 1.00x | <font color="#E33D30">-0.0363</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-7896.58</font> | <font color="#1ABD76">1.04x</font> | <font color="#E33D30">-0.0148</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-1421.15</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0343</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-1101.09</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0308</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-1560.17</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0309</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+2610.25</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0020</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-4484.63</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0236</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-3228.08</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0166</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#E33D30">+275.03</font> | 1.00x | <font color="#1ABD76">+0.0085</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">+8899.79</font> | <font color="#E33D30">0.96x</font> | <font color="#E33D30">-0.0317</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-19177.67</font> | <font color="#1ABD76">1.11x</font> | <font color="#1ABD76">+0.0670</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#E33D30">+2574.68</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0210</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#E33D30">+5435.01</font> | <font color="#E33D30">0.97x</font> | <font color="#1ABD76">+0.0049</font> |





## mbpp

### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色</span>: 该列中的最差值。
* 🥇: 该列中的最佳值 (Pass@1 越高越好, 时间越低越好)。
* 🥈: 该列中的第二佳值。
* 🥉: 该列中的第三佳值。

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">145201.96</font> | 🥉0.2487 |
| deepseek1.3b-original-data-dpo-pvf-qfs | 125537.00 | 0.1693 |
| deepseek1.3b-original-data-25-sft-dpo-qfs | 🥇116314.85 | 🥈0.2852 |
| deepseek1.3b-original-data-dpo-codedpo | 135058.94 | 0.1135 |
| deepseek1.3b-original-data-dpo-pvf-qra | 130816.76 | 0.1569 |
| deepseek1.3b-original-data-dpo-all | 129329.41 | <font color="#E33D30">0.1104</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | 128873.30 | 0.1218 |
| deepseek1.3b-original-data-dpo-pvf-qts | 129501.17 | 0.1218 |
| deepseek1.3b-original-data-sft-1 | 129970.42 | 0.1565 |
| deepseek1.3b-original-data-25-sft-dpo-qsl | 119350.19 | 0.2207 |
| deepseek1.3b-original-data-25-sft-dpo-all | 126682.58 | 0.1394 |
| deepseek1.3b-original-data-25-sft-dpo-qts | 127388.20 | 0.1793 |
| deepseek1.3b-original-data-25-sft | 132182.73 | 0.1583 |
| deepseek1.3b-original-data-dpo-pvf | 125963.99 | 0.1137 |
| deepseek1.3b-original-data-25-sft-dpo-qra | 🥉119091.63 | 🥇0.2861 |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | 123129.94 | 0.1351 |
| deepseek1.3b-original-data-dpo-qfs | 🥈117027.71 | 0.2027 |

> 优于基准的有

`sft-qfs`

`sft-qsl`

`sft-qra`

`qfs`


### 对比基准: `deepseek1.3b-original-data-25-sft`

> **基准值: { 平均时间 (avg_time): 132182.73, Pass@1: 0.1583 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+13019.23</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0904</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-6645.73</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0110</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-15867.88</font> | <font color="#1ABD76">1.14x</font> | <font color="#1ABD76">+0.1269</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#E33D30">+2876.20</font> | <font color="#E33D30">0.98x</font> | <font color="#E33D30">-0.0448</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-1365.98</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0014</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-2853.33</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0479</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-3309.43</font> | <font color="#1ABD76">1.03x</font> | <font color="#E33D30">-0.0365</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-2681.56</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0365</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#1ABD76">-2212.31</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0018</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-12832.55</font> | <font color="#1ABD76">1.11x</font> | <font color="#1ABD76">+0.0624</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-5500.16</font> | <font color="#1ABD76">1.04x</font> | <font color="#E33D30">-0.0188</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#1ABD76">-4794.54</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0210</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#1ABD76">-6218.74</font> | <font color="#1ABD76">1.05x</font> | <font color="#E33D30">-0.0446</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-13091.10</font> | <font color="#1ABD76">1.11x</font> | <font color="#1ABD76">+0.1278</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#1ABD76">-9052.80</font> | <font color="#1ABD76">1.07x</font> | <font color="#E33D30">-0.0231</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#1ABD76">-15155.02</font> | <font color="#1ABD76">1.13x</font> | <font color="#1ABD76">+0.0445</font> |


## 总结

`sft-qra`

`sft-qsl`

优于基准和sft
