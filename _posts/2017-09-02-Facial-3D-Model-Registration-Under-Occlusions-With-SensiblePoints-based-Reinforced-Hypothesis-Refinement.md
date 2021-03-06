---
layout: post
title: "Facial 3D Model Registration Under Occlusions With SensiblePoints-based Reinforced Hypothesis Refinement"
date: 2017-09-02 04:00:29
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yuhang Wu, Ioannis A. Kakadiaris
mathjax: true
---

* content
{:toc}

##### Abstract
Registering a 3D facial model to a 2D image under occlusion is difficult. First, not all of the detected facial landmarks are accurate under occlusions. Second, the number of reliable landmarks may not be enough to constrain the problem. We propose a method to synthesize additional points (SensiblePoints) to create pose hypotheses. The visual clues extracted from the fiducial points, non-fiducial points, and facial contour are jointly employed to verify the hypotheses. We define a reward function to measure whether the projected dense 3D model is well-aligned with the confidence maps generated by two fully convolutional networks, and use the function to train recurrent policy networks to move the SensiblePoints. The same reward function is employed in testing to select the best hypothesis from a candidate pool of hypotheses. Experimentation demonstrates that the proposed approach is very promising in solving the facial model registration problem under occlusion.

##### Abstract (translated by Google)
在遮挡下将3D面部模型注册到2D图像是困难的。首先，并非所有检测到的面部标志在遮挡下都是准确的。其次，可靠的地标数量可能不足以约束这个问题。我们提出了一种方法来综合附加点（SensiblePoints）来创建姿态假设。从基准点提取的视觉线索，非基准点和面部轮廓共同用于验证假设。我们定义了一个奖励函数来衡量投影的密集三维模型是否与两个完全卷积网络生成的置信图完全一致，并且使用该函数训练周期性策略网络来移动感知点。测试中使用相同的奖励函数来从候选假设池中选择最佳假设。实验表明，该方法在解决遮挡下人脸模型配准问题方面具有很好的应用前景。

##### URL
[https://arxiv.org/abs/1709.00531](https://arxiv.org/abs/1709.00531)

##### PDF
[https://arxiv.org/pdf/1709.00531](https://arxiv.org/pdf/1709.00531)

