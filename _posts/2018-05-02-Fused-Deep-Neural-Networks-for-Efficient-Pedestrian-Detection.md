---
layout: post
title: "Fused Deep Neural Networks for Efficient Pedestrian Detection"
date: 2018-05-02 00:13:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Classification Detection
author: Xianzhi Du, Mostafa El-Khamy, Vlad I. Morariu, Jungwon Lee, Larry Davis
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an efficient pedestrian detection system, designed by fusion of multiple deep neural network (DNN) systems. Pedestrian candidates are first generated by a single shot convolutional multi-box detector at different locations with various scales and aspect ratios. The candidate generator is designed to provide the majority of ground truth pedestrian annotations at the cost of a large number of false positives. Then, a classification system using the idea of ensemble learning is deployed to improve the detection accuracy. The classification system further classifies the generated candidates based on opinions of multiple deep verification networks and a fusion network which utilizes a novel soft-rejection fusion method to adjust the confidence in the detection results. To improve the training of the deep verification networks, a novel soft-label method is devised to assign floating point labels to the generated pedestrian candidates. A deep context aggregation semantic segmentation network also provides pixel-level classification of the scene and its results are softly fused with the detection results by the single shot detector. Our pedestrian detector compared favorably to state-of-art methods on all popular pedestrian detection datasets. For example, our fused DNN has better detection accuracy on the Caltech Pedestrian dataset than all previous state of art methods, while also being the fastest. We significantly improved the log-average miss rate on the Caltech pedestrian dataset to 7.67% and achieved the new state-of-the-art.

##### Abstract (translated by Google)
在本文中，我们提出了一个高效的行人检测系统，由多个深度神经网络（DNN）系统融合设计。首先通过单次卷积多盒探测器在具有不同比例和纵横比的不同位置生成行人候选者。候选发电机的设计目的是以大量误报为代价提供大部分地面真实行人注释。然后，采用集成学习思想的分类系统来提高检测的准确性。分类系统根据多个深度验证网络和融合网络的意见对生成的候选进一步进行分类，融合网络采用新型软排斥融合方法调整检测结果的置信度。为了改善深度验证网络的训练，设计了一种新的软标签方法来为生成的行人候选者分配浮点标签。深层上下文聚合语义分割网络还提供场景的像素级分类，并且其结果与单次探测器的检测结果软融合。我们的行人探测器与所有流行的行人探测数据集的最先进方法相比毫不逊色。例如，我们的融合DNN在Caltech Pedestrian数据集上的检测精度比以往任何一种先进的方法都要好，同时也是最快的。我们将加州理工行人数据集的对数平均失误率显着提高至7.67％，并实现了最新的最新技术。

##### URL
[https://arxiv.org/abs/1805.08688](https://arxiv.org/abs/1805.08688)

##### PDF
[https://arxiv.org/pdf/1805.08688](https://arxiv.org/pdf/1805.08688)

