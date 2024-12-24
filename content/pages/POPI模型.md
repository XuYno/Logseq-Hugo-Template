---
title: POPI模型
tags:
categories:
date: 2024-12-03
lastMod: 2024-12-09
---
公式
模型参数辨识
|参数|值|
|--|--|
|\alpha|-0.0101|
|\beta|-3.5414|
|$p_0$|-0.7450|

Play算子的阈值和密度函数
| Play算子 | 阈值$r_j$ | 密度函数$p(r_j)$ |
| --- | --- | --- |
| 1 | 0.1 | -0.0101 |
| 2 | 0.2 | -0.0144 |
| 3 | 0.3 | -0.0205 |
| 4 | 0.4 | -0.0293 |
| 5 | 0.5 | -0.0417 |
| 6 | 0.6 | -0.0594 |
| 7 | 0.7 | -0.0847 |
| 8 | 0.8 | -0.1207 |
| 9 | 0.9 | -0.1719 |
| 10 | 1 | -0.2450 |

POPI模型

POPI模型辨识（归一化）
 ![ModelPOPI.png](/assets/modelpopi_1733383586561_0.png)

  + POPI模型辨识

![ModelPOPI_Pro.png](/assets/modelpopi_pro_1732693992087_0.png)

  + POPI模型

![POPI模型.png](/assets/popi模型_1733388218468_0.png)

POPI模型误差

  + POPI模型误差（归一化）

![POPI模型误差.png](/assets/popi模型误差_1733454408283_0.png)

  + POPI模型误差

![symPOPI_error_Pro.png](/assets/sympopi_error_pro_1733452554268_0.png)

  + 最大误差

    + |最大误差(%)|最大误差(rpm)|平均误差(%)|平均误差(rpm)|
|4.55|2.1012|2.34|1.0845|


