---
layout: post
title: "Neural Architecture Construction using EnvelopeNets"
date: 2018-03-18 21:28:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection
author: Purushotham Kamath, Abhishek Singh, Debo Dutta
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, advances in the design of convolutional neural networks have resulted in significant improvements on the image classification and object detection problems. One of the advances is networks built by stacking complex cells, seen in such networks as InceptionNet and NasNet. These cells are either constructed by hand, generated by generative networks or discovered by search. Unlike conventional networks (where layers consist of a convolution block, sampling and non linear unit), the new cells feature more complex designs consisting of several filters and other operators connected in series and parallel. Recently, several cells have been proposed or generated that are supersets of previously proposed custom or generated cells. Influenced by this, we introduce a network construction method based on EnvelopeNets. An EnvelopeNet is a deep convolutional neural network of stacked EnvelopeCells. EnvelopeCells are supersets (or envelopes) of previously proposed handcrafted and generated cells. We propose a method to construct improved network architectures by restructuring EnvelopeNets. The algorithm restructures an EnvelopeNet by rearranging blocks in the network. It identifies blocks to be restructured using metrics derived from the featuremaps collected during a partial training run of the EnvelopeNet. The method requires less computation resources to generate an architecture than an optimized architecture search over the entire search space of blocks. The restructured networks have higher accuracy on the image classification problem on a representative dataset than both the generating EnvelopeNet and an equivalent arbitrary network.

##### Abstract (translated by Google)
近年来，卷积神经网络设计的进步使得图像分类和目标检测问题得到了显着改善。其中一项进展是通过堆叠复杂单元构建的网络，可以在InceptionNet和NasNet等网络中看到。这些细胞或者由手工构建，由生成网络产生或者通过搜索发现。与传统网络（其中层包含卷积块，采样和非线性单元）不同，新单元具有更复杂的设计，其由多个滤波器和其他串联和并联的运算器组成。最近，已经提出或生成了几个单元，它们是以前提出的定制或生成单元的超集。受此影响，我们引入了基于EnvelopeNets的网络构建方法。 EnvelopeNet是一种叠层EnvelopeCells的深度卷积神经网络。 EnvelopeCells是先前提出的手工生成单元的超集（或信封）。我们提出了一种通过重构EnvelopeNets来构建改进的网络体系结构的方法。该算法通过重新排列网络中的块来重构EnvelopeNet。它使用在EnvelopeNet的部分培训运行期间收集的要素图导出的指标来识别要重构的块。该方法需要较少的计算资源来生成体系结构，而不是在整个块的搜索空间上进行优化的体系结构搜索。重构网络在代表性数据集上的图像分类问题的精度要高于生成的EnvelopeNet和等效的任意网络。

##### URL
[https://arxiv.org/abs/1803.06744](https://arxiv.org/abs/1803.06744)

##### PDF
[https://arxiv.org/pdf/1803.06744](https://arxiv.org/pdf/1803.06744)
