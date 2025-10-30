- [介绍](#介绍)
- [mbppplus](#mbppplus)
  - [指标分析总表](#指标分析总表)
  - [对比基准: `sft-25-original-data-1b`](#对比基准-sft-25-original-data-1b)
- [mbpp](#mbpp)
  - [指标分析总表](#指标分析总表-1)
  - [对比基准: `sft-25-original-data-1b`](#对比基准-sft-25-original-data-1b-1)
- [humaneval](#humaneval)
  - [指标分析总表](#指标分析总表-2)
  - [对比基准: `sft-25-original-data-1b`](#对比基准-sft-25-original-data-1b-2)
- [humanevalplus](#humanevalplus)
  - [指标分析总表](#指标分析总表-3)
  - [对比基准: `sft-25-original-data-1b`](#对比基准-sft-25-original-data-1b-3)
- [总结](#总结)

## 介绍
>以下的基准指的是 sft-codedpo sft-optimise codedpo optimise  四个模型在效率和准确率方面的最优值

* sft-codedpo  是在基础模型上进行微调之后进行的codedpo训练
* codedpo      是在基础模型上进行的codedpo训练
##  mbppplus
### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色</span>: 该列中的最差值。
* 🥇: 该列中的最佳值 (Pass@1 越高越好, 时间越低越好)。
* 🥈: 该列中的第二佳值。
* 🥉: 该列中的第三佳值。

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| sft-codedpo | 2400984.91 | 0.1459 |
| sft-25-original-data-1b-dpo-pvf-qsl | 2391965.38 | 🥉0.1697 |
| sft-25-original-data-1b-dpo-qfs | 🥇2380615.93 | 0.1560 |
| sft-25-original-data-1b-dpo-pvf-qra | 2389976.76 | 🥇0.1713 |
| sft-25-original-data-1b-dpo-qsl | 2400639.12 | 0.1379 |
| startcode1b-original-data-dpo-pvf-qts | 2386640.07 | 0.0926 |
| startcode1b-original-data-dpo-pvf-qra | 🥈2384107.24 | 0.1236 |
| startcode1b-original-data-dpo-pvf-qsl | 🥉2386117.68 | 0.1111 |
| startcode1b-original-data-dpo-pvf-qfs | 2388721.33 | 0.1226 |
| sft-25-original-data-1b-dpo-pvf | 2390199.21 | 0.1429 |
| sft-25-original-data-1b-sft-1 | <font color="#E33D30">2426774.06</font> | 0.1283 |
| sft-25-original-data-1b-dpo-pvf-qfs | 2419096.29 | 🥈0.1699 |
| sft-25-original-data-1b-dpo-pvf-qts | 2399194.70 | 0.1525 |
| codedpo | 2392069.73 | <font color="#E33D30">0.0836</font> |
| sft-25-original-data-1b-dpo-qts | 2403430.52 | 0.1040 |
| sft-optimise | 2409526.18 | 0.1371 |
| optimise | 2395815.36 | 0.0837 |
| sft-25-original-data-1b-dpo-qra | 2389638.60 | 0.1678 |
| sft-25-original-data-1b | 2412874.89 | 0.0947 |

>比基准高效且比基准的pass@1高的有

`sft-pvf-qsl`

`sft-qfs`

`sft-pvf-qra`

`sft-qra`

>比基准更高效但是，pass@1差于基准的有

`pvf-qts`

`pvf-qra`

`pvf-qsl`

`pvf-qfs`

`sft-pvf`


### 对比基准: `sft-25-original-data-1b`

> **基准值: { 平均时间 (avg_time): 2412874.89, Pass@1: 0.0947 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-codedpo | <font color="#1ABD76">-11889.98</font> | 1.00x | <font color="#1ABD76">+0.0512</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-20909.50</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0750</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-32258.96</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0613</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-22898.13</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0766</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-12235.76</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0431</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-26234.82</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0021</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-28767.64</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0289</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-26757.20</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0164</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-24153.56</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0279</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-22675.68</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0482</font> |
| sft-25-original-data-1b-sft-1 | <font color="#E33D30">+13899.18</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0336</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+6221.40</font> | 1.00x | <font color="#1ABD76">+0.0752</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-13680.18</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0578</font> |
| codedpo | <font color="#1ABD76">-20805.16</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0111</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-9444.37</font> | 1.00x | <font color="#1ABD76">+0.0093</font> |
| sft-optimise | <font color="#1ABD76">-3348.70</font> | 1.00x | <font color="#1ABD76">+0.0424</font> |
| optimise | <font color="#1ABD76">-17059.53</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0110</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-23236.29</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0731</font> |

>对比sft微调`pvf-qts ,  codedpo , optimise`比sft高效，但是pass@1不如sft

>sft-pvf-qfs 效率和准确率都不如 sft
## mbpp

### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色</span>: 该列中的最差值。
* 🥇: 该列中的最佳值 (Pass@1 越高越好, 时间越低越好)。
* 🥈: 该列中的第二佳值。
* 🥉: 该列中的第三佳值。

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | 113046.06 | 0.1453 |
| sft-codedpo | 111384.71 | 0.1138 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | 117525.75 | 0.1305 |
| sft-25-original-data-1b-dpo-pvf-qsl | 123402.04 | 0.1351 |
| sft-25-original-data-1b-dpo-qfs | 111653.21 | 🥉0.1499 |
| sft-25-original-data-1b-dpo-pvf-qra | 120240.77 | 0.1342 |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | 121924.19 | 0.1198 |
| sft-25-original-data-1b-dpo-qsl | 117952.04 | 0.1399 |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | 118036.06 | 0.1258 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | 113499.44 | 0.1469 |
| startcode1b-original-data-dpo-pvf-qts | 109003.60 | 0.0706 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | 123876.02 | 0.1167 |
| startcode1b-original-data-dpo-pvf | 110234.59 | 0.0657 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | 114368.02 | 0.1447 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | 122107.74 | 0.1268 |
| startcode1b-original-data-dpo-pvf-qra | 🥇103704.80 | 0.0957 |
| startcode1b-original-data-dpo-pvf-qsl | 🥈104042.74 | 0.0922 |
| startcode1b-original-data-dpo-pvf-qfs | 🥉104079.26 | 0.1005 |
| sft-25-original-data-1b-dpo-pvf | 118963.15 | 0.1302 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | 118820.66 | 0.1360 |
| sft-25-original-data-1b-dpo-pvf-qfs | 115512.28 | 0.1306 |
| original-data | 111893.93 | 🥇1.0000 |
| sft-25-original-data-1b-dpo-pvf-qts | 131881.13 | 0.1205 |
| codedpo | 112972.16 | <font color="#E33D30">0.0620</font> |
| sft-25-original-data-1b-dpo-qts | 124349.25 | 0.1052 |
| startcode1b-original-data-sft-1 | <font color="#E33D30">152894.36</font> | 0.0875 |
| sft-optimise | 115403.10 | 0.1103 |
| optimise | 113053.20 | 0.0642 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | 113162.96 | 🥈0.1511 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | 120603.98 | 0.1373 |
| sft-25-original-data-1b-dpo-qra | 121600.25 | 0.1480 |
| sft-25-original-data-1b | 129490.12 | 0.0901 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | 127771.48 | 0.1370 |

> 在此数据集上没有一个方法是完全意义上战胜基准的，有sft-qfs在时间上与基础持平，在pass@1上比基准高3.6%

>时间上由于基准，pass@1低于基准的

`pvf-qts`

`pvf`

`pvf-qra`

`pvf-qsl`

`pvf-qfs`

### 对比基准: `sft-25-original-data-1b`

> **基准值: { 平均时间 (avg_time): 129490.12, Pass@1: 0.0901 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-16444.06</font> | <font color="#1ABD76">1.15x</font> | <font color="#1ABD76">+0.0552</font> |
| sft-codedpo | <font color="#1ABD76">-18105.41</font> | <font color="#1ABD76">1.16x</font> | <font color="#1ABD76">+0.0237</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#1ABD76">-11964.37</font> | <font color="#1ABD76">1.10x</font> | <font color="#1ABD76">+0.0404</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-6088.09</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0450</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-17836.92</font> | <font color="#1ABD76">1.16x</font> | <font color="#1ABD76">+0.0598</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-9249.35</font> | <font color="#1ABD76">1.08x</font> | <font color="#1ABD76">+0.0441</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#1ABD76">-7565.93</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0297</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-11538.08</font> | <font color="#1ABD76">1.10x</font> | <font color="#1ABD76">+0.0498</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#1ABD76">-11454.07</font> | <font color="#1ABD76">1.10x</font> | <font color="#1ABD76">+0.0357</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#1ABD76">-15990.69</font> | <font color="#1ABD76">1.14x</font> | <font color="#1ABD76">+0.0568</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-20486.52</font> | <font color="#1ABD76">1.19x</font> | <font color="#E33D30">-0.0195</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#1ABD76">-5614.11</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0266</font> |
| startcode1b-original-data-dpo-pvf | <font color="#1ABD76">-19255.53</font> | <font color="#1ABD76">1.17x</font> | <font color="#E33D30">-0.0244</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#1ABD76">-15122.11</font> | <font color="#1ABD76">1.13x</font> | <font color="#1ABD76">+0.0546</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#1ABD76">-7382.38</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0366</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-25785.32</font> | <font color="#1ABD76">1.25x</font> | <font color="#1ABD76">+0.0056</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-25447.38</font> | <font color="#1ABD76">1.24x</font> | <font color="#1ABD76">+0.0021</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-25410.86</font> | <font color="#1ABD76">1.24x</font> | <font color="#1ABD76">+0.0103</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-10526.97</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0401</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#1ABD76">-10669.46</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0459</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-13977.84</font> | <font color="#1ABD76">1.12x</font> | <font color="#1ABD76">+0.0404</font> |
| original-data | <font color="#1ABD76">-17596.19</font> | <font color="#1ABD76">1.16x</font> | <font color="#1ABD76">+0.9099</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#E33D30">+2391.00</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0304</font> |
| codedpo | <font color="#1ABD76">-16517.96</font> | <font color="#1ABD76">1.15x</font> | <font color="#E33D30">-0.0281</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-5140.87</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0151</font> |
| startcode1b-original-data-sft-1 | <font color="#E33D30">+23404.24</font> | <font color="#E33D30">0.85x</font> | <font color="#E33D30">-0.0026</font> |
| sft-optimise | <font color="#1ABD76">-14087.02</font> | <font color="#1ABD76">1.12x</font> | <font color="#1ABD76">+0.0202</font> |
| optimise | <font color="#1ABD76">-16436.92</font> | <font color="#1ABD76">1.15x</font> | <font color="#E33D30">-0.0259</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-16327.16</font> | <font color="#1ABD76">1.14x</font> | <font color="#1ABD76">+0.0610</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#1ABD76">-8886.14</font> | <font color="#1ABD76">1.07x</font> | <font color="#1ABD76">+0.0472</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-7889.87</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0579</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#1ABD76">-1718.64</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0468</font> |

> pvf-qts , opt, optimise 三个效率优于sft，但是pass@1 低于 sft

> sft-pvf-qts 效率不如sft



## humaneval

### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色</span>: 该列中的最差值。
* 🥇: 该列中的最佳值 (Pass@1 越高越好, 时间越低越好)。
* 🥈: 该列中的第二佳值。
* 🥉: 该列中的第三佳值。

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | 196514.11 | 0.1111 |
| sft-codedpo | 244828.90 | 0.0991 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | 224516.12 | 0.1122 |
| sft-25-original-data-1b-dpo-pvf-qsl | 203864.84 | 🥈0.1230 |
| sft-25-original-data-1b-dpo-qfs | 199572.95 | 0.1116 |
| sft-25-original-data-1b-dpo-pvf-qra | 147666.91 | 🥇0.1251 |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | 263421.74 | 0.1068 |
| sft-25-original-data-1b-dpo-qsl | 180508.80 | 0.1140 |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | 251714.85 | 0.1071 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | 152529.41 | 0.1187 |
| startcode1b-original-data-dpo-pvf-qts | 🥇126672.29 | 0.0727 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | 233361.19 | 0.1053 |
| startcode1b-original-data-dpo-pvf | <font color="#E33D30">321155.49</font> | 0.0730 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | 🥉142974.20 | 0.1182 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | 232347.74 | 0.1102 |
| startcode1b-original-data-dpo-pvf-qra | 205045.27 | 0.0825 |
| startcode1b-original-data-dpo-pvf-qsl | 188620.36 | 0.0764 |
| startcode1b-original-data-dpo-pvf-qfs | 305765.62 | 0.0809 |
| sft-25-original-data-1b-dpo-pvf | 163131.42 | 0.1185 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | 218110.18 | 0.1079 |
| sft-25-original-data-1b-dpo-pvf-qfs | 176009.49 | 0.1183 |
| sft-25-original-data-1b-dpo-pvf-qts | 148688.89 | 0.1184 |
| codedpo | 248412.54 | <font color="#E33D30">0.0704</font> |
| sft-25-original-data-1b-dpo-qts | 243661.31 | 0.1042 |
| startcode1b-original-data-sft-1 | 🥈133612.54 | 0.1005 |
| sft-optimise | 242294.59 | 0.1027 |
| optimise | 221468.64 | 0.0742 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | 188892.28 | 0.1124 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | 182894.67 | 0.1082 |
| sft-25-original-data-1b-dpo-qra | 162440.13 | 0.1204 |
| sft-25-original-data-1b | 300671.57 | 0.1014 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | 176834.83 | 🥉0.1209 |

> 效率和准确率优于基准的有

`sft-0.3qsl-0.2qts-0.5qfs`

`sft-pvf-qsl`

`sft-qfs`

`sft-pvf-qra`

`sft-qsl`

`sft-0.5qra-0.5qsl`

`sft-0.5qra-0.5qfs`

`sft-pvf`

`sft-0.5pvf-0.5qfs`

`sft-pvf-qfs`

`sft-pvf-qts`

`sft-0.5qsl-0.5qfs`

`sft-0.5pvf-0.5qsl`

`sft-0.5pvf-0.5qra`

`sft-qra`

> 效率比基准高但是pass@1不如基准

`pvf-qts`

`pvf-qra`

`pvf-qsl`

### 对比基准: `sft-25-original-data-1b`

> **基准值: { 平均时间 (avg_time): 300671.57, Pass@1: 0.1014 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-104157.45</font> | <font color="#1ABD76">1.53x</font> | <font color="#1ABD76">+0.0097</font> |
| sft-codedpo | <font color="#1ABD76">-55842.67</font> | <font color="#1ABD76">1.23x</font> | <font color="#E33D30">-0.0023</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#1ABD76">-76155.45</font> | <font color="#1ABD76">1.34x</font> | <font color="#1ABD76">+0.0108</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-96806.72</font> | <font color="#1ABD76">1.47x</font> | <font color="#1ABD76">+0.0216</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-101098.62</font> | <font color="#1ABD76">1.51x</font> | <font color="#1ABD76">+0.0102</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-153004.66</font> | <font color="#1ABD76">2.04x</font> | <font color="#1ABD76">+0.0237</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#1ABD76">-37249.83</font> | <font color="#1ABD76">1.14x</font> | <font color="#1ABD76">+0.0054</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-120162.77</font> | <font color="#1ABD76">1.67x</font> | <font color="#1ABD76">+0.0126</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#1ABD76">-48956.72</font> | <font color="#1ABD76">1.19x</font> | <font color="#1ABD76">+0.0057</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#1ABD76">-148142.16</font> | <font color="#1ABD76">1.97x</font> | <font color="#1ABD76">+0.0173</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-173999.28</font> | <font color="#1ABD76">2.37x</font> | <font color="#E33D30">-0.0287</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#1ABD76">-67310.38</font> | <font color="#1ABD76">1.29x</font> | <font color="#1ABD76">+0.0039</font> |
| startcode1b-original-data-dpo-pvf | <font color="#E33D30">+20483.92</font> | <font color="#E33D30">0.94x</font> | <font color="#E33D30">-0.0284</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#1ABD76">-157697.37</font> | <font color="#1ABD76">2.10x</font> | <font color="#1ABD76">+0.0168</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#1ABD76">-68323.83</font> | <font color="#1ABD76">1.29x</font> | <font color="#1ABD76">+0.0088</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-95626.30</font> | <font color="#1ABD76">1.47x</font> | <font color="#E33D30">-0.0189</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-112051.20</font> | <font color="#1ABD76">1.59x</font> | <font color="#E33D30">-0.0250</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#E33D30">+5094.05</font> | <font color="#E33D30">0.98x</font> | <font color="#E33D30">-0.0205</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-137540.15</font> | <font color="#1ABD76">1.84x</font> | <font color="#1ABD76">+0.0171</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#1ABD76">-82561.39</font> | <font color="#1ABD76">1.38x</font> | <font color="#1ABD76">+0.0065</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-124662.08</font> | <font color="#1ABD76">1.71x</font> | <font color="#1ABD76">+0.0169</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-151982.68</font> | <font color="#1ABD76">2.02x</font> | <font color="#1ABD76">+0.0170</font> |
| codedpo | <font color="#1ABD76">-52259.02</font> | <font color="#1ABD76">1.21x</font> | <font color="#E33D30">-0.0310</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-57010.25</font> | <font color="#1ABD76">1.23x</font> | <font color="#1ABD76">+0.0028</font> |
| startcode1b-original-data-sft-1 | <font color="#1ABD76">-167059.03</font> | <font color="#1ABD76">2.25x</font> | <font color="#E33D30">-0.0009</font> |
| sft-optimise | <font color="#1ABD76">-58376.97</font> | <font color="#1ABD76">1.24x</font> | <font color="#1ABD76">+0.0013</font> |
| optimise | <font color="#1ABD76">-79202.93</font> | <font color="#1ABD76">1.36x</font> | <font color="#E33D30">-0.0272</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-111779.29</font> | <font color="#1ABD76">1.59x</font> | <font color="#1ABD76">+0.0110</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#1ABD76">-117776.89</font> | <font color="#1ABD76">1.64x</font> | <font color="#1ABD76">+0.0068</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-138231.43</font> | <font color="#1ABD76">1.85x</font> | <font color="#1ABD76">+0.0190</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#1ABD76">-123836.74</font> | <font color="#1ABD76">1.70x</font> | <font color="#1ABD76">+0.0195</font> |

> 效率优于sft但是pass@1低于 sft有

`sft-codedpo` 

`pvf-qts`

`pvf-qra`

`pvf-qsl` 

`codedpo`

`optimise`

> 效率和pass@1都不如sft

`pvf`

`pvf-qfs`



## humanevalplus

--- [开始生成表格] ---
### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色</span>: 该列中的最差值。
* 🥇: 该列中的最佳值 (Pass@1 越高越好, 时间越低越好)。
* 🥈: 该列中的第二佳值。
* 🥉: 该列中的第三佳值。

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| sft-codedpo | <font color="#E33D30">13759895.34</font> | 0.0666 |
| sft-25-original-data-1b-dpo-pvf-qsl | 🥇12553206.40 | 🥈0.0857 |
| sft-25-original-data-1b-dpo-qfs | 13341700.30 | 0.0730 |
| sft-25-original-data-1b-dpo-pvf-qra | 🥈12802731.54 | 🥇0.0894 |
| sft-25-original-data-1b-dpo-qsl | 13067472.07 | 0.0760 |
| startcode1b-original-data-dpo-pvf-qts | 12986944.58 | 0.0565 |
| startcode1b-original-data-dpo-pvf-qra | 13154605.51 | 0.0637 |
| startcode1b-original-data-dpo-pvf-qsl | 12996166.07 | 0.0577 |
| startcode1b-original-data-dpo-pvf-qfs | 13264023.90 | 0.0602 |
| sft-25-original-data-1b-dpo-pvf | 13141814.67 | 0.0823 |
| sft-25-original-data-1b-sft-1 | 13010269.05 | 0.0707 |
| sft-25-original-data-1b-dpo-pvf-qfs | 13044557.88 | 🥉0.0843 |
| sft-25-original-data-1b-dpo-pvf-qts | 12995184.77 | 0.0799 |
| codedpo | 13546593.57 | <font color="#E33D30">0.0518</font> |
| sft-25-original-data-1b-dpo-qts | 13060078.53 | 0.0657 |
| sft-optimise | 13672029.98 | 0.0691 |
| optimise | 13722836.70 | 0.0541 |
| sft-25-original-data-1b-dpo-qra | 13015695.05 | 0.0802 |
| sft-25-original-data-1b | 🥉12900094.60 | 0.0668 |


> 效率，准确率优于基准的是
`sft-pvf-qsl`

`sft-qfs`

`sft-pvf-qra`

`sft-qsl`

`sft-pvf`

`sft-pvf-qfs`

`sft-pvf-qts`

`sft-qra`

> 效率优于基准 pass@1 低于基准

`pvf-qts`

`pvf-qra`

`pvf-qsl`

`pvf-qfs`

`sft-qts`

`pvf`


### 对比基准: `sft-25-original-data-1b`

> **基准值: { 平均时间 (avg_time): 12900094.60, Pass@1: 0.0668 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-codedpo | <font color="#E33D30">+859800.73</font> | <font color="#E33D30">0.94x</font> | <font color="#E33D30">-0.0002</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-346888.20</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0189</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#E33D30">+441605.70</font> | <font color="#E33D30">0.97x</font> | <font color="#1ABD76">+0.0062</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-97363.07</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0226</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#E33D30">+167377.47</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0092</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#E33D30">+86849.98</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0104</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#E33D30">+254510.91</font> | <font color="#E33D30">0.98x</font> | <font color="#E33D30">-0.0032</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#E33D30">+96071.47</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0091</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#E33D30">+363929.29</font> | <font color="#E33D30">0.97x</font> | <font color="#E33D30">-0.0066</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#E33D30">+241720.07</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0155</font> |
| sft-25-original-data-1b-sft-1 | <font color="#E33D30">+110174.45</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0039</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+144463.27</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0174</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#E33D30">+95090.17</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0130</font> |
| codedpo | <font color="#E33D30">+646498.97</font> | <font color="#E33D30">0.95x</font> | <font color="#E33D30">-0.0150</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+159983.93</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0011</font> |
| sft-optimise | <font color="#E33D30">+771935.38</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0023</font> |
| optimise | <font color="#E33D30">+822742.09</font> | <font color="#E33D30">0.94x</font> | <font color="#E33D30">-0.0127</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#E33D30">+115600.44</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0134</font> |


> 效率，准确率优于sft的

`sft-pvf-qsl`

`sft-pvf-qra`

## 总结

* pvf-qts, pvf-qra, pvf-qsl在数据集mbpp, mbpp+, humaneval, humaneval+上效率优于基准。但是pass@1不如基准。

* sft-qfs, sft-pvf-qsl, sft-pvf-qra, sft-qra在humaneval, humaneval+, mbpp+优于基准。sft-qfs在mbpp上效率与基准持平, 正确率优于基准。


* sft-qfs, sft-qra在humaneval+数据集上的效率不如sft。

总之，sft-pvf-qsl, sft-pvf-qra在humaneval, humaneval+, mbpp+三个数据集上优于基准和sft。sft-qfs在mbpp+, humaneval, humaneval+三个数据集上优于基准，在mbpp上效率与基准持平，准确率优于基准，但是在humaneval+上不如sft。
