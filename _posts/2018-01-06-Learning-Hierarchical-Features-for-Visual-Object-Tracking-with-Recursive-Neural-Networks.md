---
layout: post
title: "Learning Hierarchical Features for Visual Object Tracking with Recursive Neural Networks"
date: 2018-01-06 14:39:29
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking CNN Object_Tracking RNN Deep_Learning
author: Li Wang, Ting Liu, Bing Wang, Xulei Yang, Gang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep learning has achieved very promising results in visual object tracking. Deep neural networks in existing tracking methods require a lot of training data to learn a large number of parameters. However, training data is not sufficient for visual object tracking as annotations of a target object are only available in the first frame of a test sequence. In this paper, we propose to learn hierarchical features for visual object tracking by using tree structure based Recursive Neural Networks (RNN), which have fewer parameters than other deep neural networks, e.g. Convolutional Neural Networks (CNN). First, we learn RNN parameters to discriminate between the target object and background in the first frame of a test sequence. Tree structure over local patches of an exemplar region is randomly generated by using a bottom-up greedy search strategy. Given the learned RNN parameters, we create two dictionaries regarding target regions and corresponding local patches based on the learned hierarchical features from both top and leaf nodes of multiple random trees. In each of the subsequent frames, we conduct sparse dictionary coding on all candidates to select the best candidate as the new target location. In addition, we online update two dictionaries to handle appearance changes of target objects. Experimental results demonstrate that our feature learning algorithm can significantly improve tracking performance on benchmark datasets.

##### Abstract (translated by Google)
最近，深度学习在视觉对象跟踪方面取得了非常有希望的成果。现有跟踪方法中的深度神经网络需要大量的训练数据来学习大量的参数。但是，训练数据不足以进行视觉对象跟踪，因为目标对象的注释仅在测试序列的第一帧中可用。在本文中，我们建议通过使用基于树结构的递归神经网络（RNN）来学习用于视觉对象跟踪的分层特征，所述递归神经网络具有比其他深度神经网络（例如，卷积神经网络（CNN）。首先，我们学习RNN参数来区分测试序列的第一帧中的目标对象和背景。通过使用自下而上的贪婪搜索策略来随机生成示例区域的局部区块上的树结构。给定已学习的RNN参数，我们根据多个随机树的顶点和叶节点的学习层次特征，创建两个关于目标区域和相应局部区块的字典。在每个后续帧中，我们对所有候选者进行稀疏字典编码，以选择最佳候选者作为新的目标位置。另外我们在线更新两本字典来处理目标对象的外观变化。实验结果表明，我们的特征学习算法可以显着提高基准数据集上的跟踪性能。

##### URL
[http://arxiv.org/abs/1801.02021](http://arxiv.org/abs/1801.02021)

##### PDF
[http://arxiv.org/pdf/1801.02021](http://arxiv.org/pdf/1801.02021)

