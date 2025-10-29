
@[toc]


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



--- [开始生成对比表格] ---

==============================

### 对比基准: `deepseek1.3b-original-data-25-sft-dpo-all`

> **基准值: { 平均时间 (avg_time): 190873.82, Pass@1: 0.1810 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+3543.56</font> | <font color="#1ABD76">+0.0638</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-4651.46</font> | <font color="#1ABD76">+0.0084</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#E33D30">+202.71</font> | <font color="#1ABD76">+0.0820</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#E33D30">+3107.41</font> | <font color="#E33D30">-0.0197</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-4668.50</font> | <font color="#1ABD76">+0.0018</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#E33D30">+1806.93</font> | <font color="#E33D30">-0.0177</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#E33D30">+2126.99</font> | <font color="#E33D30">-0.0142</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#E33D30">+1667.91</font> | <font color="#E33D30">-0.0143</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+5838.33</font> | <font color="#1ABD76">+0.0186</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-1256.55</font> | <font color="#1ABD76">+0.0402</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#E33D30">+3503.11</font> | <font color="#1ABD76">+0.0251</font> |
| deepseek1.3b-original-data-25-sft | <font color="#E33D30">+3228.08</font> | <font color="#1ABD76">+0.0166</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">+12127.87</font> | <font color="#E33D30">-0.0151</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-15949.59</font> | <font color="#1ABD76">+0.0836</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#E33D30">+5802.76</font> | <font color="#E33D30">-0.0044</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#E33D30">+8663.09</font> | <font color="#1ABD76">+0.0215</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-25-sft-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 196676.58, Pass@1: 0.1766 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#1ABD76">-2259.21</font> | <font color="#1ABD76">+0.0682</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-10454.22</font> | <font color="#1ABD76">+0.0128</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-5600.05</font> | <font color="#1ABD76">+0.0864</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#1ABD76">-2695.35</font> | <font color="#E33D30">-0.0153</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-10471.26</font> | <font color="#1ABD76">+0.0062</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-3995.84</font> | <font color="#E33D30">-0.0133</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-3675.77</font> | <font color="#E33D30">-0.0098</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-4134.85</font> | <font color="#E33D30">-0.0099</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+35.57</font> | <font color="#1ABD76">+0.0230</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-7059.31</font> | <font color="#1ABD76">+0.0446</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-5802.76</font> | <font color="#1ABD76">+0.0044</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#1ABD76">-2299.65</font> | <font color="#1ABD76">+0.0295</font> |
| deepseek1.3b-original-data-25-sft | <font color="#1ABD76">-2574.68</font> | <font color="#1ABD76">+0.0210</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">+6325.11</font> | <font color="#E33D30">-0.0107</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-21752.35</font> | <font color="#1ABD76">+0.0880</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#E33D30">+2860.33</font> | <font color="#1ABD76">+0.0259</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-dpo-all`

> **基准值: { 平均时间 (avg_time): 192680.75, Pass@1: 0.1633 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+1736.63</font> | <font color="#1ABD76">+0.0815</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-6458.38</font> | <font color="#1ABD76">+0.0261</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-1604.22</font> | <font color="#1ABD76">+0.0997</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#E33D30">+1300.48</font> | <font color="#E33D30">-0.0020</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-6475.43</font> | <font color="#1ABD76">+0.0195</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#E33D30">+320.07</font> | <font color="#1ABD76">+0.0035</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-139.02</font> | <font color="#1ABD76">+0.0034</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+4031.41</font> | <font color="#1ABD76">+0.0363</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-3063.48</font> | <font color="#1ABD76">+0.0579</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-1806.93</font> | <font color="#1ABD76">+0.0177</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#E33D30">+1696.18</font> | <font color="#1ABD76">+0.0428</font> |
| deepseek1.3b-original-data-25-sft | <font color="#E33D30">+1421.15</font> | <font color="#1ABD76">+0.0343</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">+10320.95</font> | <font color="#1ABD76">+0.0026</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-17756.52</font> | <font color="#1ABD76">+0.1013</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#E33D30">+3995.84</font> | <font color="#1ABD76">+0.0133</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#E33D30">+6856.17</font> | <font color="#1ABD76">+0.0392</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 193981.23, Pass@1: 0.1613 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+436.15</font> | <font color="#1ABD76">+0.0835</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-7758.87</font> | <font color="#1ABD76">+0.0281</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-2904.70</font> | <font color="#1ABD76">+0.1017</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-7775.91</font> | <font color="#1ABD76">+0.0215</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-1300.48</font> | <font color="#1ABD76">+0.0020</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-980.41</font> | <font color="#1ABD76">+0.0055</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-1439.50</font> | <font color="#1ABD76">+0.0054</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+2730.93</font> | <font color="#1ABD76">+0.0383</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-4363.96</font> | <font color="#1ABD76">+0.0599</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-3107.41</font> | <font color="#1ABD76">+0.0197</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#E33D30">+395.70</font> | <font color="#1ABD76">+0.0448</font> |
| deepseek1.3b-original-data-25-sft | <font color="#E33D30">+120.67</font> | <font color="#1ABD76">+0.0363</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">+9020.46</font> | <font color="#1ABD76">+0.0046</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-19057.00</font> | <font color="#1ABD76">+0.1033</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#E33D30">+2695.35</font> | <font color="#1ABD76">+0.0153</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#E33D30">+5555.68</font> | <font color="#1ABD76">+0.0412</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-25-sft`

> **基准值: { 平均时间 (avg_time): 194101.90, Pass@1: 0.1976 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+315.48</font> | <font color="#1ABD76">+0.0472</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-7879.54</font> | <font color="#E33D30">-0.0082</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-3025.37</font> | <font color="#1ABD76">+0.0654</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#1ABD76">-120.67</font> | <font color="#E33D30">-0.0363</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-7896.58</font> | <font color="#E33D30">-0.0148</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-1421.15</font> | <font color="#E33D30">-0.0343</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-1101.09</font> | <font color="#E33D30">-0.0308</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-1560.17</font> | <font color="#E33D30">-0.0309</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+2610.25</font> | <font color="#1ABD76">+0.0020</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-4484.63</font> | <font color="#1ABD76">+0.0236</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-3228.08</font> | <font color="#E33D30">-0.0166</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#E33D30">+275.03</font> | <font color="#1ABD76">+0.0085</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">+8899.79</font> | <font color="#E33D30">-0.0317</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-19177.67</font> | <font color="#1ABD76">+0.0670</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#E33D30">+2574.68</font> | <font color="#E33D30">-0.0210</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#E33D30">+5435.01</font> | <font color="#1ABD76">+0.0049</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-sft-1`

> **基准值: { 平均时间 (avg_time): 196712.15, Pass@1: 0.1996 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#1ABD76">-2294.78</font> | <font color="#1ABD76">+0.0452</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-10489.79</font> | <font color="#E33D30">-0.0102</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-5635.63</font> | <font color="#1ABD76">+0.0634</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#1ABD76">-2730.93</font> | <font color="#E33D30">-0.0383</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-10506.84</font> | <font color="#E33D30">-0.0168</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-4031.41</font> | <font color="#E33D30">-0.0363</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-3711.34</font> | <font color="#E33D30">-0.0328</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-4170.43</font> | <font color="#E33D30">-0.0329</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-7094.88</font> | <font color="#1ABD76">+0.0216</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-5838.33</font> | <font color="#E33D30">-0.0186</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#1ABD76">-2335.22</font> | <font color="#1ABD76">+0.0065</font> |
| deepseek1.3b-original-data-25-sft | <font color="#1ABD76">-2610.25</font> | <font color="#E33D30">-0.0020</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">+6289.54</font> | <font color="#E33D30">-0.0337</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-21787.92</font> | <font color="#1ABD76">+0.0650</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#1ABD76">-35.57</font> | <font color="#E33D30">-0.0230</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#E33D30">+2824.76</font> | <font color="#1ABD76">+0.0029</font> |


## mbpp
--- [开始生成表格] ---
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



--- [开始生成对比表格] ---

==============================

### 对比基准: `deepseek1.3b-original-data-25-sft-dpo-all`

> **基准值: { 平均时间 (avg_time): 126682.58, Pass@1: 0.1394 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+18519.38</font> | <font color="#1ABD76">+0.1092</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-1145.57</font> | <font color="#1ABD76">+0.0298</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-10367.73</font> | <font color="#1ABD76">+0.1458</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#E33D30">+8376.36</font> | <font color="#E33D30">-0.0259</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#E33D30">+4134.18</font> | <font color="#1ABD76">+0.0174</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#E33D30">+2646.83</font> | <font color="#E33D30">-0.0290</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#E33D30">+2190.73</font> | <font color="#E33D30">-0.0176</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#E33D30">+2818.59</font> | <font color="#E33D30">-0.0176</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+3287.85</font> | <font color="#1ABD76">+0.0170</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-7332.39</font> | <font color="#1ABD76">+0.0813</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#E33D30">+705.62</font> | <font color="#1ABD76">+0.0398</font> |
| deepseek1.3b-original-data-25-sft | <font color="#E33D30">+5500.16</font> | <font color="#1ABD76">+0.0188</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#1ABD76">-718.58</font> | <font color="#E33D30">-0.0258</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-7590.94</font> | <font color="#1ABD76">+0.1466</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#1ABD76">-3552.64</font> | <font color="#E33D30">-0.0043</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#1ABD76">-9654.86</font> | <font color="#1ABD76">+0.0633</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-25-sft-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 123129.94, Pass@1: 0.1351 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+22072.02</font> | <font color="#1ABD76">+0.1135</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#E33D30">+2407.06</font> | <font color="#1ABD76">+0.0341</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-6815.09</font> | <font color="#1ABD76">+0.1501</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#E33D30">+11929.00</font> | <font color="#E33D30">-0.0216</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#E33D30">+7686.82</font> | <font color="#1ABD76">+0.0217</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#E33D30">+6199.47</font> | <font color="#E33D30">-0.0247</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#E33D30">+5743.37</font> | <font color="#E33D30">-0.0133</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#E33D30">+6371.23</font> | <font color="#E33D30">-0.0133</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+6840.48</font> | <font color="#1ABD76">+0.0213</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-3779.75</font> | <font color="#1ABD76">+0.0856</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#E33D30">+3552.64</font> | <font color="#1ABD76">+0.0043</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#E33D30">+4258.26</font> | <font color="#1ABD76">+0.0441</font> |
| deepseek1.3b-original-data-25-sft | <font color="#E33D30">+9052.80</font> | <font color="#1ABD76">+0.0231</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#E33D30">+2834.05</font> | <font color="#E33D30">-0.0215</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-4038.31</font> | <font color="#1ABD76">+0.1509</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#1ABD76">-6102.22</font> | <font color="#1ABD76">+0.0676</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-dpo-all`

> **基准值: { 平均时间 (avg_time): 129329.41, Pass@1: 0.1104 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+15872.55</font> | <font color="#1ABD76">+0.1383</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-3792.41</font> | <font color="#1ABD76">+0.0589</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-13014.56</font> | <font color="#1ABD76">+0.1748</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#E33D30">+5729.53</font> | <font color="#1ABD76">+0.0031</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#E33D30">+1487.35</font> | <font color="#1ABD76">+0.0465</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-456.10</font> | <font color="#1ABD76">+0.0114</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#E33D30">+171.76</font> | <font color="#1ABD76">+0.0114</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#E33D30">+641.01</font> | <font color="#1ABD76">+0.0461</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-9979.22</font> | <font color="#1ABD76">+0.1103</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-2646.83</font> | <font color="#1ABD76">+0.0290</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#1ABD76">-1941.21</font> | <font color="#1ABD76">+0.0689</font> |
| deepseek1.3b-original-data-25-sft | <font color="#E33D30">+2853.33</font> | <font color="#1ABD76">+0.0479</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#1ABD76">-3365.42</font> | <font color="#1ABD76">+0.0033</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-10237.78</font> | <font color="#1ABD76">+0.1757</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#1ABD76">-6199.47</font> | <font color="#1ABD76">+0.0247</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#1ABD76">-12301.69</font> | <font color="#1ABD76">+0.0923</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 135058.94, Pass@1: 0.1135 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+10143.02</font> | <font color="#1ABD76">+0.1352</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-9521.94</font> | <font color="#1ABD76">+0.0558</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-18744.09</font> | <font color="#1ABD76">+0.1717</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-4242.18</font> | <font color="#1ABD76">+0.0434</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-5729.53</font> | <font color="#E33D30">-0.0031</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-6185.63</font> | <font color="#1ABD76">+0.0083</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-5557.77</font> | <font color="#1ABD76">+0.0083</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#1ABD76">-5088.52</font> | <font color="#1ABD76">+0.0430</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-15708.75</font> | <font color="#1ABD76">+0.1072</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-8376.36</font> | <font color="#1ABD76">+0.0259</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#1ABD76">-7670.74</font> | <font color="#1ABD76">+0.0658</font> |
| deepseek1.3b-original-data-25-sft | <font color="#1ABD76">-2876.20</font> | <font color="#1ABD76">+0.0448</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#1ABD76">-9094.94</font> | <font color="#1ABD76">+0.0002</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-15967.31</font> | <font color="#1ABD76">+0.1726</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#1ABD76">-11929.00</font> | <font color="#1ABD76">+0.0216</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#1ABD76">-18031.22</font> | <font color="#1ABD76">+0.0892</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-25-sft`

> **基准值: { 平均时间 (avg_time): 132182.73, Pass@1: 0.1583 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+13019.23</font> | <font color="#1ABD76">+0.0904</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-6645.73</font> | <font color="#1ABD76">+0.0110</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-15867.88</font> | <font color="#1ABD76">+0.1269</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#E33D30">+2876.20</font> | <font color="#E33D30">-0.0448</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#1ABD76">-1365.98</font> | <font color="#E33D30">-0.0014</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-2853.33</font> | <font color="#E33D30">-0.0479</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-3309.43</font> | <font color="#E33D30">-0.0365</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-2681.56</font> | <font color="#E33D30">-0.0365</font> |
| deepseek1.3b-original-data-sft-1 | <font color="#1ABD76">-2212.31</font> | <font color="#E33D30">-0.0018</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-12832.55</font> | <font color="#1ABD76">+0.0624</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-5500.16</font> | <font color="#E33D30">-0.0188</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#1ABD76">-4794.54</font> | <font color="#1ABD76">+0.0210</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#1ABD76">-6218.74</font> | <font color="#E33D30">-0.0446</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-13091.10</font> | <font color="#1ABD76">+0.1278</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#1ABD76">-9052.80</font> | <font color="#E33D30">-0.0231</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#1ABD76">-15155.02</font> | <font color="#1ABD76">+0.0445</font> |


==============================

### 对比基准: `deepseek1.3b-original-data-sft-1`

> **基准值: { 平均时间 (avg_time): 129970.42, Pass@1: 0.1565 }**

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font color="#E33D30">+15231.54</font> | <font color="#1ABD76">+0.0922</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-4433.42</font> | <font color="#1ABD76">+0.0128</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font color="#1ABD76">-13655.57</font> | <font color="#1ABD76">+0.1287</font> |
| deepseek1.3b-original-data-dpo-codedpo | <font color="#E33D30">+5088.52</font> | <font color="#E33D30">-0.0430</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | <font color="#E33D30">+846.34</font> | <font color="#1ABD76">+0.0004</font> |
| deepseek1.3b-original-data-dpo-all | <font color="#1ABD76">-641.01</font> | <font color="#E33D30">-0.0461</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-1097.12</font> | <font color="#E33D30">-0.0347</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font color="#1ABD76">-469.25</font> | <font color="#E33D30">-0.0347</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font color="#1ABD76">-10620.23</font> | <font color="#1ABD76">+0.0642</font> |
| deepseek1.3b-original-data-25-sft-dpo-all | <font color="#1ABD76">-3287.85</font> | <font color="#E33D30">-0.0170</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font color="#1ABD76">-2582.23</font> | <font color="#1ABD76">+0.0228</font> |
| deepseek1.3b-original-data-25-sft | <font color="#E33D30">+2212.31</font> | <font color="#1ABD76">+0.0018</font> |
| deepseek1.3b-original-data-dpo-pvf | <font color="#1ABD76">-4006.43</font> | <font color="#E33D30">-0.0428</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font color="#1ABD76">-10878.79</font> | <font color="#1ABD76">+0.1296</font> |
| deepseek1.3b-original-data-25-sft-dpo-codedpo | <font color="#1ABD76">-6840.48</font> | <font color="#E33D30">-0.0213</font> |
| deepseek1.3b-original-data-dpo-qfs | <font color="#1ABD76">-12942.71</font> | <font color="#1ABD76">+0.0462</font> |


--- [所有表格生成完毕] ---
