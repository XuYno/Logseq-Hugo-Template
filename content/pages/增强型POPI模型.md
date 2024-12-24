---
title: 增强型POPI模型
tags:
categories:
date: 2024-12-03
lastMod: 2024-12-09
---
公式
$$n(t)=\Phi[\nu](t)=p_1\nu(t)^3+p_0\nu(t)+\intop_0^Rp(r)F_r[\nu](t)$$
$$f_r(\nu,z)=\max{(\nu-r,\min{(\nu+r,z))}}$$

模型参数辨识
|参数|值|
|--|--|
|\alpha|-4.6184|
|\beta|15.7166|
|$p_0$|4.9373|
|$p_1$|-0.2264|

Play算子的阈值和密度函数
| Play算子 | 阈值$r_j$ | 密度函数$p(r_j)$ |
| --- | --- | --- |

POPI模型

  + POPI模型辨识（归一化）

![symPOPI.png](/assets/sympopi_1732849921539_0.png)

  + POPI模型辨识

![symPOPI_Pro.png](/assets/sympopi_pro_1732849927975_0.png)

  + POPI模型

![增强型POPI建模.png](/assets/增强型popi建模_1733462500968_0.png)

POPI模型误差

  + POPI模型误差（归一化）

![增强型POPI模型误差(归一).png](/assets/增强型popi模型误差(归一)_1733462131344_0.png)

  + POPI模型误差

![增强型POPI模型误差.png](/assets/增强型popi模型误差_1733462138700_0.png)

  + 误差
|最大误差(%)|最大误差(rpm)|平均误差(%)|平均误差(rpm)|
|2.95|1.3638|1.6958|0.78382|
