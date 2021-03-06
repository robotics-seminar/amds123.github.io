---
layout: post
title: "Fooling End-to-end Speaker Verification by Adversarial Examples"
date: 2018-01-10 12:24:34
categories: arXiv_CL
tags: arXiv_CL Adversarial
author: Felix Kreuk, Yossi Adi, Moustapha Cisse, Joseph Keshet
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic speaker verification systems are increasingly used as the primary means to authenticate costumers. Recently, it has been proposed to train speaker verification systems using end-to-end deep neural models. In this paper, we show that such systems are vulnerable to adversarial example attack. Adversarial examples are generated by adding a peculiar noise to original speaker examples, in such a way that they are almost indistinguishable from the original examples by a human listener. Yet, the generated waveforms, which sound as speaker A can be used to fool such a system by claiming as if the waveforms were uttered by speaker B. We present white-box attacks on an end-to-end deep network that was either trained on YOHO or NTIMIT. We also present two black-box attacks: where the adversarial examples were generated with a system that was trained on YOHO, but the attack is on a system that was trained on NTIMIT; and when the adversarial examples were generated with a system that was trained on Mel-spectrum feature set, but the attack is on a system that was trained on MFCC. Results suggest that the accuracy of the attacked system was decreased and the false-positive rate was dramatically increased.

##### Abstract (translated by Google)
自动说话人验证系统越来越多地被用作验证用户的主要手段。最近，已经提出使用端到端深度神经模型训练说话者验证系统。在本文中，我们表明这样的系统容易受到敌对的例子攻击。敌对的例子是通过给原始的演讲者例子添加一个特殊的噪声而产生的，这样的话，他们几乎与原来的例子是由人类的听众区分开来的。然而，所产生的作为说话者A听起来的波形可以用来欺骗这样的系统，声称好像说话者B说出了波形。我们在一个端到端的深度网络上呈现白盒攻击，在YOHO或NTIMIT上。我们还提出了两个黑盒子攻击：对手的例子是在YOHO上训练的系统生成的，但攻击是在NTIMIT上训练过的系统上进行的;并且当对抗例子是利用Mel谱特征集训练的系统产生的，但攻击是在MFCC上训练过的系统上的。结果表明，攻击系统的准确性下降，假阳性率显着增加。

##### URL
[https://arxiv.org/abs/1801.03339](https://arxiv.org/abs/1801.03339)

##### PDF
[https://arxiv.org/pdf/1801.03339](https://arxiv.org/pdf/1801.03339)

