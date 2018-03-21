---
layout: post
title: "Practical Block-wise Neural Network Architecture Generation"
date: 2018-03-13 04:28:33
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Zhao Zhong, Junjie Yan, Wei Wu, Jing Shao, Cheng-Lin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have gained a remarkable success in computer vision. However, most usable network architectures are hand-crafted and usually require expertise and elaborate design. In this paper, we provide a block-wise network generation pipeline called BlockQNN which automatically builds high-performance networks using the Q-Learning paradigm with epsilon-greedy exploration strategy. The optimal network block is constructed by the learning agent which is trained sequentially to choose component layers. We stack the block to construct the whole auto-generated network. To accelerate the generation process, we also propose a distributed asynchronous framework and an early stop strategy. The block-wise generation brings unique advantages: (1) it performs competitive results in comparison to the hand-crafted state-of-the-art networks on image classification, additionally, the best network generated by BlockQNN achieves 3.54% top-1 error rate on CIFAR-10 which beats all existing auto-generate networks. (2) in the meanwhile, it offers tremendous reduction of the search space in designing networks which only spends 3 days with 32 GPUs, and (3) moreover, it has strong generalizability that the network built on CIFAR also performs well on a larger-scale ImageNet dataset.

##### Abstract (translated by Google)
卷积神经网络在计算机视觉领域取得了显着的成功。但是，大多数可用的网络架构都是手工制作的，通常需要专业知识和精心设计。在本文中，我们提供了一个基于块的网络生成管道，称为BlockQNN，它使用具有epsilon-greedy探索策略的Q-Learning范式自动构建高性能网络。最优网络块由学习代理构造，按顺序进行训练以选择组件层。我们将该块堆叠起来以构建整个自动生成的网络。为了加速生成过程，我们还提出了分布式异步框架和早期停止策略。分块代具有独特的优势：（1）与手工制作的最先进的图像分类网络相比，它具有竞争性的结果，另外，BlockQNN生成的最佳网络实现了3.54％的top-1错误在CIFAR-10上打败了所有现有的自动生成网络。 （2）同时，它在设计网络中的搜索空间大大减少，仅花费3天32 GPUs;（3）此外，它具有很强的普遍性，即建立在CIFAR上的网络在较大规模的网络上也表现良好，规模较大的ImageNet数据集。

##### URL
[http://arxiv.org/abs/1708.05552](http://arxiv.org/abs/1708.05552)

##### PDF
[http://arxiv.org/pdf/1708.05552](http://arxiv.org/pdf/1708.05552)
