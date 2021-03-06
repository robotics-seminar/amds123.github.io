---
layout: post
title: "Deep Learning based Retinal OCT Segmentation"
date: 2018-01-29 20:44:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Semantic_Segmentation Deep_Learning
author: Mike Pekala, Neil Joshi, David E. Freund, Neil M. Bressler, Delia Cabrera DeBuc, Philippe M Burlina
mathjax: true
---

* content
{:toc}

##### Abstract
Our objective is to evaluate the efficacy of methods that use deep learning (DL) for the automatic fine-grained segmentation of optical coherence tomography (OCT) images of the retina. OCT images from 10 patients with mild non-proliferative diabetic retinopathy were used from a public (U. of Miami) dataset. For each patient, five images were available: one image of the fovea center, two images of the perifovea, and two images of the parafovea. For each image, two expert graders each manually annotated five retinal surfaces (i.e. boundaries between pairs of retinal layers). The first grader's annotations were used as ground truth and the second grader's annotations to compute inter-operator agreement. The proposed automated approach segments images using fully convolutional networks (FCNs) together with Gaussian process (GP)-based regression as a post-processing step to improve the quality of the estimates. Using 10-fold cross validation, the performance of the algorithms is determined by computing the per-pixel unsigned error (distance) between the automated estimates and the ground truth annotations generated by the first manual grader. We compare the proposed method against five state of the art automatic segmentation techniques. The results show that the proposed methods compare favorably with state of the art techniques, resulting in the smallest mean unsigned error values and associated standard deviations, and performance is comparable with human annotation of retinal layers from OCT when there is only mild retinopathy. The results suggest that semantic segmentation using FCNs, coupled with regression-based post-processing, can effectively solve the OCT segmentation problem on par with human capabilities with mild retinopathy.

##### Abstract (translated by Google)
我们的目标是评估使用深度学习（DL）的方法对视网膜的光学相干断层扫描（OCT）图像的自动细粒度分割的功效。来自10名轻度非增殖性糖尿病视网膜病变患者的OCT图像来自公共（迈阿密大学）数据集。对于每个患者，有五个图像可用：一个中央凹的图像，两个perifovea图像，两个parafovea图像。对于每个图像，两个专家级别人员手动注释五个视网膜表面（即视网膜层对之间的边界）。一年级学生的注释被用作基础事实和二年级学生的注释来计算运营商之间的协议。所提出的自动化方法使用完全卷积网络（FCN）和基于高斯过程（GP）的回归作为后处理步骤来分割图像，以提高估计的质量。使用10倍交叉验证，通过计算自动估算与第一台手动分级机生成的地面真实注释之间的每像素无符号误差（距离）来确定算法的性能。我们将所提出的方法与五种最先进的自动分割技术进行比较。结果表明，所提出的方法与现有技术相比较有利，导致最小的平均无符号误差值和相关的标准偏差，并且性能与只有轻度视网膜病变的OCT的视网膜层的人注释相当。结果表明，使用FCN进行语义分割，结合基于回归的后处理，可以有效地解决OCT分割问题，与轻度视网膜病变相媲美。

##### URL
[http://arxiv.org/abs/1801.09749](http://arxiv.org/abs/1801.09749)

##### PDF
[http://arxiv.org/pdf/1801.09749](http://arxiv.org/pdf/1801.09749)

