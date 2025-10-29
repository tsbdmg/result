
--- [开始生成表格] ---
### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色加粗</span>: 该列中的最大值 (性能最差)。
* 🥇: 该列中的最小值 (性能第一)。
* 🥈: 该列中的第二小值 (性能第二)。
* 🥉: 该列中的第三小值 (性能第三)。

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| startcode_1b | 1.21 | <font  color="#E33D30">9.46</font> | 🥇37.77 | 🥇1.00 | 31.86 | 3.84 |
| sft-25-original-data-1b | <font  color="#E33D30">1.37</font> | 8.81 | 411.37 | 7.66 | 900.77 | 62.16 |
| sft-25-original-data-1b-dpo-qfs | 0.85 | 5.32 | 127.65 | 2.32 | 175.39 | 11.51 |
| sft-25-original-data-1b-dpo-pvf | 0.95 | 6.45 | 125.20 | 2.63 | 186.79 | 16.14 |
| sft-25-original-data-1b-dpo-qsl | 0.81 | 5.76 | 238.05 | 5.56 | 491.16 | 52.35 |
| sft-25-original-data-1b-dpo-qts | 1.15 | 8.34 | 108.65 | 2.65 | 191.78 | 21.27 |
| sft-codedpo | 1.01 | 7.51 | 143.87 | 3.52 | 434.00 | 49.65 |
| sft-Code-Optimise | 0.67 | 🥈3.80 | 88.81 | 1.44 | 95.54 | 4.98 |
| sft-25-original-data-1b-dpo-qra | 0.87 | 5.57 | 207.35 | 4.50 | 526.39 | 42.17 |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | 0.83 | 5.95 | 53.68 | 1.27 | 50.29 | 5.57 |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | 0.72 | 5.86 | 73.45 | 2.15 | 114.34 | 17.68 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | 0.79 | 4.90 | 111.94 | 1.96 | 150.34 | 9.48 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | 0.84 | 5.28 | 345.82 | 7.31 | 852.89 | 64.06 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | 0.90 | 6.66 | 154.60 | 3.80 | 262.20 | 30.67 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | 1.06 | 5.53 | 71.88 | 🥇1.00 | 49.11 | 🥈2.18 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | 0.70 | 5.35 | 49.63 | 1.33 | 48.01 | 6.55 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | 0.86 | 6.27 | 🥉39.64 | 🥇1.00 | 🥈24.54 | 🥉2.78 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | 🥈0.57 | 4.39 | 64.04 | 1.65 | 75.32 | 9.72 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | 0.98 | 6.66 | 54.58 | 🥉1.15 | 51.39 | 4.53 |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | 1.03 | 7.25 | 53.71 | 1.24 | 56.41 | 5.98 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | 0.72 | 5.20 | 44.71 | 🥈1.04 | 30.16 | 3.10 |
| sft-25-original-data-1b-dpo-pvf-qsl | 🥇0.51 | 🥇3.18 | 343.30 | 6.85 | 921.31 | 65.44 |
| sft-25-original-data-1b-dpo-pvf-qts | 0.68 | 4.45 | 129.44 | 2.66 | 199.93 | 14.64 |
| sft-25-original-data-1b-dpo-pvf-qra | 0.89 | 6.22 | 196.71 | 4.93 | 540.84 | 59.42 |
| sft-25-original-data-1b-dpo-pvf-qfs | 0.71 | 5.57 | 274.52 | 8.01 | 623.97 | 97.92 |
| startcode1b-original-data-dpo-pvf | 1.12 | 8.56 | 59.16 | 1.53 | 84.48 | 9.69 |
| startcode1b-original-data-dpo-pvf-qfs | 1.01 | 7.35 | 170.31 | 4.24 | 573.65 | 60.15 |
| startcode1b-original-data-sft-1 | 1.08 | 8.42 | <font  color="#E33D30">799.24</font> | <font  color="#E33D30">22.52</font> | <font  color="#E33D30">2045.40</font> | 278.46 |
| startcode1b-original-data-dpo-pvf-qts | 🥉0.62 | 🥉4.29 | 45.72 | 🥇1.00 | 🥇22.26 | 🥇1.77 |
| startcode1b-original-data-dpo-pvf-qra | 0.85 | 6.64 | 43.76 | 1.36 | 45.90 | 7.46 |
| Code-Optimise | 0.90 | 8.77 | 358.56 | 16.10 | 888.14 | <font  color="#E33D30">620.55</font> |
| codedpo | 0.84 | 6.50 | 125.26 | 3.15 | 230.40 | 24.71 |
| startcode1b-original-data-dpo-pvf-qsl | 0.88 | 6.39 | 🥈38.55 | 🥇1.00 | 🥉27.18 | 3.18 |



--- [开始生成对比表格] ---

==============================

### 对比基准: `sft-codedpo`

> **基准值: {执行时间: 1.01, 归一化执行时间: 7.51, 峰值内存: 143.87, 归一化峰值内存: 3.52, 内存时间面积: 434.00, 归一化内存时间面积: 49.65}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| startcode_1b | +0.20 | +1.95 | <font  color="#1ABD76">-106.10</font> | <font  color="#1ABD76">-2.52</font> | <font  color="#1ABD76">-402.14</font> | <font  color="#1ABD76">-45.81</font> |
| sft-25-original-data-1b | +0.36 | +1.30 | +267.50 | +4.14 | +466.77 | +12.51 |
| sft-25-original-data-1b-dpo-qfs | <font  color="#1ABD76">-0.16</font> | <font  color="#1ABD76">-2.19</font> | <font  color="#1ABD76">-16.22</font> | <font  color="#1ABD76">-1.20</font> | <font  color="#1ABD76">-258.61</font> | <font  color="#1ABD76">-38.14</font> |
| sft-25-original-data-1b-dpo-pvf | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-1.06</font> | <font  color="#1ABD76">-18.67</font> | <font  color="#1ABD76">-0.89</font> | <font  color="#1ABD76">-247.21</font> | <font  color="#1ABD76">-33.51</font> |
| sft-25-original-data-1b-dpo-qsl | <font  color="#1ABD76">-0.20</font> | <font  color="#1ABD76">-1.75</font> | +94.18 | +2.04 | +57.16 | +2.70 |
| sft-25-original-data-1b-dpo-qts | +0.14 | +0.83 | <font  color="#1ABD76">-35.22</font> | <font  color="#1ABD76">-0.87</font> | <font  color="#1ABD76">-242.22</font> | <font  color="#1ABD76">-28.38</font> |
| sft-Code-Optimise | <font  color="#1ABD76">-0.34</font> | <font  color="#1ABD76">-3.71</font> | <font  color="#1ABD76">-55.06</font> | <font  color="#1ABD76">-2.08</font> | <font  color="#1ABD76">-338.46</font> | <font  color="#1ABD76">-44.67</font> |
| sft-25-original-data-1b-dpo-qra | <font  color="#1ABD76">-0.14</font> | <font  color="#1ABD76">-1.94</font> | +63.48 | +0.98 | +92.39 | <font  color="#1ABD76">-7.48</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font  color="#1ABD76">-0.18</font> | <font  color="#1ABD76">-1.56</font> | <font  color="#1ABD76">-90.19</font> | <font  color="#1ABD76">-2.25</font> | <font  color="#1ABD76">-383.71</font> | <font  color="#1ABD76">-44.08</font> |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font  color="#1ABD76">-0.29</font> | <font  color="#1ABD76">-1.65</font> | <font  color="#1ABD76">-70.42</font> | <font  color="#1ABD76">-1.37</font> | <font  color="#1ABD76">-319.66</font> | <font  color="#1ABD76">-31.97</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font  color="#1ABD76">-0.22</font> | <font  color="#1ABD76">-2.61</font> | <font  color="#1ABD76">-31.93</font> | <font  color="#1ABD76">-1.56</font> | <font  color="#1ABD76">-283.66</font> | <font  color="#1ABD76">-40.17</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font  color="#1ABD76">-0.17</font> | <font  color="#1ABD76">-2.23</font> | +201.95 | +3.79 | +418.89 | +14.41 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font  color="#1ABD76">-0.11</font> | <font  color="#1ABD76">-0.85</font> | +10.73 | +0.28 | <font  color="#1ABD76">-171.80</font> | <font  color="#1ABD76">-18.98</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | +0.05 | <font  color="#1ABD76">-1.98</font> | <font  color="#1ABD76">-71.99</font> | <font  color="#1ABD76">-2.52</font> | <font  color="#1ABD76">-384.89</font> | <font  color="#1ABD76">-47.47</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font  color="#1ABD76">-0.31</font> | <font  color="#1ABD76">-2.16</font> | <font  color="#1ABD76">-94.24</font> | <font  color="#1ABD76">-2.19</font> | <font  color="#1ABD76">-385.99</font> | <font  color="#1ABD76">-43.10</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font  color="#1ABD76">-0.15</font> | <font  color="#1ABD76">-1.24</font> | <font  color="#1ABD76">-104.23</font> | <font  color="#1ABD76">-2.52</font> | <font  color="#1ABD76">-409.46</font> | <font  color="#1ABD76">-46.87</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font  color="#1ABD76">-0.44</font> | <font  color="#1ABD76">-3.12</font> | <font  color="#1ABD76">-79.83</font> | <font  color="#1ABD76">-1.87</font> | <font  color="#1ABD76">-358.68</font> | <font  color="#1ABD76">-39.93</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.85</font> | <font  color="#1ABD76">-89.29</font> | <font  color="#1ABD76">-2.37</font> | <font  color="#1ABD76">-382.61</font> | <font  color="#1ABD76">-45.12</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | +0.02 | <font  color="#1ABD76">-0.26</font> | <font  color="#1ABD76">-90.16</font> | <font  color="#1ABD76">-2.28</font> | <font  color="#1ABD76">-377.59</font> | <font  color="#1ABD76">-43.67</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font  color="#1ABD76">-0.29</font> | <font  color="#1ABD76">-2.31</font> | <font  color="#1ABD76">-99.16</font> | <font  color="#1ABD76">-2.48</font> | <font  color="#1ABD76">-403.84</font> | <font  color="#1ABD76">-46.55</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font  color="#1ABD76">-0.50</font> | <font  color="#1ABD76">-4.33</font> | +199.43 | +3.33 | +487.31 | +15.79 |
| sft-25-original-data-1b-dpo-pvf-qts | <font  color="#1ABD76">-0.33</font> | <font  color="#1ABD76">-3.06</font> | <font  color="#1ABD76">-14.43</font> | <font  color="#1ABD76">-0.86</font> | <font  color="#1ABD76">-234.07</font> | <font  color="#1ABD76">-35.01</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font  color="#1ABD76">-0.12</font> | <font  color="#1ABD76">-1.29</font> | +52.84 | +1.41 | +106.84 | +9.77 |
| sft-25-original-data-1b-dpo-pvf-qfs | <font  color="#1ABD76">-0.30</font> | <font  color="#1ABD76">-1.94</font> | +130.65 | +4.49 | +189.97 | +48.27 |
| startcode1b-original-data-dpo-pvf | +0.11 | +1.05 | <font  color="#1ABD76">-84.71</font> | <font  color="#1ABD76">-1.99</font> | <font  color="#1ABD76">-349.52</font> | <font  color="#1ABD76">-39.96</font> |
| startcode1b-original-data-dpo-pvf-qfs | 0.00 | <font  color="#1ABD76">-0.16</font> | +26.44 | +0.72 | +139.65 | +10.50 |
| startcode1b-original-data-sft-1 | +0.07 | +0.91 | +655.37 | +19.00 | +1611.40 | +228.81 |
| startcode1b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.39</font> | <font  color="#1ABD76">-3.22</font> | <font  color="#1ABD76">-98.15</font> | <font  color="#1ABD76">-2.52</font> | <font  color="#1ABD76">-411.74</font> | <font  color="#1ABD76">-47.88</font> |
| startcode1b-original-data-dpo-pvf-qra | <font  color="#1ABD76">-0.16</font> | <font  color="#1ABD76">-0.87</font> | <font  color="#1ABD76">-100.11</font> | <font  color="#1ABD76">-2.16</font> | <font  color="#1ABD76">-388.10</font> | <font  color="#1ABD76">-42.19</font> |
| Code-Optimise | <font  color="#1ABD76">-0.11</font> | +1.26 | +214.69 | +12.58 | +454.14 | +570.90 |
| codedpo | <font  color="#1ABD76">-0.17</font> | <font  color="#1ABD76">-1.01</font> | <font  color="#1ABD76">-18.61</font> | <font  color="#1ABD76">-0.37</font> | <font  color="#1ABD76">-203.60</font> | <font  color="#1ABD76">-24.94</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font  color="#1ABD76">-0.13</font> | <font  color="#1ABD76">-1.12</font> | <font  color="#1ABD76">-105.32</font> | <font  color="#1ABD76">-2.52</font> | <font  color="#1ABD76">-406.82</font> | <font  color="#1ABD76">-46.47</font> |


==============================

### 对比基准: `codedpo`

> **基准值: {执行时间: 0.84, 归一化执行时间: 6.50, 峰值内存: 125.26, 归一化峰值内存: 3.15, 内存时间面积: 230.40, 归一化内存时间面积: 24.71}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| startcode_1b | +0.37 | +2.96 | <font  color="#1ABD76">-87.49</font> | <font  color="#1ABD76">-2.15</font> | <font  color="#1ABD76">-198.54</font> | <font  color="#1ABD76">-20.87</font> |
| sft-25-original-data-1b | +0.53 | +2.31 | +286.11 | +4.51 | +670.37 | +37.45 |
| sft-25-original-data-1b-dpo-qfs | +0.01 | <font  color="#1ABD76">-1.18</font> | +2.39 | <font  color="#1ABD76">-0.83</font> | <font  color="#1ABD76">-55.01</font> | <font  color="#1ABD76">-13.20</font> |
| sft-25-original-data-1b-dpo-pvf | +0.11 | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-0.52</font> | <font  color="#1ABD76">-43.61</font> | <font  color="#1ABD76">-8.57</font> |
| sft-25-original-data-1b-dpo-qsl | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.74</font> | +112.79 | +2.41 | +260.76 | +27.64 |
| sft-25-original-data-1b-dpo-qts | +0.31 | +1.84 | <font  color="#1ABD76">-16.61</font> | <font  color="#1ABD76">-0.50</font> | <font  color="#1ABD76">-38.62</font> | <font  color="#1ABD76">-3.44</font> |
| sft-codedpo | +0.17 | +1.01 | +18.61 | +0.37 | +203.60 | +24.94 |
| sft-Code-Optimise | <font  color="#1ABD76">-0.17</font> | <font  color="#1ABD76">-2.70</font> | <font  color="#1ABD76">-36.45</font> | <font  color="#1ABD76">-1.71</font> | <font  color="#1ABD76">-134.86</font> | <font  color="#1ABD76">-19.73</font> |
| sft-25-original-data-1b-dpo-qra | +0.03 | <font  color="#1ABD76">-0.93</font> | +82.09 | +1.35 | +295.99 | +17.46 |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font  color="#1ABD76">-0.01</font> | <font  color="#1ABD76">-0.55</font> | <font  color="#1ABD76">-71.58</font> | <font  color="#1ABD76">-1.88</font> | <font  color="#1ABD76">-180.11</font> | <font  color="#1ABD76">-19.14</font> |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font  color="#1ABD76">-0.12</font> | <font  color="#1ABD76">-0.64</font> | <font  color="#1ABD76">-51.81</font> | <font  color="#1ABD76">-1.00</font> | <font  color="#1ABD76">-116.06</font> | <font  color="#1ABD76">-7.03</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-1.60</font> | <font  color="#1ABD76">-13.32</font> | <font  color="#1ABD76">-1.19</font> | <font  color="#1ABD76">-80.06</font> | <font  color="#1ABD76">-15.23</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | 0.00 | <font  color="#1ABD76">-1.22</font> | +220.56 | +4.16 | +622.49 | +39.35 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | +0.06 | +0.16 | +29.34 | +0.65 | +31.80 | +5.96 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | +0.22 | <font  color="#1ABD76">-0.97</font> | <font  color="#1ABD76">-53.38</font> | <font  color="#1ABD76">-2.15</font> | <font  color="#1ABD76">-181.29</font> | <font  color="#1ABD76">-22.53</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font  color="#1ABD76">-0.14</font> | <font  color="#1ABD76">-1.15</font> | <font  color="#1ABD76">-75.63</font> | <font  color="#1ABD76">-1.82</font> | <font  color="#1ABD76">-182.39</font> | <font  color="#1ABD76">-18.16</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | +0.02 | <font  color="#1ABD76">-0.23</font> | <font  color="#1ABD76">-85.62</font> | <font  color="#1ABD76">-2.15</font> | <font  color="#1ABD76">-205.86</font> | <font  color="#1ABD76">-21.93</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font  color="#1ABD76">-0.27</font> | <font  color="#1ABD76">-2.11</font> | <font  color="#1ABD76">-61.22</font> | <font  color="#1ABD76">-1.50</font> | <font  color="#1ABD76">-155.08</font> | <font  color="#1ABD76">-14.99</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | +0.14 | +0.16 | <font  color="#1ABD76">-70.68</font> | <font  color="#1ABD76">-2.00</font> | <font  color="#1ABD76">-179.01</font> | <font  color="#1ABD76">-20.18</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | +0.19 | +0.75 | <font  color="#1ABD76">-71.55</font> | <font  color="#1ABD76">-1.91</font> | <font  color="#1ABD76">-173.99</font> | <font  color="#1ABD76">-18.73</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font  color="#1ABD76">-0.12</font> | <font  color="#1ABD76">-1.30</font> | <font  color="#1ABD76">-80.55</font> | <font  color="#1ABD76">-2.11</font> | <font  color="#1ABD76">-200.24</font> | <font  color="#1ABD76">-21.61</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font  color="#1ABD76">-0.33</font> | <font  color="#1ABD76">-3.32</font> | +218.04 | +3.70 | +690.91 | +40.73 |
| sft-25-original-data-1b-dpo-pvf-qts | <font  color="#1ABD76">-0.16</font> | <font  color="#1ABD76">-2.05</font> | +4.18 | <font  color="#1ABD76">-0.49</font> | <font  color="#1ABD76">-30.47</font> | <font  color="#1ABD76">-10.07</font> |
| sft-25-original-data-1b-dpo-pvf-qra | +0.05 | <font  color="#1ABD76">-0.28</font> | +71.45 | +1.78 | +310.44 | +34.71 |
| sft-25-original-data-1b-dpo-pvf-qfs | <font  color="#1ABD76">-0.13</font> | <font  color="#1ABD76">-0.93</font> | +149.26 | +4.86 | +393.57 | +73.21 |
| startcode1b-original-data-dpo-pvf | +0.28 | +2.06 | <font  color="#1ABD76">-66.10</font> | <font  color="#1ABD76">-1.62</font> | <font  color="#1ABD76">-145.92</font> | <font  color="#1ABD76">-15.02</font> |
| startcode1b-original-data-dpo-pvf-qfs | +0.17 | +0.85 | +45.05 | +1.09 | +343.25 | +35.44 |
| startcode1b-original-data-sft-1 | +0.24 | +1.92 | +673.98 | +19.37 | +1815.00 | +253.75 |
| startcode1b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.22</font> | <font  color="#1ABD76">-2.21</font> | <font  color="#1ABD76">-79.54</font> | <font  color="#1ABD76">-2.15</font> | <font  color="#1ABD76">-208.14</font> | <font  color="#1ABD76">-22.94</font> |
| startcode1b-original-data-dpo-pvf-qra | +0.01 | +0.14 | <font  color="#1ABD76">-81.50</font> | <font  color="#1ABD76">-1.79</font> | <font  color="#1ABD76">-184.50</font> | <font  color="#1ABD76">-17.25</font> |
| Code-Optimise | +0.06 | +2.27 | +233.30 | +12.95 | +657.74 | +595.84 |
| startcode1b-original-data-dpo-pvf-qsl | +0.04 | <font  color="#1ABD76">-0.11</font> | <font  color="#1ABD76">-86.71</font> | <font  color="#1ABD76">-2.15</font> | <font  color="#1ABD76">-203.22</font> | <font  color="#1ABD76">-21.53</font> |


==============================

### 对比基准: `Code-Optimise`

> **基准值: {执行时间: 0.90, 归一化执行时间: 8.77, 峰值内存: 358.56, 归一化峰值内存: 16.10, 内存时间面积: 888.14, 归一化内存时间面积: 620.55}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| startcode_1b | +0.31 | +0.69 | <font  color="#1ABD76">-320.79</font> | <font  color="#1ABD76">-15.10</font> | <font  color="#1ABD76">-856.28</font> | <font  color="#1ABD76">-616.71</font> |
| sft-25-original-data-1b | +0.47 | +0.04 | +52.81 | <font  color="#1ABD76">-8.44</font> | +12.63 | <font  color="#1ABD76">-558.39</font> |
| sft-25-original-data-1b-dpo-qfs | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-3.45</font> | <font  color="#1ABD76">-230.91</font> | <font  color="#1ABD76">-13.78</font> | <font  color="#1ABD76">-712.75</font> | <font  color="#1ABD76">-609.04</font> |
| sft-25-original-data-1b-dpo-pvf | +0.05 | <font  color="#1ABD76">-2.32</font> | <font  color="#1ABD76">-233.36</font> | <font  color="#1ABD76">-13.47</font> | <font  color="#1ABD76">-701.35</font> | <font  color="#1ABD76">-604.41</font> |
| sft-25-original-data-1b-dpo-qsl | <font  color="#1ABD76">-0.09</font> | <font  color="#1ABD76">-3.01</font> | <font  color="#1ABD76">-120.51</font> | <font  color="#1ABD76">-10.54</font> | <font  color="#1ABD76">-396.98</font> | <font  color="#1ABD76">-568.20</font> |
| sft-25-original-data-1b-dpo-qts | +0.25 | <font  color="#1ABD76">-0.43</font> | <font  color="#1ABD76">-249.91</font> | <font  color="#1ABD76">-13.45</font> | <font  color="#1ABD76">-696.36</font> | <font  color="#1ABD76">-599.28</font> |
| sft-codedpo | +0.11 | <font  color="#1ABD76">-1.26</font> | <font  color="#1ABD76">-214.69</font> | <font  color="#1ABD76">-12.58</font> | <font  color="#1ABD76">-454.14</font> | <font  color="#1ABD76">-570.90</font> |
| sft-Code-Optimise | <font  color="#1ABD76">-0.23</font> | <font  color="#1ABD76">-4.97</font> | <font  color="#1ABD76">-269.75</font> | <font  color="#1ABD76">-14.66</font> | <font  color="#1ABD76">-792.60</font> | <font  color="#1ABD76">-615.57</font> |
| sft-25-original-data-1b-dpo-qra | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-3.20</font> | <font  color="#1ABD76">-151.21</font> | <font  color="#1ABD76">-11.60</font> | <font  color="#1ABD76">-361.75</font> | <font  color="#1ABD76">-578.38</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-2.82</font> | <font  color="#1ABD76">-304.88</font> | <font  color="#1ABD76">-14.83</font> | <font  color="#1ABD76">-837.85</font> | <font  color="#1ABD76">-614.98</font> |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font  color="#1ABD76">-0.18</font> | <font  color="#1ABD76">-2.91</font> | <font  color="#1ABD76">-285.11</font> | <font  color="#1ABD76">-13.95</font> | <font  color="#1ABD76">-773.80</font> | <font  color="#1ABD76">-602.87</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font  color="#1ABD76">-0.11</font> | <font  color="#1ABD76">-3.87</font> | <font  color="#1ABD76">-246.62</font> | <font  color="#1ABD76">-14.14</font> | <font  color="#1ABD76">-737.80</font> | <font  color="#1ABD76">-611.07</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-3.49</font> | <font  color="#1ABD76">-12.74</font> | <font  color="#1ABD76">-8.79</font> | <font  color="#1ABD76">-35.25</font> | <font  color="#1ABD76">-556.49</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | 0.00 | <font  color="#1ABD76">-2.11</font> | <font  color="#1ABD76">-203.96</font> | <font  color="#1ABD76">-12.30</font> | <font  color="#1ABD76">-625.94</font> | <font  color="#1ABD76">-589.88</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | +0.16 | <font  color="#1ABD76">-3.24</font> | <font  color="#1ABD76">-286.68</font> | <font  color="#1ABD76">-15.10</font> | <font  color="#1ABD76">-839.03</font> | <font  color="#1ABD76">-618.37</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font  color="#1ABD76">-0.20</font> | <font  color="#1ABD76">-3.42</font> | <font  color="#1ABD76">-308.93</font> | <font  color="#1ABD76">-14.77</font> | <font  color="#1ABD76">-840.13</font> | <font  color="#1ABD76">-614.00</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font  color="#1ABD76">-0.04</font> | <font  color="#1ABD76">-2.50</font> | <font  color="#1ABD76">-318.92</font> | <font  color="#1ABD76">-15.10</font> | <font  color="#1ABD76">-863.60</font> | <font  color="#1ABD76">-617.77</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font  color="#1ABD76">-0.33</font> | <font  color="#1ABD76">-4.38</font> | <font  color="#1ABD76">-294.52</font> | <font  color="#1ABD76">-14.45</font> | <font  color="#1ABD76">-812.82</font> | <font  color="#1ABD76">-610.83</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | +0.08 | <font  color="#1ABD76">-2.11</font> | <font  color="#1ABD76">-303.98</font> | <font  color="#1ABD76">-14.95</font> | <font  color="#1ABD76">-836.75</font> | <font  color="#1ABD76">-616.02</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | +0.13 | <font  color="#1ABD76">-1.52</font> | <font  color="#1ABD76">-304.85</font> | <font  color="#1ABD76">-14.86</font> | <font  color="#1ABD76">-831.73</font> | <font  color="#1ABD76">-614.57</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font  color="#1ABD76">-0.18</font> | <font  color="#1ABD76">-3.57</font> | <font  color="#1ABD76">-313.85</font> | <font  color="#1ABD76">-15.06</font> | <font  color="#1ABD76">-857.98</font> | <font  color="#1ABD76">-617.45</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font  color="#1ABD76">-0.39</font> | <font  color="#1ABD76">-5.59</font> | <font  color="#1ABD76">-15.26</font> | <font  color="#1ABD76">-9.25</font> | +33.17 | <font  color="#1ABD76">-555.11</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font  color="#1ABD76">-0.22</font> | <font  color="#1ABD76">-4.32</font> | <font  color="#1ABD76">-229.12</font> | <font  color="#1ABD76">-13.44</font> | <font  color="#1ABD76">-688.21</font> | <font  color="#1ABD76">-605.91</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font  color="#1ABD76">-0.01</font> | <font  color="#1ABD76">-2.55</font> | <font  color="#1ABD76">-161.85</font> | <font  color="#1ABD76">-11.17</font> | <font  color="#1ABD76">-347.30</font> | <font  color="#1ABD76">-561.13</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font  color="#1ABD76">-0.19</font> | <font  color="#1ABD76">-3.20</font> | <font  color="#1ABD76">-84.04</font> | <font  color="#1ABD76">-8.09</font> | <font  color="#1ABD76">-264.17</font> | <font  color="#1ABD76">-522.63</font> |
| startcode1b-original-data-dpo-pvf | +0.22 | <font  color="#1ABD76">-0.21</font> | <font  color="#1ABD76">-299.40</font> | <font  color="#1ABD76">-14.57</font> | <font  color="#1ABD76">-803.66</font> | <font  color="#1ABD76">-610.86</font> |
| startcode1b-original-data-dpo-pvf-qfs | +0.11 | <font  color="#1ABD76">-1.42</font> | <font  color="#1ABD76">-188.25</font> | <font  color="#1ABD76">-11.86</font> | <font  color="#1ABD76">-314.49</font> | <font  color="#1ABD76">-560.40</font> |
| startcode1b-original-data-sft-1 | +0.18 | <font  color="#1ABD76">-0.35</font> | +440.68 | +6.42 | +1157.26 | <font  color="#1ABD76">-342.09</font> |
| startcode1b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.28</font> | <font  color="#1ABD76">-4.48</font> | <font  color="#1ABD76">-312.84</font> | <font  color="#1ABD76">-15.10</font> | <font  color="#1ABD76">-865.88</font> | <font  color="#1ABD76">-618.78</font> |
| startcode1b-original-data-dpo-pvf-qra | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-2.13</font> | <font  color="#1ABD76">-314.80</font> | <font  color="#1ABD76">-14.74</font> | <font  color="#1ABD76">-842.24</font> | <font  color="#1ABD76">-613.09</font> |
| codedpo | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-2.27</font> | <font  color="#1ABD76">-233.30</font> | <font  color="#1ABD76">-12.95</font> | <font  color="#1ABD76">-657.74</font> | <font  color="#1ABD76">-595.84</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-2.38</font> | <font  color="#1ABD76">-320.01</font> | <font  color="#1ABD76">-15.10</font> | <font  color="#1ABD76">-860.96</font> | <font  color="#1ABD76">-617.37</font> |


==============================

### 对比基准: `sft-Code-Optimise`

> **基准值: {执行时间: 0.67, 归一化执行时间: 3.80, 峰值内存: 88.81, 归一化峰值内存: 1.44, 内存时间面积: 95.54, 归一化内存时间面积: 4.98}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| startcode_1b | +0.54 | +5.66 | <font  color="#1ABD76">-51.04</font> | <font  color="#1ABD76">-0.44</font> | <font  color="#1ABD76">-63.68</font> | <font  color="#1ABD76">-1.14</font> |
| sft-25-original-data-1b | +0.70 | +5.01 | +322.56 | +6.22 | +805.23 | +57.18 |
| sft-25-original-data-1b-dpo-qfs | +0.18 | +1.52 | +38.84 | +0.88 | +79.85 | +6.53 |
| sft-25-original-data-1b-dpo-pvf | +0.28 | +2.65 | +36.39 | +1.19 | +91.25 | +11.16 |
| sft-25-original-data-1b-dpo-qsl | +0.14 | +1.96 | +149.24 | +4.12 | +395.62 | +47.37 |
| sft-25-original-data-1b-dpo-qts | +0.48 | +4.54 | +19.84 | +1.21 | +96.24 | +16.29 |
| sft-codedpo | +0.34 | +3.71 | +55.06 | +2.08 | +338.46 | +44.67 |
| sft-25-original-data-1b-dpo-qra | +0.20 | +1.77 | +118.54 | +3.06 | +430.85 | +37.19 |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | +0.16 | +2.15 | <font  color="#1ABD76">-35.13</font> | <font  color="#1ABD76">-0.17</font> | <font  color="#1ABD76">-45.25</font> | +0.59 |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | +0.05 | +2.06 | <font  color="#1ABD76">-15.36</font> | +0.71 | +18.80 | +12.70 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | +0.12 | +1.10 | +23.13 | +0.52 | +54.80 | +4.50 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | +0.17 | +1.48 | +257.01 | +5.87 | +757.35 | +59.08 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | +0.23 | +2.86 | +65.79 | +2.36 | +166.66 | +25.69 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | +0.39 | +1.73 | <font  color="#1ABD76">-16.93</font> | <font  color="#1ABD76">-0.44</font> | <font  color="#1ABD76">-46.43</font> | <font  color="#1ABD76">-2.80</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | +0.03 | +1.55 | <font  color="#1ABD76">-39.18</font> | <font  color="#1ABD76">-0.11</font> | <font  color="#1ABD76">-47.53</font> | +1.57 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | +0.19 | +2.47 | <font  color="#1ABD76">-49.17</font> | <font  color="#1ABD76">-0.44</font> | <font  color="#1ABD76">-71.00</font> | <font  color="#1ABD76">-2.20</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font  color="#1ABD76">-0.10</font> | +0.59 | <font  color="#1ABD76">-24.77</font> | +0.21 | <font  color="#1ABD76">-20.22</font> | +4.74 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | +0.31 | +2.86 | <font  color="#1ABD76">-34.23</font> | <font  color="#1ABD76">-0.29</font> | <font  color="#1ABD76">-44.15</font> | <font  color="#1ABD76">-0.45</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | +0.36 | +3.45 | <font  color="#1ABD76">-35.10</font> | <font  color="#1ABD76">-0.20</font> | <font  color="#1ABD76">-39.13</font> | +1.00 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | +0.05 | +1.40 | <font  color="#1ABD76">-44.10</font> | <font  color="#1ABD76">-0.40</font> | <font  color="#1ABD76">-65.38</font> | <font  color="#1ABD76">-1.88</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font  color="#1ABD76">-0.16</font> | <font  color="#1ABD76">-0.62</font> | +254.49 | +5.41 | +825.77 | +60.46 |
| sft-25-original-data-1b-dpo-pvf-qts | +0.01 | +0.65 | +40.63 | +1.22 | +104.39 | +9.66 |
| sft-25-original-data-1b-dpo-pvf-qra | +0.22 | +2.42 | +107.90 | +3.49 | +445.30 | +54.44 |
| sft-25-original-data-1b-dpo-pvf-qfs | +0.04 | +1.77 | +185.71 | +6.57 | +528.43 | +92.94 |
| startcode1b-original-data-dpo-pvf | +0.45 | +4.76 | <font  color="#1ABD76">-29.65</font> | +0.09 | <font  color="#1ABD76">-11.06</font> | +4.71 |
| startcode1b-original-data-dpo-pvf-qfs | +0.34 | +3.55 | +81.50 | +2.80 | +478.11 | +55.17 |
| startcode1b-original-data-sft-1 | +0.41 | +4.62 | +710.43 | +21.08 | +1949.86 | +273.48 |
| startcode1b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.05</font> | +0.49 | <font  color="#1ABD76">-43.09</font> | <font  color="#1ABD76">-0.44</font> | <font  color="#1ABD76">-73.28</font> | <font  color="#1ABD76">-3.21</font> |
| startcode1b-original-data-dpo-pvf-qra | +0.18 | +2.84 | <font  color="#1ABD76">-45.05</font> | <font  color="#1ABD76">-0.08</font> | <font  color="#1ABD76">-49.64</font> | +2.48 |
| Code-Optimise | +0.23 | +4.97 | +269.75 | +14.66 | +792.60 | +615.57 |
| codedpo | +0.17 | +2.70 | +36.45 | +1.71 | +134.86 | +19.73 |
| startcode1b-original-data-dpo-pvf-qsl | +0.21 | +2.59 | <font  color="#1ABD76">-50.26</font> | <font  color="#1ABD76">-0.44</font> | <font  color="#1ABD76">-68.36</font> | <font  color="#1ABD76">-1.80</font> |


==============================

### 对比基准: `sft-25-original-data-1b`

> **基准值: {执行时间: 1.37, 归一化执行时间: 8.81, 峰值内存: 411.37, 归一化峰值内存: 7.66, 内存时间面积: 900.77, 归一化内存时间面积: 62.16}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| startcode_1b | <font  color="#1ABD76">-0.16</font> | +0.65 | <font  color="#1ABD76">-373.60</font> | <font  color="#1ABD76">-6.66</font> | <font  color="#1ABD76">-868.91</font> | <font  color="#1ABD76">-58.32</font> |
| sft-25-original-data-1b-dpo-qfs | <font  color="#1ABD76">-0.52</font> | <font  color="#1ABD76">-3.49</font> | <font  color="#1ABD76">-283.72</font> | <font  color="#1ABD76">-5.34</font> | <font  color="#1ABD76">-725.38</font> | <font  color="#1ABD76">-50.65</font> |
| sft-25-original-data-1b-dpo-pvf | <font  color="#1ABD76">-0.42</font> | <font  color="#1ABD76">-2.36</font> | <font  color="#1ABD76">-286.17</font> | <font  color="#1ABD76">-5.03</font> | <font  color="#1ABD76">-713.98</font> | <font  color="#1ABD76">-46.02</font> |
| sft-25-original-data-1b-dpo-qsl | <font  color="#1ABD76">-0.56</font> | <font  color="#1ABD76">-3.05</font> | <font  color="#1ABD76">-173.32</font> | <font  color="#1ABD76">-2.10</font> | <font  color="#1ABD76">-409.61</font> | <font  color="#1ABD76">-9.81</font> |
| sft-25-original-data-1b-dpo-qts | <font  color="#1ABD76">-0.22</font> | <font  color="#1ABD76">-0.47</font> | <font  color="#1ABD76">-302.72</font> | <font  color="#1ABD76">-5.01</font> | <font  color="#1ABD76">-708.99</font> | <font  color="#1ABD76">-40.89</font> |
| sft-codedpo | <font  color="#1ABD76">-0.36</font> | <font  color="#1ABD76">-1.30</font> | <font  color="#1ABD76">-267.50</font> | <font  color="#1ABD76">-4.14</font> | <font  color="#1ABD76">-466.77</font> | <font  color="#1ABD76">-12.51</font> |
| sft-Code-Optimise | <font  color="#1ABD76">-0.70</font> | <font  color="#1ABD76">-5.01</font> | <font  color="#1ABD76">-322.56</font> | <font  color="#1ABD76">-6.22</font> | <font  color="#1ABD76">-805.23</font> | <font  color="#1ABD76">-57.18</font> |
| sft-25-original-data-1b-dpo-qra | <font  color="#1ABD76">-0.50</font> | <font  color="#1ABD76">-3.24</font> | <font  color="#1ABD76">-204.02</font> | <font  color="#1ABD76">-3.16</font> | <font  color="#1ABD76">-374.38</font> | <font  color="#1ABD76">-19.99</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font  color="#1ABD76">-0.54</font> | <font  color="#1ABD76">-2.86</font> | <font  color="#1ABD76">-357.69</font> | <font  color="#1ABD76">-6.39</font> | <font  color="#1ABD76">-850.48</font> | <font  color="#1ABD76">-56.59</font> |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font  color="#1ABD76">-0.65</font> | <font  color="#1ABD76">-2.95</font> | <font  color="#1ABD76">-337.92</font> | <font  color="#1ABD76">-5.51</font> | <font  color="#1ABD76">-786.43</font> | <font  color="#1ABD76">-44.48</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font  color="#1ABD76">-0.58</font> | <font  color="#1ABD76">-3.91</font> | <font  color="#1ABD76">-299.43</font> | <font  color="#1ABD76">-5.70</font> | <font  color="#1ABD76">-750.43</font> | <font  color="#1ABD76">-52.68</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font  color="#1ABD76">-0.53</font> | <font  color="#1ABD76">-3.53</font> | <font  color="#1ABD76">-65.55</font> | <font  color="#1ABD76">-0.35</font> | <font  color="#1ABD76">-47.88</font> | +1.90 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font  color="#1ABD76">-0.47</font> | <font  color="#1ABD76">-2.15</font> | <font  color="#1ABD76">-256.77</font> | <font  color="#1ABD76">-3.86</font> | <font  color="#1ABD76">-638.57</font> | <font  color="#1ABD76">-31.49</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font  color="#1ABD76">-0.31</font> | <font  color="#1ABD76">-3.28</font> | <font  color="#1ABD76">-339.49</font> | <font  color="#1ABD76">-6.66</font> | <font  color="#1ABD76">-851.66</font> | <font  color="#1ABD76">-59.98</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font  color="#1ABD76">-0.67</font> | <font  color="#1ABD76">-3.46</font> | <font  color="#1ABD76">-361.74</font> | <font  color="#1ABD76">-6.33</font> | <font  color="#1ABD76">-852.76</font> | <font  color="#1ABD76">-55.61</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font  color="#1ABD76">-0.51</font> | <font  color="#1ABD76">-2.54</font> | <font  color="#1ABD76">-371.73</font> | <font  color="#1ABD76">-6.66</font> | <font  color="#1ABD76">-876.23</font> | <font  color="#1ABD76">-59.38</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font  color="#1ABD76">-0.80</font> | <font  color="#1ABD76">-4.42</font> | <font  color="#1ABD76">-347.33</font> | <font  color="#1ABD76">-6.01</font> | <font  color="#1ABD76">-825.45</font> | <font  color="#1ABD76">-52.44</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font  color="#1ABD76">-0.39</font> | <font  color="#1ABD76">-2.15</font> | <font  color="#1ABD76">-356.79</font> | <font  color="#1ABD76">-6.51</font> | <font  color="#1ABD76">-849.38</font> | <font  color="#1ABD76">-57.63</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font  color="#1ABD76">-0.34</font> | <font  color="#1ABD76">-1.56</font> | <font  color="#1ABD76">-357.66</font> | <font  color="#1ABD76">-6.42</font> | <font  color="#1ABD76">-844.36</font> | <font  color="#1ABD76">-56.18</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font  color="#1ABD76">-0.65</font> | <font  color="#1ABD76">-3.61</font> | <font  color="#1ABD76">-366.66</font> | <font  color="#1ABD76">-6.62</font> | <font  color="#1ABD76">-870.61</font> | <font  color="#1ABD76">-59.06</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font  color="#1ABD76">-0.86</font> | <font  color="#1ABD76">-5.63</font> | <font  color="#1ABD76">-68.07</font> | <font  color="#1ABD76">-0.81</font> | +20.54 | +3.28 |
| sft-25-original-data-1b-dpo-pvf-qts | <font  color="#1ABD76">-0.69</font> | <font  color="#1ABD76">-4.36</font> | <font  color="#1ABD76">-281.93</font> | <font  color="#1ABD76">-5.00</font> | <font  color="#1ABD76">-700.84</font> | <font  color="#1ABD76">-47.52</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font  color="#1ABD76">-0.48</font> | <font  color="#1ABD76">-2.59</font> | <font  color="#1ABD76">-214.66</font> | <font  color="#1ABD76">-2.73</font> | <font  color="#1ABD76">-359.93</font> | <font  color="#1ABD76">-2.74</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font  color="#1ABD76">-0.66</font> | <font  color="#1ABD76">-3.24</font> | <font  color="#1ABD76">-136.85</font> | +0.35 | <font  color="#1ABD76">-276.80</font> | +35.76 |
| startcode1b-original-data-dpo-pvf | <font  color="#1ABD76">-0.25</font> | <font  color="#1ABD76">-0.25</font> | <font  color="#1ABD76">-352.21</font> | <font  color="#1ABD76">-6.13</font> | <font  color="#1ABD76">-816.29</font> | <font  color="#1ABD76">-52.47</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font  color="#1ABD76">-0.36</font> | <font  color="#1ABD76">-1.46</font> | <font  color="#1ABD76">-241.06</font> | <font  color="#1ABD76">-3.42</font> | <font  color="#1ABD76">-327.12</font> | <font  color="#1ABD76">-2.01</font> |
| startcode1b-original-data-sft-1 | <font  color="#1ABD76">-0.29</font> | <font  color="#1ABD76">-0.39</font> | +387.87 | +14.86 | +1144.63 | +216.30 |
| startcode1b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.75</font> | <font  color="#1ABD76">-4.52</font> | <font  color="#1ABD76">-365.65</font> | <font  color="#1ABD76">-6.66</font> | <font  color="#1ABD76">-878.51</font> | <font  color="#1ABD76">-60.39</font> |
| startcode1b-original-data-dpo-pvf-qra | <font  color="#1ABD76">-0.52</font> | <font  color="#1ABD76">-2.17</font> | <font  color="#1ABD76">-367.61</font> | <font  color="#1ABD76">-6.30</font> | <font  color="#1ABD76">-854.87</font> | <font  color="#1ABD76">-54.70</font> |
| Code-Optimise | <font  color="#1ABD76">-0.47</font> | <font  color="#1ABD76">-0.04</font> | <font  color="#1ABD76">-52.81</font> | +8.44 | <font  color="#1ABD76">-12.63</font> | +558.39 |
| codedpo | <font  color="#1ABD76">-0.53</font> | <font  color="#1ABD76">-2.31</font> | <font  color="#1ABD76">-286.11</font> | <font  color="#1ABD76">-4.51</font> | <font  color="#1ABD76">-670.37</font> | <font  color="#1ABD76">-37.45</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font  color="#1ABD76">-0.49</font> | <font  color="#1ABD76">-2.42</font> | <font  color="#1ABD76">-372.82</font> | <font  color="#1ABD76">-6.66</font> | <font  color="#1ABD76">-873.59</font> | <font  color="#1ABD76">-58.98</font> |


==============================

### 对比基准: `startcode_1b`

> **基准值: {执行时间: 1.21, 归一化执行时间: 9.46, 峰值内存: 37.77, 归一化峰值内存: 1.00, 内存时间面积: 31.86, 归一化内存时间面积: 3.84}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| sft-25-original-data-1b | +0.16 | <font  color="#1ABD76">-0.65</font> | +373.60 | +6.66 | +868.91 | +58.32 |
| sft-25-original-data-1b-dpo-qfs | <font  color="#1ABD76">-0.36</font> | <font  color="#1ABD76">-4.14</font> | +89.88 | +1.32 | +143.53 | +7.67 |
| sft-25-original-data-1b-dpo-pvf | <font  color="#1ABD76">-0.26</font> | <font  color="#1ABD76">-3.01</font> | +87.43 | +1.63 | +154.93 | +12.30 |
| sft-25-original-data-1b-dpo-qsl | <font  color="#1ABD76">-0.40</font> | <font  color="#1ABD76">-3.70</font> | +200.28 | +4.56 | +459.30 | +48.51 |
| sft-25-original-data-1b-dpo-qts | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-1.12</font> | +70.88 | +1.65 | +159.92 | +17.43 |
| sft-codedpo | <font  color="#1ABD76">-0.20</font> | <font  color="#1ABD76">-1.95</font> | +106.10 | +2.52 | +402.14 | +45.81 |
| sft-Code-Optimise | <font  color="#1ABD76">-0.54</font> | <font  color="#1ABD76">-5.66</font> | +51.04 | +0.44 | +63.68 | +1.14 |
| sft-25-original-data-1b-dpo-qra | <font  color="#1ABD76">-0.34</font> | <font  color="#1ABD76">-3.89</font> | +169.58 | +3.50 | +494.53 | +38.33 |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font  color="#1ABD76">-0.38</font> | <font  color="#1ABD76">-3.51</font> | +15.91 | +0.27 | +18.43 | +1.73 |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font  color="#1ABD76">-0.49</font> | <font  color="#1ABD76">-3.60</font> | +35.68 | +1.15 | +82.48 | +13.84 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font  color="#1ABD76">-0.42</font> | <font  color="#1ABD76">-4.56</font> | +74.17 | +0.96 | +118.48 | +5.64 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font  color="#1ABD76">-0.37</font> | <font  color="#1ABD76">-4.18</font> | +308.05 | +6.31 | +821.03 | +60.22 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font  color="#1ABD76">-0.31</font> | <font  color="#1ABD76">-2.80</font> | +116.83 | +2.80 | +230.34 | +26.83 |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font  color="#1ABD76">-0.15</font> | <font  color="#1ABD76">-3.93</font> | +34.11 | 0.00 | +17.25 | <font  color="#1ABD76">-1.66</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font  color="#1ABD76">-0.51</font> | <font  color="#1ABD76">-4.11</font> | +11.86 | +0.33 | +16.15 | +2.71 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font  color="#1ABD76">-0.35</font> | <font  color="#1ABD76">-3.19</font> | +1.87 | 0.00 | <font  color="#1ABD76">-7.32</font> | <font  color="#1ABD76">-1.06</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font  color="#1ABD76">-0.64</font> | <font  color="#1ABD76">-5.07</font> | +26.27 | +0.65 | +43.46 | +5.88 |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font  color="#1ABD76">-0.23</font> | <font  color="#1ABD76">-2.80</font> | +16.81 | +0.15 | +19.53 | +0.69 |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font  color="#1ABD76">-0.18</font> | <font  color="#1ABD76">-2.21</font> | +15.94 | +0.24 | +24.55 | +2.14 |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font  color="#1ABD76">-0.49</font> | <font  color="#1ABD76">-4.26</font> | +6.94 | +0.04 | <font  color="#1ABD76">-1.70</font> | <font  color="#1ABD76">-0.74</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font  color="#1ABD76">-0.70</font> | <font  color="#1ABD76">-6.28</font> | +305.53 | +5.85 | +889.45 | +61.60 |
| sft-25-original-data-1b-dpo-pvf-qts | <font  color="#1ABD76">-0.53</font> | <font  color="#1ABD76">-5.01</font> | +91.67 | +1.66 | +168.07 | +10.80 |
| sft-25-original-data-1b-dpo-pvf-qra | <font  color="#1ABD76">-0.32</font> | <font  color="#1ABD76">-3.24</font> | +158.94 | +3.93 | +508.98 | +55.58 |
| sft-25-original-data-1b-dpo-pvf-qfs | <font  color="#1ABD76">-0.50</font> | <font  color="#1ABD76">-3.89</font> | +236.75 | +7.01 | +592.11 | +94.08 |
| startcode1b-original-data-dpo-pvf | <font  color="#1ABD76">-0.09</font> | <font  color="#1ABD76">-0.90</font> | +21.39 | +0.53 | +52.62 | +5.85 |
| startcode1b-original-data-dpo-pvf-qfs | <font  color="#1ABD76">-0.20</font> | <font  color="#1ABD76">-2.11</font> | +132.54 | +3.24 | +541.79 | +56.31 |
| startcode1b-original-data-sft-1 | <font  color="#1ABD76">-0.13</font> | <font  color="#1ABD76">-1.04</font> | +761.47 | +21.52 | +2013.54 | +274.62 |
| startcode1b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.59</font> | <font  color="#1ABD76">-5.17</font> | +7.95 | 0.00 | <font  color="#1ABD76">-9.60</font> | <font  color="#1ABD76">-2.07</font> |
| startcode1b-original-data-dpo-pvf-qra | <font  color="#1ABD76">-0.36</font> | <font  color="#1ABD76">-2.82</font> | +5.99 | +0.36 | +14.04 | +3.62 |
| Code-Optimise | <font  color="#1ABD76">-0.31</font> | <font  color="#1ABD76">-0.69</font> | +320.79 | +15.10 | +856.28 | +616.71 |
| codedpo | <font  color="#1ABD76">-0.37</font> | <font  color="#1ABD76">-2.96</font> | +87.49 | +2.15 | +198.54 | +20.87 |
| startcode1b-original-data-dpo-pvf-qsl | <font  color="#1ABD76">-0.33</font> | <font  color="#1ABD76">-3.07</font> | +0.78 | 0.00 | <font  color="#1ABD76">-4.68</font> | <font  color="#1ABD76">-0.66</font> |


==============================

### 对比基准: `startcode1b-original-data-sft-1`

> **基准值: {执行时间: 1.08, 归一化执行时间: 8.42, 峰值内存: 799.24, 归一化峰值内存: 22.52, 内存时间面积: 2045.40, 归一化内存时间面积: 278.46}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| startcode_1b | +0.13 | +1.04 | <font  color="#1ABD76">-761.47</font> | <font  color="#1ABD76">-21.52</font> | <font  color="#1ABD76">-2013.54</font> | <font  color="#1ABD76">-274.62</font> |
| sft-25-original-data-1b | +0.29 | +0.39 | <font  color="#1ABD76">-387.87</font> | <font  color="#1ABD76">-14.86</font> | <font  color="#1ABD76">-1144.63</font> | <font  color="#1ABD76">-216.30</font> |
| sft-25-original-data-1b-dpo-qfs | <font  color="#1ABD76">-0.23</font> | <font  color="#1ABD76">-3.10</font> | <font  color="#1ABD76">-671.59</font> | <font  color="#1ABD76">-20.20</font> | <font  color="#1ABD76">-1870.01</font> | <font  color="#1ABD76">-266.95</font> |
| sft-25-original-data-1b-dpo-pvf | <font  color="#1ABD76">-0.13</font> | <font  color="#1ABD76">-1.97</font> | <font  color="#1ABD76">-674.04</font> | <font  color="#1ABD76">-19.89</font> | <font  color="#1ABD76">-1858.61</font> | <font  color="#1ABD76">-262.32</font> |
| sft-25-original-data-1b-dpo-qsl | <font  color="#1ABD76">-0.27</font> | <font  color="#1ABD76">-2.66</font> | <font  color="#1ABD76">-561.19</font> | <font  color="#1ABD76">-16.96</font> | <font  color="#1ABD76">-1554.24</font> | <font  color="#1ABD76">-226.11</font> |
| sft-25-original-data-1b-dpo-qts | +0.07 | <font  color="#1ABD76">-0.08</font> | <font  color="#1ABD76">-690.59</font> | <font  color="#1ABD76">-19.87</font> | <font  color="#1ABD76">-1853.62</font> | <font  color="#1ABD76">-257.19</font> |
| sft-codedpo | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-0.91</font> | <font  color="#1ABD76">-655.37</font> | <font  color="#1ABD76">-19.00</font> | <font  color="#1ABD76">-1611.40</font> | <font  color="#1ABD76">-228.81</font> |
| sft-Code-Optimise | <font  color="#1ABD76">-0.41</font> | <font  color="#1ABD76">-4.62</font> | <font  color="#1ABD76">-710.43</font> | <font  color="#1ABD76">-21.08</font> | <font  color="#1ABD76">-1949.86</font> | <font  color="#1ABD76">-273.48</font> |
| sft-25-original-data-1b-dpo-qra | <font  color="#1ABD76">-0.21</font> | <font  color="#1ABD76">-2.85</font> | <font  color="#1ABD76">-591.89</font> | <font  color="#1ABD76">-18.02</font> | <font  color="#1ABD76">-1519.01</font> | <font  color="#1ABD76">-236.29</font> |
| sft-25-original-data-1b-dpo-0.2qsl-0.3qts-0.5qfs | <font  color="#1ABD76">-0.25</font> | <font  color="#1ABD76">-2.47</font> | <font  color="#1ABD76">-745.56</font> | <font  color="#1ABD76">-21.25</font> | <font  color="#1ABD76">-1995.11</font> | <font  color="#1ABD76">-272.89</font> |
| sft-25-original-data-1b-dpo-0.3qsl-0.2qts-0.5qfs | <font  color="#1ABD76">-0.36</font> | <font  color="#1ABD76">-2.56</font> | <font  color="#1ABD76">-725.79</font> | <font  color="#1ABD76">-20.37</font> | <font  color="#1ABD76">-1931.06</font> | <font  color="#1ABD76">-260.78</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qfs | <font  color="#1ABD76">-0.29</font> | <font  color="#1ABD76">-3.52</font> | <font  color="#1ABD76">-687.30</font> | <font  color="#1ABD76">-20.56</font> | <font  color="#1ABD76">-1895.06</font> | <font  color="#1ABD76">-268.98</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qra | <font  color="#1ABD76">-0.24</font> | <font  color="#1ABD76">-3.14</font> | <font  color="#1ABD76">-453.42</font> | <font  color="#1ABD76">-15.21</font> | <font  color="#1ABD76">-1192.51</font> | <font  color="#1ABD76">-214.40</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qsl | <font  color="#1ABD76">-0.18</font> | <font  color="#1ABD76">-1.76</font> | <font  color="#1ABD76">-644.64</font> | <font  color="#1ABD76">-18.72</font> | <font  color="#1ABD76">-1783.20</font> | <font  color="#1ABD76">-247.79</font> |
| sft-25-original-data-1b-dpo-0.5pvf-0.5qts | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-2.89</font> | <font  color="#1ABD76">-727.36</font> | <font  color="#1ABD76">-21.52</font> | <font  color="#1ABD76">-1996.29</font> | <font  color="#1ABD76">-276.28</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qfs | <font  color="#1ABD76">-0.38</font> | <font  color="#1ABD76">-3.07</font> | <font  color="#1ABD76">-749.61</font> | <font  color="#1ABD76">-21.19</font> | <font  color="#1ABD76">-1997.39</font> | <font  color="#1ABD76">-271.91</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qts | <font  color="#1ABD76">-0.22</font> | <font  color="#1ABD76">-2.15</font> | <font  color="#1ABD76">-759.60</font> | <font  color="#1ABD76">-21.52</font> | <font  color="#1ABD76">-2020.86</font> | <font  color="#1ABD76">-275.68</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qfs | <font  color="#1ABD76">-0.51</font> | <font  color="#1ABD76">-4.03</font> | <font  color="#1ABD76">-735.20</font> | <font  color="#1ABD76">-20.87</font> | <font  color="#1ABD76">-1970.08</font> | <font  color="#1ABD76">-268.74</font> |
| sft-25-original-data-1b-dpo-0.5qsl-0.5qts | <font  color="#1ABD76">-0.10</font> | <font  color="#1ABD76">-1.76</font> | <font  color="#1ABD76">-744.66</font> | <font  color="#1ABD76">-21.37</font> | <font  color="#1ABD76">-1994.01</font> | <font  color="#1ABD76">-273.93</font> |
| sft-25-original-data-1b-dpo-0.5qts-0.5qfs | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-1.17</font> | <font  color="#1ABD76">-745.53</font> | <font  color="#1ABD76">-21.28</font> | <font  color="#1ABD76">-1988.99</font> | <font  color="#1ABD76">-272.48</font> |
| sft-25-original-data-1b-dpo-0.5qra-0.5qsl | <font  color="#1ABD76">-0.36</font> | <font  color="#1ABD76">-3.22</font> | <font  color="#1ABD76">-754.53</font> | <font  color="#1ABD76">-21.48</font> | <font  color="#1ABD76">-2015.24</font> | <font  color="#1ABD76">-275.36</font> |
| sft-25-original-data-1b-dpo-pvf-qsl | <font  color="#1ABD76">-0.57</font> | <font  color="#1ABD76">-5.24</font> | <font  color="#1ABD76">-455.94</font> | <font  color="#1ABD76">-15.67</font> | <font  color="#1ABD76">-1124.09</font> | <font  color="#1ABD76">-213.02</font> |
| sft-25-original-data-1b-dpo-pvf-qts | <font  color="#1ABD76">-0.40</font> | <font  color="#1ABD76">-3.97</font> | <font  color="#1ABD76">-669.80</font> | <font  color="#1ABD76">-19.86</font> | <font  color="#1ABD76">-1845.47</font> | <font  color="#1ABD76">-263.82</font> |
| sft-25-original-data-1b-dpo-pvf-qra | <font  color="#1ABD76">-0.19</font> | <font  color="#1ABD76">-2.20</font> | <font  color="#1ABD76">-602.53</font> | <font  color="#1ABD76">-17.59</font> | <font  color="#1ABD76">-1504.56</font> | <font  color="#1ABD76">-219.04</font> |
| sft-25-original-data-1b-dpo-pvf-qfs | <font  color="#1ABD76">-0.37</font> | <font  color="#1ABD76">-2.85</font> | <font  color="#1ABD76">-524.72</font> | <font  color="#1ABD76">-14.51</font> | <font  color="#1ABD76">-1421.43</font> | <font  color="#1ABD76">-180.54</font> |
| startcode1b-original-data-dpo-pvf | +0.04 | +0.14 | <font  color="#1ABD76">-740.08</font> | <font  color="#1ABD76">-20.99</font> | <font  color="#1ABD76">-1960.92</font> | <font  color="#1ABD76">-268.77</font> |
| startcode1b-original-data-dpo-pvf-qfs | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-1.07</font> | <font  color="#1ABD76">-628.93</font> | <font  color="#1ABD76">-18.28</font> | <font  color="#1ABD76">-1471.75</font> | <font  color="#1ABD76">-218.31</font> |
| startcode1b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.46</font> | <font  color="#1ABD76">-4.13</font> | <font  color="#1ABD76">-753.52</font> | <font  color="#1ABD76">-21.52</font> | <font  color="#1ABD76">-2023.14</font> | <font  color="#1ABD76">-276.69</font> |
| startcode1b-original-data-dpo-pvf-qra | <font  color="#1ABD76">-0.23</font> | <font  color="#1ABD76">-1.78</font> | <font  color="#1ABD76">-755.48</font> | <font  color="#1ABD76">-21.16</font> | <font  color="#1ABD76">-1999.50</font> | <font  color="#1ABD76">-271.00</font> |
| Code-Optimise | <font  color="#1ABD76">-0.18</font> | +0.35 | <font  color="#1ABD76">-440.68</font> | <font  color="#1ABD76">-6.42</font> | <font  color="#1ABD76">-1157.26</font> | +342.09 |
| codedpo | <font  color="#1ABD76">-0.24</font> | <font  color="#1ABD76">-1.92</font> | <font  color="#1ABD76">-673.98</font> | <font  color="#1ABD76">-19.37</font> | <font  color="#1ABD76">-1815.00</font> | <font  color="#1ABD76">-253.75</font> |
| startcode1b-original-data-dpo-pvf-qsl | <font  color="#1ABD76">-0.20</font> | <font  color="#1ABD76">-2.03</font> | <font  color="#1ABD76">-760.69</font> | <font  color="#1ABD76">-21.52</font> | <font  color="#1ABD76">-2018.22</font> | <font  color="#1ABD76">-275.28</font> |


--- [所有表格生成完毕] ---
