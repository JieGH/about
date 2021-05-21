 Jie.Lei@newcastle.ac.uk | Jie.Lei.contact@gmail.com 
 
 [🎓 Google Scholar](https://scholar.google.com/citations?user=g0nZZiMAAAAJ&hl=en&oi=ao){:target="_blank"} 
| [📽 Youtube](https://www.youtube.com/channel/UCbG3LTzpZPVncPePOpqxW9w){:target="_blank"}    |   [🐧 Twitter](https://twitter.com/That_JieLei){:target="_blank"}

---

[⇦ Back Home](https://jiegh.github.io/about/)

#### **4 methods of Current measurement & Comparison**

- [📽 Video on Youtube](https://www.youtube.com/watch?v=l88mAXGDyJU){:target="_blank"}

- [❓ What is Burden Voltage](https://zone.ni.com/reference/en-XX/help/370384V-01/dmm/burden_voltage/#:~:text=Burden%20voltage%20is%20the%20voltage,kept%20as%20low%20as%20possible.){:target="_blank"}

- [❓ What is TinyCurrent](https://www.n-fuse.co/devices/tinyCurrent-precision-low-Current-Measurement-Shunt-and-Amplifier-Device.html){:target="_blank"}

- [❓ What is Shunt resister](https://hackaday.com/2018/02/08/how-current-shunts-work/){:target="_blank"}

---

- 📜 [Wiring & adapter schematic   ](https://github.com/JieGH/about/raw/gh-pages/CurrentMeasurement/Book1.xlsx.pdf){:target="_blank"}

- 📜 [Result in file   ](https://github.com/JieGH/about/blob/gh-pages/CurrentMeasurement/Book1.xlsx.pdf){:target="_blank"}
---
## 1.0 Using Shunt resister

### 1.1 Wiring
<img src="1.png " alt="drawing" style="width:400px;"/>


### 1.2 Meeasurement results:
| V_PowSup 	| V_10KR in V 	| V Drop 	| V_Shunt in mV 	| P_10KR in mW 	| Delta P in mW 	|
|-	|-	|-	|-	|-	|-	|
| 1 	| 0.9878 	| 1.22% 	| 9.812 	| 9.69 	| -0.33 	|
| 1.4 	| 1.3824 	| 1.26% 	| 13.728 	| 18.98 	| -0.64 	|
| 1.8 	| 1.7774 	| 1.26% 	| 17.644 	| 31.36 	| -1.12 	|
| 2.2 	| 2.1716 	| 1.29% 	| 21.557 	| 46.81 	| -1.66 	|
| 2.6 	| 2.5664 	| 1.29% 	| 25.475 	| 65.38 	| -2.39 	|
| 3 	| 2.9609 	| 1.30% 	| 29.388 	| 87.01 	| -3.09 	|
| 3.4 	| 3.3589 	| 1.21% 	| 33.338 	| 111.98 	| -3.74 	|
| 3.8 	| 3.7534 	| 1.23% 	| 37.255 	| 139.83 	| -4.70 	|
| 4.2 	| 4.148 	| 1.24% 	| 41.173 	| 170.79 	| -5.80 	|
| 4.6 	| 4.5425 	| 1.25% 	| 45.093 	| 204.83 	| -7.11 	|
| 5 	| 4.9373 	| 1.25% 	| 49.015 	| 242.00 	| -11.52 	|
| AVG 	|   	| 1.25% 	|   	|   	| -3.83 	|




## 2.0 Using TinyCurrent

### 2.1 Wiring
<img src="2.png " alt="drawing" style="width:400px;"/>


### 2.2 Meeasurement results:
| V_PowSup 	| V_10KR in V 	| V Drop 	| I_10KR in mA 	| P_10KR in mW 	| Delta P in mW 	|
|-	|-	|-	|-	|-	|-	|
| 1 	| 0.9948 	| 0.52% 	| 9.955 	| 9.90 	| -0.12 	|
| 1.4 	| 1.392 	| 0.57% 	| 13.959 	| 19.43 	| -0.19 	|
| 1.8 	| 1.7898 	| 0.57% 	| 17.9839 	| 32.19 	| -0.29 	|
| 2.2 	| 2.1869 	| 0.60% 	| 21.93 	| 47.96 	| -0.52 	|
| 2.6 	| 2.5844 	| 0.60% 	| 25.903 	| 66.94 	| -0.82 	|
| 3 	| 2.9817 	| 0.61% 	| 29.864 	| 89.05 	| -1.06 	|
| 3.4 	| 3.3826 	| 0.51% 	| 33.881 	| 114.61 	| -1.11 	|
| 3.8 	| 3.7797 	| 0.53% 	| 37.859 	| 143.10 	| -1.43 	|
| 4.2 	| 4.1771 	| 0.55% 	| 41.841 	| 174.77 	| -1.81 	|
| 4.6 	| 4.5745 	| 0.55% 	| 45.832 	| 209.66 	| -2.28 	|
| 5 	| 4.972 	| 0.56% 	| 49.818 	| 247.70 	| -5.83 	|
| AVG 	|   	| 0.56% 	|   	|   	| -1.40 	|


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">TinyCurrent</th>
    <th class="tg-0pky">V_10KR in V</th>
    <th class="tg-0pky">V Drop</th>
    <th class="tg-0pky">I_10KR in mA</th>
    <th class="tg-0pky">P_10KR in mW</th>
    <th class="tg-0pky">Delta P in mW</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">1</td>
    <td class="tg-0pky">0.9948</td>
    <td class="tg-0pky">0.52%</td>
    <td class="tg-0pky">9.955</td>
    <td class="tg-0pky">9.90</td>
    <td class="tg-0pky">-0.12</td>
  </tr>
  <tr>
    <td class="tg-0pky">1.4</td>
    <td class="tg-0pky">1.392</td>
    <td class="tg-0pky">0.57%</td>
    <td class="tg-0pky">13.959</td>
    <td class="tg-0pky">19.43</td>
    <td class="tg-0pky">-0.19</td>
  </tr>
  <tr>
    <td class="tg-0pky">1.8</td>
    <td class="tg-0pky">1.7898</td>
    <td class="tg-0pky">0.57%</td>
    <td class="tg-0pky">17.9839</td>
    <td class="tg-0pky">32.19</td>
    <td class="tg-0pky">-0.29</td>
  </tr>
  <tr>
    <td class="tg-0pky">2.2</td>
    <td class="tg-0pky">2.1869</td>
    <td class="tg-0pky">0.60%</td>
    <td class="tg-0pky">21.93</td>
    <td class="tg-0pky">47.96</td>
    <td class="tg-0pky">-0.52</td>
  </tr>
  <tr>
    <td class="tg-0pky">2.6</td>
    <td class="tg-0pky">2.5844</td>
    <td class="tg-0pky">0.60%</td>
    <td class="tg-0pky">25.903</td>
    <td class="tg-0pky">66.94</td>
    <td class="tg-0pky">-0.82</td>
  </tr>
  <tr>
    <td class="tg-0pky">3</td>
    <td class="tg-0pky">2.9817</td>
    <td class="tg-0pky">0.61%</td>
    <td class="tg-0pky">29.864</td>
    <td class="tg-0pky">89.05</td>
    <td class="tg-0pky">-1.06</td>
  </tr>
  <tr>
    <td class="tg-0pky">3.4</td>
    <td class="tg-0pky">3.3826</td>
    <td class="tg-0pky">0.51%</td>
    <td class="tg-0pky">33.881</td>
    <td class="tg-0pky">114.61</td>
    <td class="tg-0pky">-1.11</td>
  </tr>
  <tr>
    <td class="tg-0pky">3.8</td>
    <td class="tg-0pky">3.7797</td>
    <td class="tg-0pky">0.53%</td>
    <td class="tg-0pky">37.859</td>
    <td class="tg-0pky">143.10</td>
    <td class="tg-0pky">-1.43</td>
  </tr>
  <tr>
    <td class="tg-0pky">4.2</td>
    <td class="tg-0pky">4.1771</td>
    <td class="tg-0pky">0.55%</td>
    <td class="tg-0pky">41.841</td>
    <td class="tg-0pky">174.77</td>
    <td class="tg-0pky">-1.81</td>
  </tr>
  <tr>
    <td class="tg-0pky">4.6</td>
    <td class="tg-0pky">4.5745</td>
    <td class="tg-0pky">0.55%</td>
    <td class="tg-0pky">45.832</td>
    <td class="tg-0pky">209.66</td>
    <td class="tg-0pky">-2.28</td>
  </tr>
  <tr>
    <td class="tg-0pky">5</td>
    <td class="tg-0pky">4.972</td>
    <td class="tg-0pky">0.56%</td>
    <td class="tg-0pky">49.818</td>
    <td class="tg-0pky">247.70</td>
    <td class="tg-0pky">-5.83</td>
  </tr>
  <tr>
    <td class="tg-0pky">AVG</td>
    <td class="tg-0pky"> </td>
    <td class="tg-0pky">0.56%</td>
    <td class="tg-0pky"> </td>
    <td class="tg-0pky"> </td>
    <td class="tg-0pky">-1.40</td>
  </tr>
</tbody>
</table>


## 3.0 Using multimeter 

### 3.1 Wiring
<img src="3.png " alt="drawing" style="width:400px;"/>


### 3.2 Meeasurement results:
| V_PowSup 	| V_10KR in V 	| V Drop 	| I_10KR in mA 	| P_10KR in mW 	| Delta P in mW 	|
|-	|-	|-	|-	|-	|-	|
| 1 	| 0.992 	| 0.80% 	| 9.928 	| 9.85 	| -0.17 	|
| 1.4 	| 1.388 	| 0.86% 	| 13.9 	| 19.29 	| -0.32 	|
| 1.8 	| 1.7858 	| 0.79% 	| 17.872 	| 31.92 	| -0.56 	|
| 2.2 	| 2.1821 	| 0.81% 	| 21.839 	| 47.65 	| -0.82 	|
| 2.6 	| 2.5786 	| 0.82% 	| 25.809 	| 66.55 	| -1.22 	|
| 3 	| 2.9751 	| 0.83% 	| 29.777 	| 88.59 	| -1.51 	|
| 3.4 	| 3.3751 	| 0.73% 	| 33.783 	| 114.02 	| -1.69 	|
| 3.8 	| 3.7715 	| 0.75% 	| 37.753 	| 142.39 	| -2.14 	|
| 4.2 	| 4.168 	| 0.76% 	| 41.726 	| 173.91 	| -2.67 	|
| 4.6 	| 4.5645 	| 0.77% 	| 45.7 	| 208.60 	| -3.34 	|
| 5 	| 4.9613 	| 0.77% 	| 49.674 	| 246.45 	| -7.07 	|
| AVG 	|   	| 0.79% 	|   	|   	| -1.96 	|



## 4.0 Using Power Analyzer, 4 Wire 

### 4.1 Wiring
<img src="4.png " alt="drawing" style="width:400px;"/>


### 4.2 Meeasurement results:
| V_PowSup 	| V_10KR in V 	| I_10KR in mA 	| P_10KR in mW 	|
|-	|-	|-	|-	|
| 1 	| 1.00018 	| 10.02 	| 10.02 	|
| 1.4 	| 1.40022 	| 14.01 	| 19.62 	|
| 1.8 	| 1.80024 	| 18.04 	| 32.48 	|
| 2.2 	| 2.2004 	| 22.03 	| 48.47 	|
| 2.6 	| 2.6004 	| 26.06 	| 67.77 	|
| 3 	| 3.0004 	| 30.03 	| 90.10 	|
| 3.4 	| 3.4004 	| 34.03 	| 115.72 	|
| 3.8 	| 3.8004 	| 38.03 	| 144.53 	|
| 4.2 	| 4.2004 	| 42.04 	| 176.58 	|
| 4.6 	| 4.6004 	| 46.07 	| 211.94 	|
| 5 	| 5.0004 	| 50.7 	| 253.52 	|


---

## Delta P cross 3 in-accuract methods


<img src="DeltaP.png " alt="drawing" style="width:300px;"/>


---
---
---

![ ](currentM.jpeg)
