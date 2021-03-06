---
layout: post
title: "Replicating Active Appearance Model by Generator Network"
date: 2018-05-14 04:54:00
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Relation Recognition Face_Recognition
author: Tian Han, Jiawen Wu, Ying Nian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
A recent Cell paper [Chang and Tsao, 2017] reports an interesting discovery. For the face stimuli generated by a pre-trained active appearance model (AAM), the responses of neurons in the areas of the primate brain that are responsible for face recognition exhibit strong linear relationship with the shape variables and appearance variables of the AAM that generates the face stimuli. In this paper, we show that this behavior can be replicated by a deep generative model called the generator network, which assumes that the observed signals are generated by latent random variables via a top-down convolutional neural network. Specifically, we learn the generator network from the face images generated by a pre-trained AAM model using variational auto-encoder, and we show that the inferred latent variables of the learned generator network have strong linear relationship with the shape and appearance variables of the AAM model that generates the face images. Unlike the AAM model that has an explicit shape model where the shape variables generate the control points or landmarks, the generator network has no such shape model and shape variables. Yet the generator network can learn the shape knowledge in the sense that some of the latent variables of the learned generator network capture the shape variations in the face images generated by AAM.

##### Abstract (translated by Google)
最近的Cell文章[Chang and Tsao，2017]报道了一个有趣的发现。对于由预先训练的活动外观模型（AAM）产生的面部刺激，灵长类大脑区域中负责人脸识别的区域中的神经元的响应与产生AAM的形状变量和外观变量呈现出强烈的线性关系，面部刺激。在本文中，我们表明，这种行为可以通过称为生成器网络的深层生成模型来复制，该生成器网络假定观察信号是由潜在随机变量通过自顶向下卷积神经网络生成的。具体来说，我们从使用变分自动编码器的预训练的AAM模型生成的人脸图像中学习生成器网络，并且我们显示所学习的生成器网络的推断的潜变量与形状和外观变量之间具有强的线性关系AAM模型生成人脸图像。与具有形状变量生成控制点或界标的显式形状模型的AAM模型不同，生成器网络没有这种形状模型和形状变量。然而，生成器网络可以学习形状知识，因为学习生成器网络的一些潜在变量捕获由AAM生成的面部图像中的形状变化。

##### URL
[https://arxiv.org/abs/1805.08704](https://arxiv.org/abs/1805.08704)

##### PDF
[https://arxiv.org/pdf/1805.08704](https://arxiv.org/pdf/1805.08704)

