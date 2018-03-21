---
layout: post
title: "Improving Object Counting with Heatmap Regulation"
date: 2018-03-14 19:52:43
categories: arXiv_CV
tags: arXiv_CV Detection
author: Shubhra Aich, Ian Stavness
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple and effective way to improve one-look regression models for object counting from images. We use class activation map visualizations to illustrate the drawbacks of learning a pure one-look regression model for a counting task. Based on these insights, we enhance one-look regression counting models by regulating activation maps from the final convolution layer of the network with coarse ground-truth activation maps generated from simple dot annotations. We call this strategy heatmap regulation (HR). We show that this simple enhancement effectively suppresses false detections generated by the corresponding one-look baseline model and also improves the performance in terms of false negatives. Evaluations are performed on four different counting datasets --- two for car counting (CARPK, PUCPR+), one for crowd counting (WorldExpo) and another for biological cell counting (VGG-Cells). Adding HR to a simple VGG front-end improves performance on all these benchmarks compared to a simple one-look baseline model and results in state-of-the-art performance for car counting.

##### Abstract (translated by Google)
在本文中，我们提出了一种简单而有效的方法来改善从图像中进行物体计数的单外观回归模型。我们使用类激活地图可视化来说明学习计数任务的纯粹一看回归模型的缺点。基于这些见解，我们通过调整来自网络最终卷积层的激活图与简单点注释生成的粗糙地面真实激活图来增强单看回归计数模型。我们将这种策略称为热图调节（HR）。我们表明，这种简单的增强有效地抑制了由相应的一眼基线模型生成的错误检测，并且还改善了假阴性方面的性能。对四个不同的计数数据集进行评估 - 两个用于计数（CARPK，PUCPR +），一个用于人群计数（WorldExpo），另一个用于生物细胞计数（VGG细胞）。与简单的单一基准模型相比，将HR添加到简单的VGG前端可以提高所有这些基准测试的性能，并且可以获得最新的汽车计数性能。

##### URL
[https://arxiv.org/abs/1803.05494](https://arxiv.org/abs/1803.05494)

##### PDF
[https://arxiv.org/pdf/1803.05494](https://arxiv.org/pdf/1803.05494)
