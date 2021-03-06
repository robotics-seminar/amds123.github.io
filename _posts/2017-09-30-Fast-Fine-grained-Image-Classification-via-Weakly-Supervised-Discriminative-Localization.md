---
layout: post
title: "Fast Fine-grained Image Classification via Weakly Supervised Discriminative Localization"
date: 2017-09-30 17:24:21
categories: arXiv_CV
tags: arXiv_CV Attention Weakly_Supervised CNN Image_Classification Classification
author: Xiangteng He, Yuxin Peng, Junjie Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained image classification is to recognize hundreds of subcategories in each basic-level category. Existing methods employ discriminative localization to find the key distinctions among subcategories. However, they generally have two limitations: (1) Discriminative localization relies on region proposal methods to hypothesize the locations of discriminative regions, which are time-consuming. (2) The training of discriminative localization depends on object or part annotations, which are heavily labor-consuming. It is highly challenging to address the two key limitations simultaneously, and existing methods only focus on one of them. Therefore, we propose a weakly supervised discriminative localization approach (WSDL) for fast fine-grained image classification to address the two limitations at the same time, and its main advantages are: (1) n-pathway end-to-end discriminative localization network is designed to improve classification speed, which simultaneously localizes multiple different discriminative regions for one image to boost classification accuracy, and shares full-image convolutional features generated by region proposal network to accelerate the process of generating region proposals as well as reduce the computation of convolutional operation. (2) Multi-level attention guided localization learning is proposed to localize discriminative regions with different focuses automatically, without using object and part annotations, avoiding the labor consumption. Different level attentions focus on different characteristics of the image, which are complementary and boost the classification accuracy. Both are jointly employed to simultaneously improve classification speed and eliminate dependence on object and part annotations. Compared with state-of-the-art methods on 2 widely-used fine-grained image classification datasets, our WSDL approach achieves the best performance.

##### Abstract (translated by Google)
细粒度图像分类是识别每个基本级别类别中的数百个子类别。现有方法采用区分性定位来找出子类别之间的关键区别。然而，它们通常有两个局限性：（1）区分性定位依赖区域提议方法来推测区分区域的位置，这是耗时的。 （2）歧视性定位的训练取决于对象或部分注释，这是非常耗费人力的。同时解决两个关键的局限性是非常具有挑战性的，而现有的方法只关注其中的一个。因此，本文提出了一种快速细粒度图像分类的弱监督判别定位方法（WSDL），以同时解决这两个局限性，其主要优点是：（1）n路径端到端的判别定位网络旨在提高分类速度，同时对一幅图像进行多个不同判别区域的定位，提高分类精度，共享区域提议网络生成的全图像卷积特征，加快区域提议生成过程，减少卷积计算操作。 （2）提出了多层次注意引导下的定位学习，自动定位不同焦点的判别区域，不使用对象和部分注释，避免了人工消耗。不同层次的注意力集中在图像的不同特征上，是互补的，提高了分类精度。两者共同使用，以同时提高分类速度和消除对对象和部分注释的依赖。与2个广泛使用的细粒度图像分类数据集的最新方法相比，我们的WSDL方法实现了最佳性能。

##### URL
[https://arxiv.org/abs/1710.01168](https://arxiv.org/abs/1710.01168)

##### PDF
[https://arxiv.org/pdf/1710.01168](https://arxiv.org/pdf/1710.01168)

