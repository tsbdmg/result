### 指标分析总表

**图例:**
* <span style="color:red; font-weight:bold;">红色加粗</span>: 该列中的最大值 (性能最差)。
* 🥇: 该列中的最小值 (性能第一)。
* 🥈: 该列中的第二小值 (性能第二)。
* 🥉: 该列中的第三小值 (性能第三)。

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| deepseek-coder-1.3b-base | 0.43 | 3.21 | 103.47 | 2.77 | 175.79 | 21.50 |
| deepseek1.3b-original-data-25-sft | 🥉0.36 | 2.62 | 🥇43.16 | 🥇1.12 | 🥇30.09 | 🥇3.20 |
| deepseek1.3b-original-data-25-sft-dpo-pvf | 🥉0.36 | 🥈2.46 | 80.90 | 2.24 | 123.13 | 13.45 |
| deepseek1.3b-original-data-25-sft-dpo-qfs | 🥇0.28 | 🥇2.18 | 84.01 | 2.73 | 153.59 | 29.26 |
| deepseek1.3b-original-data-25-sft-dpo-qra | 🥈0.33 | 🥉2.59 | 67.79 | 2.19 | 106.73 | 20.88 |
| deepseek1.3b-original-data-25-sft-dpo-qsl | 0.38 | 2.87 | 121.68 | 3.48 | 241.21 | 33.09 |
| deepseek1.3b-original-data-25-sft-dpo-qts | 0.41 | 2.93 | 🥈47.95 | 🥈1.24 | 🥈42.50 | 🥈4.79 |
| sft-Code-Optimise | 0.42 | 3.20 | 114.70 | 3.23 | 216.82 | 28.93 |
| sft-codedpo | 0.44 | 3.35 | 112.33 | 3.19 | 213.52 | 28.00 |
| deepseek1.3b-original-data-dpo-pvf-qfs | 0.56 | 4.25 | 84.89 | 2.47 | 151.18 | 21.92 |
| deepseek1.3b-original-data-dpo-pvf-qra | <font  color="#E33D30">0.57</font> | <font  color="#E33D30">4.47</font> | 69.02 | 2.07 | 112.18 | 17.35 |
| deepseek1.3b-original-data-dpo-pvf-qsl | 0.46 | 3.46 | 114.13 | 3.31 | 204.47 | 28.30 |
| deepseek1.3b-original-data-dpo-pvf-qts | 0.46 | 3.44 | 110.44 | 3.20 | 196.76 | 28.12 |
| deepseek1.3b-original-data-sft-1 | 0.41 | 3.02 | 113.45 | 3.01 | 212.91 | 24.39 |
| Code-Optimise | 0.48 | 3.66 | <font  color="#E33D30">146.02</font> | <font  color="#E33D30">4.18</font> | <font  color="#E33D30">288.35</font> | <font  color="#E33D30">40.43</font> |
| codedpo | 0.49 | 3.65 | 140.27 | 3.94 | 275.52 | 36.82 |
| deepseek1.3b-original-data-dpo-qfs | 0.42 | 3.16 | 🥉61.74 | 🥉1.75 | 🥉77.65 | 🥉10.84 |
| deepseek1.3b-original-data-dpo-pvf | 0.46 | 3.40 | 133.78 | 3.80 | 257.01 | 35.16 |



--- [开始生成对比表格] ---

==============================

### 对比基准: `sft-codedpo`

> **基准值: {执行时间: 0.44, 归一化执行时间: 3.35, 峰值内存: 112.33, 归一化峰值内存: 3.19, 内存时间面积: 213.52, 归一化内存时间面积: 28.00}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| deepseek-coder-1.3b-base | <font  color="#1ABD76">-0.01</font> | <font  color="#1ABD76">-0.14</font> | <font  color="#1ABD76">-8.86</font> | <font  color="#1ABD76">-0.42</font> | <font  color="#1ABD76">-37.73</font> | <font  color="#1ABD76">-6.50</font> |
| deepseek1.3b-original-data-25-sft | <font  color="#1ABD76">-0.08</font> | <font  color="#1ABD76">-0.73</font> | <font  color="#1ABD76">-69.17</font> | <font  color="#1ABD76">-2.07</font> | <font  color="#1ABD76">-183.43</font> | <font  color="#1ABD76">-24.80</font> |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font  color="#1ABD76">-0.08</font> | <font  color="#1ABD76">-0.89</font> | <font  color="#1ABD76">-31.43</font> | <font  color="#1ABD76">-0.95</font> | <font  color="#1ABD76">-90.39</font> | <font  color="#1ABD76">-14.55</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font  color="#1ABD76">-0.16</font> | <font  color="#1ABD76">-1.17</font> | <font  color="#1ABD76">-28.32</font> | <font  color="#1ABD76">-0.46</font> | <font  color="#1ABD76">-59.93</font> | +1.26 |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font  color="#1ABD76">-0.11</font> | <font  color="#1ABD76">-0.76</font> | <font  color="#1ABD76">-44.54</font> | <font  color="#1ABD76">-1.00</font> | <font  color="#1ABD76">-106.79</font> | <font  color="#1ABD76">-7.12</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-0.48</font> | +9.35 | +0.29 | +27.69 | +5.09 |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.42</font> | <font  color="#1ABD76">-64.38</font> | <font  color="#1ABD76">-1.95</font> | <font  color="#1ABD76">-171.02</font> | <font  color="#1ABD76">-23.21</font> |
| sft-Code-Optimise | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-0.15</font> | +2.37 | +0.04 | +3.30 | +0.93 |
| deepseek1.3b-original-data-dpo-pvf-qfs | +0.12 | +0.90 | <font  color="#1ABD76">-27.44</font> | <font  color="#1ABD76">-0.72</font> | <font  color="#1ABD76">-62.34</font> | <font  color="#1ABD76">-6.08</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | +0.13 | +1.12 | <font  color="#1ABD76">-43.31</font> | <font  color="#1ABD76">-1.12</font> | <font  color="#1ABD76">-101.34</font> | <font  color="#1ABD76">-10.65</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | +0.02 | +0.11 | +1.80 | +0.12 | <font  color="#1ABD76">-9.05</font> | +0.30 |
| deepseek1.3b-original-data-dpo-pvf-qts | +0.02 | +0.09 | <font  color="#1ABD76">-1.89</font> | +0.01 | <font  color="#1ABD76">-16.76</font> | +0.12 |
| deepseek1.3b-original-data-sft-1 | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.33</font> | +1.12 | <font  color="#1ABD76">-0.18</font> | <font  color="#1ABD76">-0.61</font> | <font  color="#1ABD76">-3.61</font> |
| Code-Optimise | +0.04 | +0.31 | +33.69 | +0.99 | +74.83 | +12.43 |
| codedpo | +0.05 | +0.30 | +27.94 | +0.75 | +62.00 | +8.82 |
| deepseek1.3b-original-data-dpo-qfs | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-0.19</font> | <font  color="#1ABD76">-50.59</font> | <font  color="#1ABD76">-1.44</font> | <font  color="#1ABD76">-135.87</font> | <font  color="#1ABD76">-17.16</font> |
| deepseek1.3b-original-data-dpo-pvf | +0.02 | +0.05 | +21.45 | +0.61 | +43.49 | +7.16 |


==============================

### 对比基准: `codedpo`

> **基准值: {执行时间: 0.49, 归一化执行时间: 3.65, 峰值内存: 140.27, 归一化峰值内存: 3.94, 内存时间面积: 275.52, 归一化内存时间面积: 36.82}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| deepseek-coder-1.3b-base | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-0.44</font> | <font  color="#1ABD76">-36.80</font> | <font  color="#1ABD76">-1.17</font> | <font  color="#1ABD76">-99.73</font> | <font  color="#1ABD76">-15.32</font> |
| deepseek1.3b-original-data-25-sft | <font  color="#1ABD76">-0.13</font> | <font  color="#1ABD76">-1.03</font> | <font  color="#1ABD76">-97.11</font> | <font  color="#1ABD76">-2.82</font> | <font  color="#1ABD76">-245.43</font> | <font  color="#1ABD76">-33.62</font> |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font  color="#1ABD76">-0.13</font> | <font  color="#1ABD76">-1.19</font> | <font  color="#1ABD76">-59.37</font> | <font  color="#1ABD76">-1.70</font> | <font  color="#1ABD76">-152.39</font> | <font  color="#1ABD76">-23.37</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font  color="#1ABD76">-0.21</font> | <font  color="#1ABD76">-1.47</font> | <font  color="#1ABD76">-56.26</font> | <font  color="#1ABD76">-1.21</font> | <font  color="#1ABD76">-121.93</font> | <font  color="#1ABD76">-7.56</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font  color="#1ABD76">-0.16</font> | <font  color="#1ABD76">-1.06</font> | <font  color="#1ABD76">-72.48</font> | <font  color="#1ABD76">-1.75</font> | <font  color="#1ABD76">-168.79</font> | <font  color="#1ABD76">-15.94</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font  color="#1ABD76">-0.11</font> | <font  color="#1ABD76">-0.78</font> | <font  color="#1ABD76">-18.59</font> | <font  color="#1ABD76">-0.46</font> | <font  color="#1ABD76">-34.31</font> | <font  color="#1ABD76">-3.73</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font  color="#1ABD76">-0.08</font> | <font  color="#1ABD76">-0.72</font> | <font  color="#1ABD76">-92.32</font> | <font  color="#1ABD76">-2.70</font> | <font  color="#1ABD76">-233.02</font> | <font  color="#1ABD76">-32.03</font> |
| sft-Code-Optimise | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-0.45</font> | <font  color="#1ABD76">-25.57</font> | <font  color="#1ABD76">-0.71</font> | <font  color="#1ABD76">-58.70</font> | <font  color="#1ABD76">-7.89</font> |
| sft-codedpo | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-0.30</font> | <font  color="#1ABD76">-27.94</font> | <font  color="#1ABD76">-0.75</font> | <font  color="#1ABD76">-62.00</font> | <font  color="#1ABD76">-8.82</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | +0.07 | +0.60 | <font  color="#1ABD76">-55.38</font> | <font  color="#1ABD76">-1.47</font> | <font  color="#1ABD76">-124.34</font> | <font  color="#1ABD76">-14.90</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | +0.08 | +0.82 | <font  color="#1ABD76">-71.25</font> | <font  color="#1ABD76">-1.87</font> | <font  color="#1ABD76">-163.34</font> | <font  color="#1ABD76">-19.47</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.19</font> | <font  color="#1ABD76">-26.14</font> | <font  color="#1ABD76">-0.63</font> | <font  color="#1ABD76">-71.05</font> | <font  color="#1ABD76">-8.52</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.21</font> | <font  color="#1ABD76">-29.83</font> | <font  color="#1ABD76">-0.74</font> | <font  color="#1ABD76">-78.76</font> | <font  color="#1ABD76">-8.70</font> |
| deepseek1.3b-original-data-sft-1 | <font  color="#1ABD76">-0.08</font> | <font  color="#1ABD76">-0.63</font> | <font  color="#1ABD76">-26.82</font> | <font  color="#1ABD76">-0.93</font> | <font  color="#1ABD76">-62.61</font> | <font  color="#1ABD76">-12.43</font> |
| Code-Optimise | <font  color="#1ABD76">-0.01</font> | +0.01 | +5.75 | +0.24 | +12.83 | +3.61 |
| deepseek1.3b-original-data-dpo-qfs | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-0.49</font> | <font  color="#1ABD76">-78.53</font> | <font  color="#1ABD76">-2.19</font> | <font  color="#1ABD76">-197.87</font> | <font  color="#1ABD76">-25.98</font> |
| deepseek1.3b-original-data-dpo-pvf | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.25</font> | <font  color="#1ABD76">-6.49</font> | <font  color="#1ABD76">-0.14</font> | <font  color="#1ABD76">-18.51</font> | <font  color="#1ABD76">-1.66</font> |


==============================

### 对比基准: `Code-Optimise`

> **基准值: {执行时间: 0.48, 归一化执行时间: 3.66, 峰值内存: 146.02, 归一化峰值内存: 4.18, 内存时间面积: 288.35, 归一化内存时间面积: 40.43}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| deepseek-coder-1.3b-base | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-0.45</font> | <font  color="#1ABD76">-42.55</font> | <font  color="#1ABD76">-1.41</font> | <font  color="#1ABD76">-112.56</font> | <font  color="#1ABD76">-18.93</font> |
| deepseek1.3b-original-data-25-sft | <font  color="#1ABD76">-0.12</font> | <font  color="#1ABD76">-1.04</font> | <font  color="#1ABD76">-102.86</font> | <font  color="#1ABD76">-3.06</font> | <font  color="#1ABD76">-258.26</font> | <font  color="#1ABD76">-37.23</font> |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font  color="#1ABD76">-0.12</font> | <font  color="#1ABD76">-1.20</font> | <font  color="#1ABD76">-65.12</font> | <font  color="#1ABD76">-1.94</font> | <font  color="#1ABD76">-165.22</font> | <font  color="#1ABD76">-26.98</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font  color="#1ABD76">-0.20</font> | <font  color="#1ABD76">-1.48</font> | <font  color="#1ABD76">-62.01</font> | <font  color="#1ABD76">-1.45</font> | <font  color="#1ABD76">-134.76</font> | <font  color="#1ABD76">-11.17</font> |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font  color="#1ABD76">-0.15</font> | <font  color="#1ABD76">-1.07</font> | <font  color="#1ABD76">-78.23</font> | <font  color="#1ABD76">-1.99</font> | <font  color="#1ABD76">-181.62</font> | <font  color="#1ABD76">-19.55</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font  color="#1ABD76">-0.10</font> | <font  color="#1ABD76">-0.79</font> | <font  color="#1ABD76">-24.34</font> | <font  color="#1ABD76">-0.70</font> | <font  color="#1ABD76">-47.14</font> | <font  color="#1ABD76">-7.34</font> |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-0.73</font> | <font  color="#1ABD76">-98.07</font> | <font  color="#1ABD76">-2.94</font> | <font  color="#1ABD76">-245.85</font> | <font  color="#1ABD76">-35.64</font> |
| sft-Code-Optimise | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-0.46</font> | <font  color="#1ABD76">-31.32</font> | <font  color="#1ABD76">-0.95</font> | <font  color="#1ABD76">-71.53</font> | <font  color="#1ABD76">-11.50</font> |
| sft-codedpo | <font  color="#1ABD76">-0.04</font> | <font  color="#1ABD76">-0.31</font> | <font  color="#1ABD76">-33.69</font> | <font  color="#1ABD76">-0.99</font> | <font  color="#1ABD76">-74.83</font> | <font  color="#1ABD76">-12.43</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | +0.08 | +0.59 | <font  color="#1ABD76">-61.13</font> | <font  color="#1ABD76">-1.71</font> | <font  color="#1ABD76">-137.17</font> | <font  color="#1ABD76">-18.51</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | +0.09 | +0.81 | <font  color="#1ABD76">-77.00</font> | <font  color="#1ABD76">-2.11</font> | <font  color="#1ABD76">-176.17</font> | <font  color="#1ABD76">-23.08</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-0.20</font> | <font  color="#1ABD76">-31.89</font> | <font  color="#1ABD76">-0.87</font> | <font  color="#1ABD76">-83.88</font> | <font  color="#1ABD76">-12.13</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-0.22</font> | <font  color="#1ABD76">-35.58</font> | <font  color="#1ABD76">-0.98</font> | <font  color="#1ABD76">-91.59</font> | <font  color="#1ABD76">-12.31</font> |
| deepseek1.3b-original-data-sft-1 | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-0.64</font> | <font  color="#1ABD76">-32.57</font> | <font  color="#1ABD76">-1.17</font> | <font  color="#1ABD76">-75.44</font> | <font  color="#1ABD76">-16.04</font> |
| codedpo | +0.01 | <font  color="#1ABD76">-0.01</font> | <font  color="#1ABD76">-5.75</font> | <font  color="#1ABD76">-0.24</font> | <font  color="#1ABD76">-12.83</font> | <font  color="#1ABD76">-3.61</font> |
| deepseek1.3b-original-data-dpo-qfs | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-0.50</font> | <font  color="#1ABD76">-84.28</font> | <font  color="#1ABD76">-2.43</font> | <font  color="#1ABD76">-210.70</font> | <font  color="#1ABD76">-29.59</font> |
| deepseek1.3b-original-data-dpo-pvf | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-0.26</font> | <font  color="#1ABD76">-12.24</font> | <font  color="#1ABD76">-0.38</font> | <font  color="#1ABD76">-31.34</font> | <font  color="#1ABD76">-5.27</font> |


==============================

### 对比基准: `sft-Code-Optimise`

> **基准值: {执行时间: 0.42, 归一化执行时间: 3.20, 峰值内存: 114.70, 归一化峰值内存: 3.23, 内存时间面积: 216.82, 归一化内存时间面积: 28.93}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| deepseek-coder-1.3b-base | +0.01 | +0.01 | <font  color="#1ABD76">-11.23</font> | <font  color="#1ABD76">-0.46</font> | <font  color="#1ABD76">-41.03</font> | <font  color="#1ABD76">-7.43</font> |
| deepseek1.3b-original-data-25-sft | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-0.58</font> | <font  color="#1ABD76">-71.54</font> | <font  color="#1ABD76">-2.11</font> | <font  color="#1ABD76">-186.73</font> | <font  color="#1ABD76">-25.73</font> |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font  color="#1ABD76">-0.06</font> | <font  color="#1ABD76">-0.74</font> | <font  color="#1ABD76">-33.80</font> | <font  color="#1ABD76">-0.99</font> | <font  color="#1ABD76">-93.69</font> | <font  color="#1ABD76">-15.48</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font  color="#1ABD76">-0.14</font> | <font  color="#1ABD76">-1.02</font> | <font  color="#1ABD76">-30.69</font> | <font  color="#1ABD76">-0.50</font> | <font  color="#1ABD76">-63.23</font> | +0.33 |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font  color="#1ABD76">-0.09</font> | <font  color="#1ABD76">-0.61</font> | <font  color="#1ABD76">-46.91</font> | <font  color="#1ABD76">-1.04</font> | <font  color="#1ABD76">-110.09</font> | <font  color="#1ABD76">-8.05</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font  color="#1ABD76">-0.04</font> | <font  color="#1ABD76">-0.33</font> | +6.98 | +0.25 | +24.39 | +4.16 |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font  color="#1ABD76">-0.01</font> | <font  color="#1ABD76">-0.27</font> | <font  color="#1ABD76">-66.75</font> | <font  color="#1ABD76">-1.99</font> | <font  color="#1ABD76">-174.32</font> | <font  color="#1ABD76">-24.14</font> |
| sft-codedpo | +0.02 | +0.15 | <font  color="#1ABD76">-2.37</font> | <font  color="#1ABD76">-0.04</font> | <font  color="#1ABD76">-3.30</font> | <font  color="#1ABD76">-0.93</font> |
| deepseek1.3b-original-data-dpo-pvf-qfs | +0.14 | +1.05 | <font  color="#1ABD76">-29.81</font> | <font  color="#1ABD76">-0.76</font> | <font  color="#1ABD76">-65.64</font> | <font  color="#1ABD76">-7.01</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | +0.15 | +1.27 | <font  color="#1ABD76">-45.68</font> | <font  color="#1ABD76">-1.16</font> | <font  color="#1ABD76">-104.64</font> | <font  color="#1ABD76">-11.58</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | +0.04 | +0.26 | <font  color="#1ABD76">-0.57</font> | +0.08 | <font  color="#1ABD76">-12.35</font> | <font  color="#1ABD76">-0.63</font> |
| deepseek1.3b-original-data-dpo-pvf-qts | +0.04 | +0.24 | <font  color="#1ABD76">-4.26</font> | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-20.06</font> | <font  color="#1ABD76">-0.81</font> |
| deepseek1.3b-original-data-sft-1 | <font  color="#1ABD76">-0.01</font> | <font  color="#1ABD76">-0.18</font> | <font  color="#1ABD76">-1.25</font> | <font  color="#1ABD76">-0.22</font> | <font  color="#1ABD76">-3.91</font> | <font  color="#1ABD76">-4.54</font> |
| Code-Optimise | +0.06 | +0.46 | +31.32 | +0.95 | +71.53 | +11.50 |
| codedpo | +0.07 | +0.45 | +25.57 | +0.71 | +58.70 | +7.89 |
| deepseek1.3b-original-data-dpo-qfs | 0.00 | <font  color="#1ABD76">-0.04</font> | <font  color="#1ABD76">-52.96</font> | <font  color="#1ABD76">-1.48</font> | <font  color="#1ABD76">-139.17</font> | <font  color="#1ABD76">-18.09</font> |
| deepseek1.3b-original-data-dpo-pvf | +0.04 | +0.20 | +19.08 | +0.57 | +40.19 | +6.23 |


==============================

### 对比基准: `deepseek1.3b-original-data-25-sft`

> **基准值: {执行时间: 0.36, 归一化执行时间: 2.62, 峰值内存: 43.16, 归一化峰值内存: 1.12, 内存时间面积: 30.09, 归一化内存时间面积: 3.20}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| deepseek-coder-1.3b-base | +0.07 | +0.59 | +60.31 | +1.65 | +145.70 | +18.30 |
| deepseek1.3b-original-data-25-sft-dpo-pvf | 0.00 | <font  color="#1ABD76">-0.16</font> | +37.74 | +1.12 | +93.04 | +10.25 |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font  color="#1ABD76">-0.08</font> | <font  color="#1ABD76">-0.44</font> | +40.85 | +1.61 | +123.50 | +26.06 |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.03</font> | +24.63 | +1.07 | +76.64 | +17.68 |
| deepseek1.3b-original-data-25-sft-dpo-qsl | +0.02 | +0.25 | +78.52 | +2.36 | +211.12 | +29.89 |
| deepseek1.3b-original-data-25-sft-dpo-qts | +0.05 | +0.31 | +4.79 | +0.12 | +12.41 | +1.59 |
| sft-Code-Optimise | +0.06 | +0.58 | +71.54 | +2.11 | +186.73 | +25.73 |
| sft-codedpo | +0.08 | +0.73 | +69.17 | +2.07 | +183.43 | +24.80 |
| deepseek1.3b-original-data-dpo-pvf-qfs | +0.20 | +1.63 | +41.73 | +1.35 | +121.09 | +18.72 |
| deepseek1.3b-original-data-dpo-pvf-qra | +0.21 | +1.85 | +25.86 | +0.95 | +82.09 | +14.15 |
| deepseek1.3b-original-data-dpo-pvf-qsl | +0.10 | +0.84 | +70.97 | +2.19 | +174.38 | +25.10 |
| deepseek1.3b-original-data-dpo-pvf-qts | +0.10 | +0.82 | +67.28 | +2.08 | +166.67 | +24.92 |
| deepseek1.3b-original-data-sft-1 | +0.05 | +0.40 | +70.29 | +1.89 | +182.82 | +21.19 |
| Code-Optimise | +0.12 | +1.04 | +102.86 | +3.06 | +258.26 | +37.23 |
| codedpo | +0.13 | +1.03 | +97.11 | +2.82 | +245.43 | +33.62 |
| deepseek1.3b-original-data-dpo-qfs | +0.06 | +0.54 | +18.58 | +0.63 | +47.56 | +7.64 |
| deepseek1.3b-original-data-dpo-pvf | +0.10 | +0.78 | +90.62 | +2.68 | +226.92 | +31.96 |


==============================

### 对比基准: `deepseek-coder-1.3b-base`

> **基准值: {执行时间: 0.43, 归一化执行时间: 3.21, 峰值内存: 103.47, 归一化峰值内存: 2.77, 内存时间面积: 175.79, 归一化内存时间面积: 21.50}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| deepseek1.3b-original-data-25-sft | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-0.59</font> | <font  color="#1ABD76">-60.31</font> | <font  color="#1ABD76">-1.65</font> | <font  color="#1ABD76">-145.70</font> | <font  color="#1ABD76">-18.30</font> |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font  color="#1ABD76">-0.07</font> | <font  color="#1ABD76">-0.75</font> | <font  color="#1ABD76">-22.57</font> | <font  color="#1ABD76">-0.53</font> | <font  color="#1ABD76">-52.66</font> | <font  color="#1ABD76">-8.05</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font  color="#1ABD76">-0.15</font> | <font  color="#1ABD76">-1.03</font> | <font  color="#1ABD76">-19.46</font> | <font  color="#1ABD76">-0.04</font> | <font  color="#1ABD76">-22.20</font> | +7.76 |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font  color="#1ABD76">-0.10</font> | <font  color="#1ABD76">-0.62</font> | <font  color="#1ABD76">-35.68</font> | <font  color="#1ABD76">-0.58</font> | <font  color="#1ABD76">-69.06</font> | <font  color="#1ABD76">-0.62</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-0.34</font> | +18.21 | +0.71 | +65.42 | +11.59 |
| deepseek1.3b-original-data-25-sft-dpo-qts | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-0.28</font> | <font  color="#1ABD76">-55.52</font> | <font  color="#1ABD76">-1.53</font> | <font  color="#1ABD76">-133.29</font> | <font  color="#1ABD76">-16.71</font> |
| sft-Code-Optimise | <font  color="#1ABD76">-0.01</font> | <font  color="#1ABD76">-0.01</font> | +11.23 | +0.46 | +41.03 | +7.43 |
| sft-codedpo | +0.01 | +0.14 | +8.86 | +0.42 | +37.73 | +6.50 |
| deepseek1.3b-original-data-dpo-pvf-qfs | +0.13 | +1.04 | <font  color="#1ABD76">-18.58</font> | <font  color="#1ABD76">-0.30</font> | <font  color="#1ABD76">-24.61</font> | +0.42 |
| deepseek1.3b-original-data-dpo-pvf-qra | +0.14 | +1.26 | <font  color="#1ABD76">-34.45</font> | <font  color="#1ABD76">-0.70</font> | <font  color="#1ABD76">-63.61</font> | <font  color="#1ABD76">-4.15</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | +0.03 | +0.25 | +10.66 | +0.54 | +28.68 | +6.80 |
| deepseek1.3b-original-data-dpo-pvf-qts | +0.03 | +0.23 | +6.97 | +0.43 | +20.97 | +6.62 |
| deepseek1.3b-original-data-sft-1 | <font  color="#1ABD76">-0.02</font> | <font  color="#1ABD76">-0.19</font> | +9.98 | +0.24 | +37.12 | +2.89 |
| Code-Optimise | +0.05 | +0.45 | +42.55 | +1.41 | +112.56 | +18.93 |
| codedpo | +0.06 | +0.44 | +36.80 | +1.17 | +99.73 | +15.32 |
| deepseek1.3b-original-data-dpo-qfs | <font  color="#1ABD76">-0.01</font> | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-41.73</font> | <font  color="#1ABD76">-1.02</font> | <font  color="#1ABD76">-98.14</font> | <font  color="#1ABD76">-10.66</font> |
| deepseek1.3b-original-data-dpo-pvf | +0.03 | +0.19 | +30.31 | +1.03 | +81.22 | +13.66 |


==============================

### 对比基准: `deepseek1.3b-original-data-sft-1`

> **基准值: {执行时间: 0.41, 归一化执行时间: 3.02, 峰值内存: 113.45, 归一化峰值内存: 3.01, 内存时间面积: 212.91, 归一化内存时间面积: 24.39}**

| 模型 (Model) | 执行时间 | 归一化执行时间 | 峰值内存 | 归一化峰值内存 | 内存时间面积 | 归一化内存时间面积 |
| :--- |  :--- | :--- | :--- | :--- | :--- | :--- |
| deepseek-coder-1.3b-base | +0.02 | +0.19 | <font  color="#1ABD76">-9.98</font> | <font  color="#1ABD76">-0.24</font> | <font  color="#1ABD76">-37.12</font> | <font  color="#1ABD76">-2.89</font> |
| deepseek1.3b-original-data-25-sft | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-0.40</font> | <font  color="#1ABD76">-70.29</font> | <font  color="#1ABD76">-1.89</font> | <font  color="#1ABD76">-182.82</font> | <font  color="#1ABD76">-21.19</font> |
| deepseek1.3b-original-data-25-sft-dpo-pvf | <font  color="#1ABD76">-0.05</font> | <font  color="#1ABD76">-0.56</font> | <font  color="#1ABD76">-32.55</font> | <font  color="#1ABD76">-0.77</font> | <font  color="#1ABD76">-89.78</font> | <font  color="#1ABD76">-10.94</font> |
| deepseek1.3b-original-data-25-sft-dpo-qfs | <font  color="#1ABD76">-0.13</font> | <font  color="#1ABD76">-0.84</font> | <font  color="#1ABD76">-29.44</font> | <font  color="#1ABD76">-0.28</font> | <font  color="#1ABD76">-59.32</font> | +4.87 |
| deepseek1.3b-original-data-25-sft-dpo-qra | <font  color="#1ABD76">-0.08</font> | <font  color="#1ABD76">-0.43</font> | <font  color="#1ABD76">-45.66</font> | <font  color="#1ABD76">-0.82</font> | <font  color="#1ABD76">-106.18</font> | <font  color="#1ABD76">-3.51</font> |
| deepseek1.3b-original-data-25-sft-dpo-qsl | <font  color="#1ABD76">-0.03</font> | <font  color="#1ABD76">-0.15</font> | +8.23 | +0.47 | +28.30 | +8.70 |
| deepseek1.3b-original-data-25-sft-dpo-qts | 0.00 | <font  color="#1ABD76">-0.09</font> | <font  color="#1ABD76">-65.50</font> | <font  color="#1ABD76">-1.77</font> | <font  color="#1ABD76">-170.41</font> | <font  color="#1ABD76">-19.60</font> |
| sft-Code-Optimise | +0.01 | +0.18 | +1.25 | +0.22 | +3.91 | +4.54 |
| sft-codedpo | +0.03 | +0.33 | <font  color="#1ABD76">-1.12</font> | +0.18 | +0.61 | +3.61 |
| deepseek1.3b-original-data-dpo-pvf-qfs | +0.15 | +1.23 | <font  color="#1ABD76">-28.56</font> | <font  color="#1ABD76">-0.54</font> | <font  color="#1ABD76">-61.73</font> | <font  color="#1ABD76">-2.47</font> |
| deepseek1.3b-original-data-dpo-pvf-qra | +0.16 | +1.45 | <font  color="#1ABD76">-44.43</font> | <font  color="#1ABD76">-0.94</font> | <font  color="#1ABD76">-100.73</font> | <font  color="#1ABD76">-7.04</font> |
| deepseek1.3b-original-data-dpo-pvf-qsl | +0.05 | +0.44 | +0.68 | +0.30 | <font  color="#1ABD76">-8.44</font> | +3.91 |
| deepseek1.3b-original-data-dpo-pvf-qts | +0.05 | +0.42 | <font  color="#1ABD76">-3.01</font> | +0.19 | <font  color="#1ABD76">-16.15</font> | +3.73 |
| Code-Optimise | +0.07 | +0.64 | +32.57 | +1.17 | +75.44 | +16.04 |
| codedpo | +0.08 | +0.63 | +26.82 | +0.93 | +62.61 | +12.43 |
| deepseek1.3b-original-data-dpo-qfs | +0.01 | +0.14 | <font  color="#1ABD76">-51.71</font> | <font  color="#1ABD76">-1.26</font> | <font  color="#1ABD76">-135.26</font> | <font  color="#1ABD76">-13.55</font> |
| deepseek1.3b-original-data-dpo-pvf | +0.05 | +0.38 | +20.33 | +0.79 | +44.10 | +10.77 |


--- [所有表格生成完毕] ---
