---
layout: post
title: "Improved Image Captioning via Policy Gradient optimization of SPIDEr"
date: 2017-03-18 09:24:38
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Optimization
author: Siqi Liu, Zhenhai Zhu, Ning Ye, Sergio Guadarrama, Kevin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
Current image captioning methods are usually trained via (penalized) maximum likelihood estimation. However, the log-likelihood score of a caption does not correlate well with human assessments of quality. Standard syntactic evaluation metrics, such as BLEU, METEOR and ROUGE, are also not well correlated. The newer SPICE and CIDEr metrics are better correlated, but have traditionally been hard to optimize for. In this paper, we show how to use a policy gradient (PG) method to directly optimize a linear combination of SPICE and CIDEr (a combination we call SPIDEr): the SPICE score ensures our captions are semantically faithful to the image, while CIDEr score ensures our captions are syntactically fluent. The PG method we propose improves on the prior MIXER approach, by using Monte Carlo rollouts instead of mixing MLE training with PG. We show empirically that our algorithm leads to easier optimization and improved results compared to MIXER. Finally, we show that using our PG method we can optimize any of the metrics, including the proposed SPIDEr metric which results in image captions that are strongly preferred by human raters compared to captions generated by the same model but trained to optimize MLE or the COCO metrics.

##### Abstract (translated by Google)
目前的图像字幕方法通常通过（惩罚性）最大似然估计来训练。然而，标题的对数似然分与人的质量评估没有很好的相关性。标准的句法评估指标，如BLEU，METEOR和ROUGE，也没有很好的相关性。较新的SPICE和CIDEr指标更好地相关，但传统上很难优化。在本文中，我们展示了如何使用策略梯度（PG）方法直接优化SPICE和CIDEr（我们称之为SPIDEr）的线性组合：SPICE评分确保我们的标题语义上忠实于图像，而CIDEr评分确保我们的标题语法流畅。我们提出的PG方法改进了之前的MIXER方法，通过使用Monte Carlo rollouts而不是混合MLE训练与PG。我们经验地显示，与MIXER相比，我们的算法导致更容易的优化和改进的结果。最后，我们展示了使用我们的PG方法，我们可以优化任何度量标准，包括建议的SPIDEr度量标准，这会导致图像标题强烈地被人类评估者所偏好，而与同一模型生成的标题相比，训练优化MLE或COCO指标。

##### URL
[https://arxiv.org/abs/1612.00370](https://arxiv.org/abs/1612.00370)

##### PDF
[https://arxiv.org/pdf/1612.00370](https://arxiv.org/pdf/1612.00370)

