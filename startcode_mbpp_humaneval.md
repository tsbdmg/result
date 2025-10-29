@[toc]
##  mbppplus
--- [开始生成表格] ---
### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色</span>: 该列中的最差值。
* 🥇: 该列中的最佳值 (Pass@1 越高越好, 时间越低越好)。
* 🥈: 该列中的第二佳值。
* 🥉: 该列中的第三佳值。

| 模型 (Model) | 平均时间 (avg_time) | Pass@1 |
| :--- |  :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | 2400984.91 | 0.1459 |
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
| startcode1b-original-data-dpo-codedpo | 2392069.73 | <font color="#E33D30">0.0836</font> |
| sft-25-original-data-1b-dpo-qts | 2403430.52 | 0.1040 |
| sft-25-original-data-1b-dpo-all | 2409526.18 | 0.1371 |
| startcode1b-original-data-dpo-all | 2395815.36 | 0.0837 |
| sft-25-original-data-1b-dpo-qra | 2389638.60 | 0.1678 |
| sft-25-original-data-1b | 2412874.89 | 0.0947 |



--- [开始生成对比表格] ---

==============================

### 对比基准: `sft-25-original-data-1b-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 2400984.91, Pass@1: 0.1459 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-9019.52</font> | 1.00x | <font color="#1ABD76">+0.0238</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-20368.98</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0101</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-11008.15</font> | 1.00x | <font color="#1ABD76">+0.0253</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-345.78</font> | 1.00x | <font color="#E33D30">-0.0081</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-14344.84</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0533</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-16877.66</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0223</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-14867.22</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0348</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-12263.58</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0233</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-10785.70</font> | 1.00x | <font color="#E33D30">-0.0030</font> |
| sft-25-original-data-1b-sft-1 | <font color="#E33D30">+25789.15</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0176</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+18111.38</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0240</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-1790.20</font> | 1.00x | <font color="#1ABD76">+0.0066</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-8915.18</font> | 1.00x | <font color="#E33D30">-0.0624</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+2445.61</font> | 1.00x | <font color="#E33D30">-0.0419</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+8541.28</font> | 1.00x | <font color="#E33D30">-0.0088</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-5169.55</font> | 1.00x | <font color="#E33D30">-0.0622</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-11346.31</font> | 1.00x | <font color="#1ABD76">+0.0219</font> |
| sft-25-original-data-1b | <font color="#E33D30">+11889.98</font> | 1.00x | <font color="#E33D30">-0.0512</font> |


==============================

### 对比基准: `sft-25-original-data-1b-dpo-all`

> **基准值: { 平均时间 (avg_time): 2409526.18, Pass@1: 0.1371 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-8541.28</font> | 1.00x | <font color="#1ABD76">+0.0088</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-17560.80</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0326</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-28910.26</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0188</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-19549.43</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0341</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-8887.06</font> | 1.00x | <font color="#1ABD76">+0.0007</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-22886.12</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0446</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-25418.94</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0135</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-23408.50</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0260</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-20804.86</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0145</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-19326.98</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0058</font> |
| sft-25-original-data-1b-sft-1 | <font color="#E33D30">+17247.88</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0088</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+9570.10</font> | 1.00x | <font color="#1ABD76">+0.0328</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-10331.48</font> | 1.00x | <font color="#1ABD76">+0.0154</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-17456.45</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0536</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-6095.67</font> | 1.00x | <font color="#E33D30">-0.0331</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-13710.83</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0534</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-19887.58</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0307</font> |
| sft-25-original-data-1b | <font color="#E33D30">+3348.70</font> | 1.00x | <font color="#E33D30">-0.0424</font> |


==============================

### 对比基准: `startcode1b-original-data-dpo-all`

> **基准值: { 平均时间 (avg_time): 2395815.36, Pass@1: 0.0837 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+5169.55</font> | 1.00x | <font color="#1ABD76">+0.0622</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-3849.98</font> | 1.00x | <font color="#1ABD76">+0.0860</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-15199.43</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0722</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-5838.60</font> | 1.00x | <font color="#1ABD76">+0.0875</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#E33D30">+4823.77</font> | 1.00x | <font color="#1ABD76">+0.0541</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-9175.29</font> | 1.00x | <font color="#1ABD76">+0.0089</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-11708.11</font> | 1.00x | <font color="#1ABD76">+0.0399</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-9697.68</font> | 1.00x | <font color="#1ABD76">+0.0274</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-7094.03</font> | 1.00x | <font color="#1ABD76">+0.0389</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-5616.15</font> | 1.00x | <font color="#1ABD76">+0.0592</font> |
| sft-25-original-data-1b-sft-1 | <font color="#E33D30">+30958.70</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0446</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+23280.93</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0862</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#E33D30">+3379.35</font> | 1.00x | <font color="#1ABD76">+0.0688</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-3745.63</font> | 1.00x | <font color="#E33D30">-0.0002</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+7615.16</font> | 1.00x | <font color="#1ABD76">+0.0203</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+13710.83</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0534</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-6176.76</font> | 1.00x | <font color="#1ABD76">+0.0841</font> |
| sft-25-original-data-1b | <font color="#E33D30">+17059.53</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0110</font> |


==============================

### 对比基准: `startcode1b-original-data-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 2392069.73, Pass@1: 0.0836 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+8915.18</font> | 1.00x | <font color="#1ABD76">+0.0624</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-104.35</font> | 1.00x | <font color="#1ABD76">+0.0861</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-11453.80</font> | 1.00x | <font color="#1ABD76">+0.0724</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-2092.97</font> | 1.00x | <font color="#1ABD76">+0.0877</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#E33D30">+8569.39</font> | 1.00x | <font color="#1ABD76">+0.0543</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-5429.66</font> | 1.00x | <font color="#1ABD76">+0.0090</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-7962.49</font> | 1.00x | <font color="#1ABD76">+0.0401</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-5952.05</font> | 1.00x | <font color="#1ABD76">+0.0276</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-3348.40</font> | 1.00x | <font color="#1ABD76">+0.0390</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-1870.52</font> | 1.00x | <font color="#1ABD76">+0.0593</font> |
| sft-25-original-data-1b-sft-1 | <font color="#E33D30">+34704.33</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0448</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+27026.56</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0863</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#E33D30">+7124.97</font> | 1.00x | <font color="#1ABD76">+0.0689</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+11360.79</font> | 1.00x | <font color="#1ABD76">+0.0205</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+17456.45</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0536</font> |
| startcode1b-original-data-dpo-all | <font color="#E33D30">+3745.63</font> | 1.00x | <font color="#1ABD76">+0.0002</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-2431.13</font> | 1.00x | <font color="#1ABD76">+0.0843</font> |
| sft-25-original-data-1b | <font color="#E33D30">+20805.16</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0111</font> |


==============================

### 对比基准: `sft-25-original-data-1b`

> **基准值: { 平均时间 (avg_time): 2412874.89, Pass@1: 0.0947 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-11889.98</font> | 1.00x | <font color="#1ABD76">+0.0512</font> |
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
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-20805.16</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0111</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-9444.37</font> | 1.00x | <font color="#1ABD76">+0.0093</font> |
| sft-25-original-data-1b-dpo-all | <font color="#1ABD76">-3348.70</font> | 1.00x | <font color="#1ABD76">+0.0424</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-17059.53</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0110</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-23236.29</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0731</font> |


==============================

### 对比基准: `sft-25-original-data-1b-sft-1`

> **基准值: { 平均时间 (avg_time): 2426774.06, Pass@1: 0.1283 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-25789.15</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0176</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-34808.68</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0414</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-46158.14</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0276</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-36797.31</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0429</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-26134.94</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0095</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-40134.00</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0357</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-42666.82</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0047</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-40656.38</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0172</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-38052.73</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0057</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-36574.86</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0146</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-7677.78</font> | 1.00x | <font color="#1ABD76">+0.0416</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-27579.36</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0242</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-34704.33</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0448</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-23343.55</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0243</font> |
| sft-25-original-data-1b-dpo-all | <font color="#1ABD76">-17247.88</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0088</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-30958.70</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0446</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-37135.46</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0395</font> |
| sft-25-original-data-1b | <font color="#1ABD76">-13899.18</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0336</font> |



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
| sft-25-original-data-1b-dpo-codedpo | 111384.71 | 0.1138 |
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
| startcode1b-original-data-dpo-codedpo | 112972.16 | <font color="#E33D30">0.0620</font> |
| sft-25-original-data-1b-dpo-qts | 124349.25 | 0.1052 |
| startcode1b-original-data-sft-1 | <font color="#E33D30">152894.36</font> | 0.0875 |
| sft-25-original-data-1b-dpo-all | 115403.10 | 0.1103 |
| startcode1b-original-data-dpo-all | 113053.20 | 0.0642 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | 113162.96 | 🥈0.1511 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | 120603.98 | 0.1373 |
| sft-25-original-data-1b-dpo-qra | 121600.25 | 0.1480 |
| sft-25-original-data-1b | 129490.12 | 0.0901 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | 127771.48 | 0.1370 |



--- [开始生成对比表格] ---

==============================

### 对比基准: `sft-25-original-data-1b-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 111384.71, Pass@1: 0.1138 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#E33D30">+1661.35</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0315</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#E33D30">+6141.04</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0167</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#E33D30">+12017.32</font> | <font color="#E33D30">0.90x</font> | <font color="#1ABD76">+0.0213</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#E33D30">+268.49</font> | 1.00x | <font color="#1ABD76">+0.0361</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#E33D30">+8856.06</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0204</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#E33D30">+10539.48</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0060</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#E33D30">+6567.33</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0261</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#E33D30">+6651.34</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0120</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#E33D30">+2114.72</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0331</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-2381.11</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0432</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#E33D30">+12491.30</font> | <font color="#E33D30">0.90x</font> | <font color="#1ABD76">+0.0029</font> |
| startcode1b-original-data-dpo-pvf | <font color="#1ABD76">-1150.12</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0481</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#E33D30">+2983.30</font> | <font color="#E33D30">0.97x</font> | <font color="#1ABD76">+0.0309</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#E33D30">+10723.03</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0130</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-7679.91</font> | <font color="#1ABD76">1.07x</font> | <font color="#E33D30">-0.0181</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-7341.97</font> | <font color="#1ABD76">1.07x</font> | <font color="#E33D30">-0.0216</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-7305.45</font> | <font color="#1ABD76">1.07x</font> | <font color="#E33D30">-0.0134</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#E33D30">+7578.44</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0164</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#E33D30">+7435.95</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0222</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+4127.57</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0167</font> |
| original-data | <font color="#E33D30">+509.22</font> | 1.00x | <font color="#1ABD76">+0.8862</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#E33D30">+20496.41</font> | <font color="#E33D30">0.84x</font> | <font color="#1ABD76">+0.0067</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#E33D30">+1587.45</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0518</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+12964.54</font> | <font color="#E33D30">0.90x</font> | <font color="#E33D30">-0.0086</font> |
| startcode1b-original-data-sft-1 | <font color="#E33D30">+41509.65</font> | <font color="#E33D30">0.73x</font> | <font color="#E33D30">-0.0263</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+4018.39</font> | <font color="#E33D30">0.97x</font> | <font color="#E33D30">-0.0035</font> |
| startcode1b-original-data-dpo-all | <font color="#E33D30">+1668.49</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0496</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#E33D30">+1778.25</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0373</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#E33D30">+9219.27</font> | <font color="#E33D30">0.92x</font> | <font color="#1ABD76">+0.0235</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#E33D30">+10215.54</font> | <font color="#E33D30">0.92x</font> | <font color="#1ABD76">+0.0342</font> |
| sft-25-original-data-1b | <font color="#E33D30">+18105.41</font> | <font color="#E33D30">0.86x</font> | <font color="#E33D30">-0.0237</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#E33D30">+16386.77</font> | <font color="#E33D30">0.87x</font> | <font color="#1ABD76">+0.0232</font> |


==============================

### 对比基准: `sft-25-original-data-1b-dpo-all`

> **基准值: { 平均时间 (avg_time): 115403.10, Pass@1: 0.1103 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-2357.04</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0350</font> |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-4018.39</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0035</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#E33D30">+2122.65</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0202</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#E33D30">+7998.93</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0248</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-3749.90</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0396</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#E33D30">+4837.67</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0239</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#E33D30">+6521.09</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0095</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#E33D30">+2548.94</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0296</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#E33D30">+2632.95</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0155</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#1ABD76">-1903.67</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0366</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-6399.50</font> | <font color="#1ABD76">1.06x</font> | <font color="#E33D30">-0.0397</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#E33D30">+8472.91</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0064</font> |
| startcode1b-original-data-dpo-pvf | <font color="#1ABD76">-5168.51</font> | <font color="#1ABD76">1.05x</font> | <font color="#E33D30">-0.0446</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#1ABD76">-1035.09</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0344</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#E33D30">+6704.64</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0165</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-11698.30</font> | <font color="#1ABD76">1.11x</font> | <font color="#E33D30">-0.0146</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-11360.36</font> | <font color="#1ABD76">1.11x</font> | <font color="#E33D30">-0.0181</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-11323.84</font> | <font color="#1ABD76">1.11x</font> | <font color="#E33D30">-0.0098</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#E33D30">+3560.05</font> | <font color="#E33D30">0.97x</font> | <font color="#1ABD76">+0.0199</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#E33D30">+3417.56</font> | <font color="#E33D30">0.97x</font> | <font color="#1ABD76">+0.0257</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+109.18</font> | 1.00x | <font color="#1ABD76">+0.0203</font> |
| original-data | <font color="#1ABD76">-3509.17</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.8897</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#E33D30">+16478.02</font> | <font color="#E33D30">0.88x</font> | <font color="#1ABD76">+0.0102</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-2430.94</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0483</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+8946.15</font> | <font color="#E33D30">0.93x</font> | <font color="#E33D30">-0.0051</font> |
| startcode1b-original-data-sft-1 | <font color="#E33D30">+37491.26</font> | <font color="#E33D30">0.75x</font> | <font color="#E33D30">-0.0228</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-2349.90</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0461</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-2240.14</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0408</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#E33D30">+5200.88</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0270</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#E33D30">+6197.15</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0377</font> |
| sft-25-original-data-1b | <font color="#E33D30">+14087.02</font> | <font color="#E33D30">0.89x</font> | <font color="#E33D30">-0.0202</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#E33D30">+12368.38</font> | <font color="#E33D30">0.90x</font> | <font color="#1ABD76">+0.0267</font> |


==============================

### 对比基准: `startcode1b-original-data-dpo-all`

> **基准值: { 平均时间 (avg_time): 113053.20, Pass@1: 0.0642 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-7.14</font> | 1.00x | <font color="#1ABD76">+0.0811</font> |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-1668.49</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0496</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#E33D30">+4472.55</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0663</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#E33D30">+10348.83</font> | <font color="#E33D30">0.92x</font> | <font color="#1ABD76">+0.0709</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-1400.00</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0857</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#E33D30">+7187.57</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0700</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#E33D30">+8870.99</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0556</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#E33D30">+4898.84</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0757</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#E33D30">+4982.85</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0616</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#E33D30">+446.23</font> | 1.00x | <font color="#1ABD76">+0.0827</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-4049.60</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0064</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#E33D30">+10822.81</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0525</font> |
| startcode1b-original-data-dpo-pvf | <font color="#1ABD76">-2818.61</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0015</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#E33D30">+1314.82</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0805</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#E33D30">+9054.54</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0626</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-9348.40</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0315</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-9010.46</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0280</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-8973.94</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0363</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#E33D30">+5909.95</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0660</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#E33D30">+5767.46</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0718</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+2459.08</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0664</font> |
| original-data | <font color="#1ABD76">-1159.27</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.9358</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#E33D30">+18827.92</font> | <font color="#E33D30">0.86x</font> | <font color="#1ABD76">+0.0563</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-81.04</font> | 1.00x | <font color="#E33D30">-0.0021</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+11296.05</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0410</font> |
| startcode1b-original-data-sft-1 | <font color="#E33D30">+39841.16</font> | <font color="#E33D30">0.74x</font> | <font color="#1ABD76">+0.0233</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+2349.90</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0461</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#E33D30">+109.76</font> | 1.00x | <font color="#1ABD76">+0.0869</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#E33D30">+7550.78</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0732</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#E33D30">+8547.05</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0838</font> |
| sft-25-original-data-1b | <font color="#E33D30">+16436.92</font> | <font color="#E33D30">0.87x</font> | <font color="#1ABD76">+0.0259</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#E33D30">+14718.28</font> | <font color="#E33D30">0.88x</font> | <font color="#1ABD76">+0.0728</font> |


==============================

### 对比基准: `startcode1b-original-data-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 112972.16, Pass@1: 0.0620 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#E33D30">+73.90</font> | 1.00x | <font color="#1ABD76">+0.0833</font> |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-1587.45</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0518</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#E33D30">+4553.59</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0685</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#E33D30">+10429.87</font> | <font color="#E33D30">0.92x</font> | <font color="#1ABD76">+0.0731</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-1318.96</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0879</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#E33D30">+7268.61</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0721</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#E33D30">+8952.03</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0578</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#E33D30">+4979.88</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0779</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#E33D30">+5063.89</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0638</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#E33D30">+527.27</font> | 1.00x | <font color="#1ABD76">+0.0849</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-3968.56</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0086</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#E33D30">+10903.85</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0547</font> |
| startcode1b-original-data-dpo-pvf | <font color="#1ABD76">-2737.57</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0037</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#E33D30">+1395.85</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0827</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#E33D30">+9135.58</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0647</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-9267.36</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0337</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-8929.42</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0301</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-8892.90</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0384</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#E33D30">+5990.99</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0681</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#E33D30">+5848.50</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0740</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+2540.12</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0685</font> |
| original-data | <font color="#1ABD76">-1078.23</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.9380</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#E33D30">+18908.96</font> | <font color="#E33D30">0.86x</font> | <font color="#1ABD76">+0.0585</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+11377.09</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0432</font> |
| startcode1b-original-data-sft-1 | <font color="#E33D30">+39922.20</font> | <font color="#E33D30">0.74x</font> | <font color="#1ABD76">+0.0255</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+2430.94</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0483</font> |
| startcode1b-original-data-dpo-all | <font color="#E33D30">+81.04</font> | 1.00x | <font color="#1ABD76">+0.0021</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#E33D30">+190.80</font> | 1.00x | <font color="#1ABD76">+0.0891</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#E33D30">+7631.82</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0753</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#E33D30">+8628.09</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0859</font> |
| sft-25-original-data-1b | <font color="#E33D30">+16517.96</font> | <font color="#E33D30">0.87x</font> | <font color="#1ABD76">+0.0281</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#E33D30">+14799.32</font> | <font color="#E33D30">0.88x</font> | <font color="#1ABD76">+0.0749</font> |


==============================

### 对比基准: `sft-25-original-data-1b`

> **基准值: { 平均时间 (avg_time): 129490.12, Pass@1: 0.0901 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-16444.06</font> | <font color="#1ABD76">1.15x</font> | <font color="#1ABD76">+0.0552</font> |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-18105.41</font> | <font color="#1ABD76">1.16x</font> | <font color="#1ABD76">+0.0237</font> |
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
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-16517.96</font> | <font color="#1ABD76">1.15x</font> | <font color="#E33D30">-0.0281</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-5140.87</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0151</font> |
| startcode1b-original-data-sft-1 | <font color="#E33D30">+23404.24</font> | <font color="#E33D30">0.85x</font> | <font color="#E33D30">-0.0026</font> |
| sft-25-original-data-1b-dpo-all | <font color="#1ABD76">-14087.02</font> | <font color="#1ABD76">1.12x</font> | <font color="#1ABD76">+0.0202</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-16436.92</font> | <font color="#1ABD76">1.15x</font> | <font color="#E33D30">-0.0259</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-16327.16</font> | <font color="#1ABD76">1.14x</font> | <font color="#1ABD76">+0.0610</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#1ABD76">-8886.14</font> | <font color="#1ABD76">1.07x</font> | <font color="#1ABD76">+0.0472</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-7889.87</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0579</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#1ABD76">-1718.64</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0468</font> |





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
| sft-25-original-data-1b-dpo-codedpo | 244828.90 | 0.0991 |
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
| startcode1b-original-data-dpo-codedpo | 248412.54 | <font color="#E33D30">0.0704</font> |
| sft-25-original-data-1b-dpo-qts | 243661.31 | 0.1042 |
| startcode1b-original-data-sft-1 | 🥈133612.54 | 0.1005 |
| sft-25-original-data-1b-dpo-all | 242294.59 | 0.1027 |
| startcode1b-original-data-dpo-all | 221468.64 | 0.0742 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | 188892.28 | 0.1124 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | 182894.67 | 0.1082 |
| sft-25-original-data-1b-dpo-qra | 162440.13 | 0.1204 |
| sft-25-original-data-1b | 300671.57 | 0.1014 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | 176834.83 | 🥉0.1209 |



--- [开始生成对比表格] ---

==============================

### 对比基准: `sft-25-original-data-1b-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 244828.90, Pass@1: 0.0991 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-48314.78</font> | <font color="#1ABD76">1.25x</font> | <font color="#1ABD76">+0.0120</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#1ABD76">-20312.78</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0130</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-40964.05</font> | <font color="#1ABD76">1.20x</font> | <font color="#1ABD76">+0.0238</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-45255.95</font> | <font color="#1ABD76">1.23x</font> | <font color="#1ABD76">+0.0125</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-97161.99</font> | <font color="#1ABD76">1.66x</font> | <font color="#1ABD76">+0.0259</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#E33D30">+18592.84</font> | <font color="#E33D30">0.93x</font> | <font color="#1ABD76">+0.0077</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-64320.10</font> | <font color="#1ABD76">1.36x</font> | <font color="#1ABD76">+0.0149</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#E33D30">+6885.95</font> | <font color="#E33D30">0.97x</font> | <font color="#1ABD76">+0.0080</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#1ABD76">-92299.49</font> | <font color="#1ABD76">1.61x</font> | <font color="#1ABD76">+0.0196</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-118156.61</font> | <font color="#1ABD76">1.93x</font> | <font color="#E33D30">-0.0264</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#1ABD76">-11467.71</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0062</font> |
| startcode1b-original-data-dpo-pvf | <font color="#E33D30">+76326.59</font> | <font color="#E33D30">0.76x</font> | <font color="#E33D30">-0.0261</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#1ABD76">-101854.70</font> | <font color="#1ABD76">1.71x</font> | <font color="#1ABD76">+0.0191</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#1ABD76">-12481.16</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0110</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-39783.63</font> | <font color="#1ABD76">1.19x</font> | <font color="#E33D30">-0.0166</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-56208.53</font> | <font color="#1ABD76">1.30x</font> | <font color="#E33D30">-0.0227</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#E33D30">+60936.72</font> | <font color="#E33D30">0.80x</font> | <font color="#E33D30">-0.0182</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-81697.48</font> | <font color="#1ABD76">1.50x</font> | <font color="#1ABD76">+0.0194</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#1ABD76">-26718.72</font> | <font color="#1ABD76">1.12x</font> | <font color="#1ABD76">+0.0088</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-68819.41</font> | <font color="#1ABD76">1.39x</font> | <font color="#1ABD76">+0.0191</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-96140.01</font> | <font color="#1ABD76">1.65x</font> | <font color="#1ABD76">+0.0193</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#E33D30">+3583.65</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0288</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-1167.58</font> | 1.00x | <font color="#1ABD76">+0.0051</font> |
| startcode1b-original-data-sft-1 | <font color="#1ABD76">-111216.36</font> | <font color="#1ABD76">1.83x</font> | <font color="#1ABD76">+0.0013</font> |
| sft-25-original-data-1b-dpo-all | <font color="#1ABD76">-2534.30</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0035</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-23360.26</font> | <font color="#1ABD76">1.11x</font> | <font color="#E33D30">-0.0249</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-55936.62</font> | <font color="#1ABD76">1.30x</font> | <font color="#1ABD76">+0.0133</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#1ABD76">-61934.22</font> | <font color="#1ABD76">1.34x</font> | <font color="#1ABD76">+0.0090</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-82388.76</font> | <font color="#1ABD76">1.51x</font> | <font color="#1ABD76">+0.0213</font> |
| sft-25-original-data-1b | <font color="#E33D30">+55842.67</font> | <font color="#E33D30">0.81x</font> | <font color="#1ABD76">+0.0023</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#1ABD76">-67994.07</font> | <font color="#1ABD76">1.38x</font> | <font color="#1ABD76">+0.0218</font> |


==============================

### 对比基准: `sft-25-original-data-1b-dpo-all`

> **基准值: { 平均时间 (avg_time): 242294.59, Pass@1: 0.1027 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-45780.48</font> | <font color="#1ABD76">1.23x</font> | <font color="#1ABD76">+0.0084</font> |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+2534.30</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0035</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#1ABD76">-17778.47</font> | <font color="#1ABD76">1.08x</font> | <font color="#1ABD76">+0.0095</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-38429.75</font> | <font color="#1ABD76">1.19x</font> | <font color="#1ABD76">+0.0203</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-42721.65</font> | <font color="#1ABD76">1.21x</font> | <font color="#1ABD76">+0.0090</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-94627.69</font> | <font color="#1ABD76">1.64x</font> | <font color="#1ABD76">+0.0224</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#E33D30">+21127.15</font> | <font color="#E33D30">0.92x</font> | <font color="#1ABD76">+0.0041</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-61785.79</font> | <font color="#1ABD76">1.34x</font> | <font color="#1ABD76">+0.0113</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#E33D30">+9420.26</font> | <font color="#E33D30">0.96x</font> | <font color="#1ABD76">+0.0045</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#1ABD76">-89765.18</font> | <font color="#1ABD76">1.59x</font> | <font color="#1ABD76">+0.0160</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-115622.31</font> | <font color="#1ABD76">1.91x</font> | <font color="#E33D30">-0.0299</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#1ABD76">-8933.40</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0026</font> |
| startcode1b-original-data-dpo-pvf | <font color="#E33D30">+78860.90</font> | <font color="#E33D30">0.75x</font> | <font color="#E33D30">-0.0296</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#1ABD76">-99320.39</font> | <font color="#1ABD76">1.69x</font> | <font color="#1ABD76">+0.0155</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#1ABD76">-9946.86</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0075</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-37249.32</font> | <font color="#1ABD76">1.18x</font> | <font color="#E33D30">-0.0202</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-53674.23</font> | <font color="#1ABD76">1.28x</font> | <font color="#E33D30">-0.0263</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#E33D30">+63471.03</font> | <font color="#E33D30">0.79x</font> | <font color="#E33D30">-0.0218</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-79163.18</font> | <font color="#1ABD76">1.49x</font> | <font color="#1ABD76">+0.0159</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#1ABD76">-24184.41</font> | <font color="#1ABD76">1.11x</font> | <font color="#1ABD76">+0.0052</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-66285.11</font> | <font color="#1ABD76">1.38x</font> | <font color="#1ABD76">+0.0156</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-93605.71</font> | <font color="#1ABD76">1.63x</font> | <font color="#1ABD76">+0.0157</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#E33D30">+6117.95</font> | <font color="#E33D30">0.98x</font> | <font color="#E33D30">-0.0323</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+1366.72</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0015</font> |
| startcode1b-original-data-sft-1 | <font color="#1ABD76">-108682.05</font> | <font color="#1ABD76">1.81x</font> | <font color="#E33D30">-0.0022</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-20825.96</font> | <font color="#1ABD76">1.09x</font> | <font color="#E33D30">-0.0285</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-53402.32</font> | <font color="#1ABD76">1.28x</font> | <font color="#1ABD76">+0.0098</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#1ABD76">-59399.92</font> | <font color="#1ABD76">1.32x</font> | <font color="#1ABD76">+0.0055</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-79854.46</font> | <font color="#1ABD76">1.49x</font> | <font color="#1ABD76">+0.0177</font> |
| sft-25-original-data-1b | <font color="#E33D30">+58376.97</font> | <font color="#E33D30">0.81x</font> | <font color="#E33D30">-0.0013</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#1ABD76">-65459.76</font> | <font color="#1ABD76">1.37x</font> | <font color="#1ABD76">+0.0182</font> |


==============================

### 对比基准: `startcode1b-original-data-dpo-all`

> **基准值: { 平均时间 (avg_time): 221468.64, Pass@1: 0.0742 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-24954.52</font> | <font color="#1ABD76">1.13x</font> | <font color="#1ABD76">+0.0369</font> |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+23360.26</font> | <font color="#E33D30">0.90x</font> | <font color="#1ABD76">+0.0249</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#E33D30">+3047.48</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0380</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-17603.79</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0488</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-21895.69</font> | <font color="#1ABD76">1.11x</font> | <font color="#1ABD76">+0.0374</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-73801.73</font> | <font color="#1ABD76">1.50x</font> | <font color="#1ABD76">+0.0509</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#E33D30">+41953.10</font> | <font color="#E33D30">0.84x</font> | <font color="#1ABD76">+0.0326</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-40959.84</font> | <font color="#1ABD76">1.23x</font> | <font color="#1ABD76">+0.0398</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#E33D30">+30246.21</font> | <font color="#E33D30">0.88x</font> | <font color="#1ABD76">+0.0329</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#1ABD76">-68939.23</font> | <font color="#1ABD76">1.45x</font> | <font color="#1ABD76">+0.0445</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-94796.35</font> | <font color="#1ABD76">1.75x</font> | <font color="#E33D30">-0.0015</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#E33D30">+11892.55</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0311</font> |
| startcode1b-original-data-dpo-pvf | <font color="#E33D30">+99686.85</font> | <font color="#E33D30">0.69x</font> | <font color="#E33D30">-0.0012</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#1ABD76">-78494.44</font> | <font color="#1ABD76">1.55x</font> | <font color="#1ABD76">+0.0440</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#E33D30">+10879.10</font> | <font color="#E33D30">0.95x</font> | <font color="#1ABD76">+0.0360</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-16423.37</font> | <font color="#1ABD76">1.08x</font> | <font color="#1ABD76">+0.0083</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-32848.27</font> | <font color="#1ABD76">1.17x</font> | <font color="#1ABD76">+0.0022</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#E33D30">+84296.98</font> | <font color="#E33D30">0.72x</font> | <font color="#1ABD76">+0.0067</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-58337.22</font> | <font color="#1ABD76">1.36x</font> | <font color="#1ABD76">+0.0443</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#1ABD76">-3358.46</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0337</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-45459.15</font> | <font color="#1ABD76">1.26x</font> | <font color="#1ABD76">+0.0441</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-72779.75</font> | <font color="#1ABD76">1.49x</font> | <font color="#1ABD76">+0.0442</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#E33D30">+26943.91</font> | <font color="#E33D30">0.89x</font> | <font color="#E33D30">-0.0038</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+22192.68</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0300</font> |
| startcode1b-original-data-sft-1 | <font color="#1ABD76">-87856.10</font> | <font color="#1ABD76">1.66x</font> | <font color="#1ABD76">+0.0263</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+20825.96</font> | <font color="#E33D30">0.91x</font> | <font color="#1ABD76">+0.0285</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-32576.36</font> | <font color="#1ABD76">1.17x</font> | <font color="#1ABD76">+0.0382</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#1ABD76">-38573.96</font> | <font color="#1ABD76">1.21x</font> | <font color="#1ABD76">+0.0340</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-59028.51</font> | <font color="#1ABD76">1.36x</font> | <font color="#1ABD76">+0.0462</font> |
| sft-25-original-data-1b | <font color="#E33D30">+79202.93</font> | <font color="#E33D30">0.74x</font> | <font color="#1ABD76">+0.0272</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#1ABD76">-44633.81</font> | <font color="#1ABD76">1.25x</font> | <font color="#1ABD76">+0.0467</font> |


==============================

### 对比基准: `startcode1b-original-data-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 248412.54, Pass@1: 0.0704 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-51898.43</font> | <font color="#1ABD76">1.26x</font> | <font color="#1ABD76">+0.0407</font> |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-3583.65</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0288</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font color="#1ABD76">-23896.42</font> | <font color="#1ABD76">1.11x</font> | <font color="#1ABD76">+0.0418</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-44547.70</font> | <font color="#1ABD76">1.22x</font> | <font color="#1ABD76">+0.0526</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-48839.59</font> | <font color="#1ABD76">1.24x</font> | <font color="#1ABD76">+0.0413</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-100745.64</font> | <font color="#1ABD76">1.68x</font> | <font color="#1ABD76">+0.0547</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font color="#E33D30">+15009.20</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0365</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-67903.74</font> | <font color="#1ABD76">1.38x</font> | <font color="#1ABD76">+0.0437</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font color="#E33D30">+3302.31</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0368</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font color="#1ABD76">-95883.13</font> | <font color="#1ABD76">1.63x</font> | <font color="#1ABD76">+0.0484</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-121740.26</font> | <font color="#1ABD76">1.96x</font> | <font color="#1ABD76">+0.0024</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font color="#1ABD76">-15051.35</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0349</font> |
| startcode1b-original-data-dpo-pvf | <font color="#E33D30">+72742.95</font> | <font color="#E33D30">0.77x</font> | <font color="#1ABD76">+0.0027</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font color="#1ABD76">-105438.34</font> | <font color="#1ABD76">1.74x</font> | <font color="#1ABD76">+0.0479</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font color="#1ABD76">-16064.81</font> | <font color="#1ABD76">1.07x</font> | <font color="#1ABD76">+0.0398</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-43367.27</font> | <font color="#1ABD76">1.21x</font> | <font color="#1ABD76">+0.0121</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-59792.18</font> | <font color="#1ABD76">1.32x</font> | <font color="#1ABD76">+0.0060</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#E33D30">+57353.08</font> | <font color="#E33D30">0.81x</font> | <font color="#1ABD76">+0.0105</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-85281.13</font> | <font color="#1ABD76">1.52x</font> | <font color="#1ABD76">+0.0482</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font color="#1ABD76">-30302.36</font> | <font color="#1ABD76">1.14x</font> | <font color="#1ABD76">+0.0376</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-72403.06</font> | <font color="#1ABD76">1.41x</font> | <font color="#1ABD76">+0.0479</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-99723.66</font> | <font color="#1ABD76">1.67x</font> | <font color="#1ABD76">+0.0480</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-4751.23</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0338</font> |
| startcode1b-original-data-sft-1 | <font color="#1ABD76">-114800.00</font> | <font color="#1ABD76">1.86x</font> | <font color="#1ABD76">+0.0301</font> |
| sft-25-original-data-1b-dpo-all | <font color="#1ABD76">-6117.95</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0323</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-26943.91</font> | <font color="#1ABD76">1.12x</font> | <font color="#1ABD76">+0.0038</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-59520.26</font> | <font color="#1ABD76">1.32x</font> | <font color="#1ABD76">+0.0421</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#1ABD76">-65517.87</font> | <font color="#1ABD76">1.36x</font> | <font color="#1ABD76">+0.0378</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-85972.41</font> | <font color="#1ABD76">1.53x</font> | <font color="#1ABD76">+0.0501</font> |
| sft-25-original-data-1b | <font color="#E33D30">+52259.02</font> | <font color="#E33D30">0.83x</font> | <font color="#1ABD76">+0.0310</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#1ABD76">-71577.71</font> | <font color="#1ABD76">1.40x</font> | <font color="#1ABD76">+0.0505</font> |


==============================

### 对比基准: `sft-25-original-data-1b`

> **基准值: { 平均时间 (avg_time): 300671.57, Pass@1: 0.1014 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font color="#1ABD76">-104157.45</font> | <font color="#1ABD76">1.53x</font> | <font color="#1ABD76">+0.0097</font> |
| sft-25-original-data-1b-dpo-codedpo | <font color="#1ABD76">-55842.67</font> | <font color="#1ABD76">1.23x</font> | <font color="#E33D30">-0.0023</font> |
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
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-52259.02</font> | <font color="#1ABD76">1.21x</font> | <font color="#E33D30">-0.0310</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-57010.25</font> | <font color="#1ABD76">1.23x</font> | <font color="#1ABD76">+0.0028</font> |
| startcode1b-original-data-sft-1 | <font color="#1ABD76">-167059.03</font> | <font color="#1ABD76">2.25x</font> | <font color="#E33D30">-0.0009</font> |
| sft-25-original-data-1b-dpo-all | <font color="#1ABD76">-58376.97</font> | <font color="#1ABD76">1.24x</font> | <font color="#1ABD76">+0.0013</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-79202.93</font> | <font color="#1ABD76">1.36x</font> | <font color="#E33D30">-0.0272</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font color="#1ABD76">-111779.29</font> | <font color="#1ABD76">1.59x</font> | <font color="#1ABD76">+0.0110</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font color="#1ABD76">-117776.89</font> | <font color="#1ABD76">1.64x</font> | <font color="#1ABD76">+0.0068</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-138231.43</font> | <font color="#1ABD76">1.85x</font> | <font color="#1ABD76">+0.0190</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font color="#1ABD76">-123836.74</font> | <font color="#1ABD76">1.70x</font> | <font color="#1ABD76">+0.0195</font> |


==============================

错误: 基准模型 'sft-25-original-data-1b-sft-1' 未在数据中找到。跳过此表。

--- [所有表格生成完毕] ---


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
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">13759895.34</font> | 0.0666 |
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
| startcode1b-original-data-dpo-codedpo | 13546593.57 | <font color="#E33D30">0.0518</font> |
| sft-25-original-data-1b-dpo-qts | 13060078.53 | 0.0657 |
| sft-25-original-data-1b-dpo-all | 13672029.98 | 0.0691 |
| startcode1b-original-data-dpo-all | 13722836.70 | 0.0541 |
| sft-25-original-data-1b-dpo-qra | 13015695.05 | 0.0802 |
| sft-25-original-data-1b | 🥉12900094.60 | 0.0668 |



--- [开始生成对比表格] ---

==============================

### 对比基准: `sft-25-original-data-1b-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 13759895.34, Pass@1: 0.0666 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-1206688.93</font> | <font color="#1ABD76">1.10x</font> | <font color="#1ABD76">+0.0191</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-418195.04</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0065</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-957163.80</font> | <font color="#1ABD76">1.07x</font> | <font color="#1ABD76">+0.0228</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-692423.26</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0095</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-772950.76</font> | <font color="#1ABD76">1.06x</font> | <font color="#E33D30">-0.0101</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-605289.82</font> | <font color="#1ABD76">1.05x</font> | <font color="#E33D30">-0.0029</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-763729.26</font> | <font color="#1ABD76">1.06x</font> | <font color="#E33D30">-0.0088</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-495871.44</font> | <font color="#1ABD76">1.04x</font> | <font color="#E33D30">-0.0063</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-618080.67</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0157</font> |
| sft-25-original-data-1b-sft-1 | <font color="#1ABD76">-749626.28</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0041</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-715337.46</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0177</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-764710.57</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0133</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-213301.77</font> | <font color="#1ABD76">1.02x</font> | <font color="#E33D30">-0.0148</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-699816.81</font> | <font color="#1ABD76">1.05x</font> | <font color="#E33D30">-0.0009</font> |
| sft-25-original-data-1b-dpo-all | <font color="#1ABD76">-87865.35</font> | <font color="#1ABD76">1.01x</font> | <font color="#1ABD76">+0.0026</font> |
| startcode1b-original-data-dpo-all | <font color="#1ABD76">-37058.64</font> | 1.00x | <font color="#E33D30">-0.0124</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-744200.29</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0137</font> |
| sft-25-original-data-1b | <font color="#1ABD76">-859800.73</font> | <font color="#1ABD76">1.07x</font> | <font color="#1ABD76">+0.0002</font> |


==============================

### 对比基准: `sft-25-original-data-1b-dpo-all`

> **基准值: { 平均时间 (avg_time): 13672029.98, Pass@1: 0.0691 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+87865.35</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0026</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-1118823.58</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0166</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-330329.68</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0039</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-869298.45</font> | <font color="#1ABD76">1.07x</font> | <font color="#1ABD76">+0.0202</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-604557.91</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0069</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-685085.40</font> | <font color="#1ABD76">1.05x</font> | <font color="#E33D30">-0.0127</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-517424.47</font> | <font color="#1ABD76">1.04x</font> | <font color="#E33D30">-0.0055</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-675863.91</font> | <font color="#1ABD76">1.05x</font> | <font color="#E33D30">-0.0114</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-408006.09</font> | <font color="#1ABD76">1.03x</font> | <font color="#E33D30">-0.0089</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-530215.31</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0132</font> |
| sft-25-original-data-1b-sft-1 | <font color="#1ABD76">-661760.93</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0016</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-627472.11</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0151</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-676845.21</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0107</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-125436.41</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0173</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-611951.46</font> | <font color="#1ABD76">1.05x</font> | <font color="#E33D30">-0.0034</font> |
| startcode1b-original-data-dpo-all | <font color="#E33D30">+50806.71</font> | 1.00x | <font color="#E33D30">-0.0150</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-656334.94</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0111</font> |
| sft-25-original-data-1b | <font color="#1ABD76">-771935.38</font> | <font color="#1ABD76">1.06x</font> | <font color="#E33D30">-0.0023</font> |


==============================

### 对比基准: `startcode1b-original-data-dpo-all`

> **基准值: { 平均时间 (avg_time): 13722836.70, Pass@1: 0.0541 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+37058.64</font> | 1.00x | <font color="#1ABD76">+0.0124</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-1169630.29</font> | <font color="#1ABD76">1.09x</font> | <font color="#1ABD76">+0.0316</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-381136.40</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0189</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-920105.16</font> | <font color="#1ABD76">1.07x</font> | <font color="#1ABD76">+0.0352</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-655364.62</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0219</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-735892.12</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0023</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-568231.18</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0095</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-726670.62</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0036</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-458812.80</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0061</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-581022.03</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0282</font> |
| sft-25-original-data-1b-sft-1 | <font color="#1ABD76">-712567.65</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0166</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-678278.82</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0301</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-727651.93</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0257</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#1ABD76">-176243.13</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0023</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-662758.17</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0116</font> |
| sft-25-original-data-1b-dpo-all | <font color="#1ABD76">-50806.71</font> | 1.00x | <font color="#1ABD76">+0.0150</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-707141.65</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0261</font> |
| sft-25-original-data-1b | <font color="#1ABD76">-822742.09</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0127</font> |


==============================

### 对比基准: `startcode1b-original-data-dpo-codedpo`

> **基准值: { 平均时间 (avg_time): 13546593.57, Pass@1: 0.0518 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+213301.77</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0148</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-993387.16</font> | <font color="#1ABD76">1.08x</font> | <font color="#1ABD76">+0.0339</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#1ABD76">-204893.27</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0212</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-743862.03</font> | <font color="#1ABD76">1.06x</font> | <font color="#1ABD76">+0.0376</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#1ABD76">-479121.49</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0242</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-559648.99</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0046</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#1ABD76">-391988.05</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0118</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-550427.50</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0059</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#1ABD76">-282569.67</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0084</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#1ABD76">-404778.90</font> | <font color="#1ABD76">1.03x</font> | <font color="#1ABD76">+0.0305</font> |
| sft-25-original-data-1b-sft-1 | <font color="#1ABD76">-536324.52</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0189</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#1ABD76">-502035.69</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0324</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-551408.80</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0280</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#1ABD76">-486515.04</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0139</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+125436.41</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0173</font> |
| startcode1b-original-data-dpo-all | <font color="#E33D30">+176243.13</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0023</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#1ABD76">-530898.52</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0284</font> |
| sft-25-original-data-1b | <font color="#1ABD76">-646498.97</font> | <font color="#1ABD76">1.05x</font> | <font color="#1ABD76">+0.0150</font> |


==============================

### 对比基准: `sft-25-original-data-1b`

> **基准值: { 平均时间 (avg_time): 12900094.60, Pass@1: 0.0668 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+859800.73</font> | <font color="#E33D30">0.94x</font> | <font color="#E33D30">-0.0002</font> |
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
| startcode1b-original-data-dpo-codedpo | <font color="#E33D30">+646498.97</font> | <font color="#E33D30">0.95x</font> | <font color="#E33D30">-0.0150</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+159983.93</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0011</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+771935.38</font> | <font color="#E33D30">0.94x</font> | <font color="#1ABD76">+0.0023</font> |
| startcode1b-original-data-dpo-all | <font color="#E33D30">+822742.09</font> | <font color="#E33D30">0.94x</font> | <font color="#E33D30">-0.0127</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#E33D30">+115600.44</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0134</font> |


==============================

### 对比基准: `sft-25-original-data-1b-sft-1`

> **基准值: { 平均时间 (avg_time): 13010269.05, Pass@1: 0.0707 }**

| 模型 (Model) | 平均时间 (avg_time) | 加速比 (Speedup) | Pass@1 |
| :--- | :--- | :--- | :--- |
| sft-25-original-data-1b-dpo-codedpo | <font color="#E33D30">+749626.28</font> | <font color="#E33D30">0.95x</font> | <font color="#E33D30">-0.0041</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font color="#1ABD76">-457062.65</font> | <font color="#1ABD76">1.04x</font> | <font color="#1ABD76">+0.0150</font> |
| sft-25-original-data-1b-dpo-qfs | <font color="#E33D30">+331431.25</font> | <font color="#E33D30">0.98x</font> | <font color="#1ABD76">+0.0023</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font color="#1ABD76">-207537.52</font> | <font color="#1ABD76">1.02x</font> | <font color="#1ABD76">+0.0187</font> |
| sft-25-original-data-1b-dpo-qsl | <font color="#E33D30">+57203.02</font> | 1.00x | <font color="#1ABD76">+0.0053</font> |
| startcode1b-original-data-dpo-pvf-qts | <font color="#1ABD76">-23324.47</font> | 1.00x | <font color="#E33D30">-0.0143</font> |
| startcode1b-original-data-dpo-pvf-qra | <font color="#E33D30">+144336.46</font> | <font color="#E33D30">0.99x</font> | <font color="#E33D30">-0.0071</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font color="#1ABD76">-14102.98</font> | 1.00x | <font color="#E33D30">-0.0130</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font color="#E33D30">+253754.84</font> | <font color="#E33D30">0.98x</font> | <font color="#E33D30">-0.0105</font> |
| sft-25-original-data-1b-dpo-pvf | <font color="#E33D30">+131545.62</font> | <font color="#E33D30">0.99x</font> | <font color="#1ABD76">+0.0116</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font color="#E33D30">+34288.82</font> | 1.00x | <font color="#1ABD76">+0.0135</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font color="#1ABD76">-15084.28</font> | 1.00x | <font color="#1ABD76">+0.0091</font> |
| startcode1b-original-data-dpo-codedpo | <font color="#E33D30">+536324.52</font> | <font color="#E33D30">0.96x</font> | <font color="#E33D30">-0.0189</font> |
| sft-25-original-data-1b-dpo-qts | <font color="#E33D30">+49809.48</font> | 1.00x | <font color="#E33D30">-0.0050</font> |
| sft-25-original-data-1b-dpo-all | <font color="#E33D30">+661760.93</font> | <font color="#E33D30">0.95x</font> | <font color="#E33D30">-0.0016</font> |
| startcode1b-original-data-dpo-all | <font color="#E33D30">+712567.65</font> | <font color="#E33D30">0.95x</font> | <font color="#E33D30">-0.0166</font> |
| sft-25-original-data-1b-dpo-qra | <font color="#E33D30">+5425.99</font> | 1.00x | <font color="#1ABD76">+0.0095</font> |
| sft-25-original-data-1b | <font color="#1ABD76">-110174.45</font> | <font color="#1ABD76">1.01x</font> | <font color="#E33D30">-0.0039</font> |


--- [所有表格生成完毕] ---

