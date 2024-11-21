# RESTOR：借助机器反学习实现知识恢复

发布时间：2024年10月31日

`LLM应用` `机器学习` `数据处理`

> RESTOR: Knowledge Recovery through Machine Unlearning

# 摘要

> 大型语言模型在网络规模的语料库上训练时，可能会记住不好的数据点，像错误的事实、有版权的内容或者敏感数据。近来，众多机器遗忘方法被提出，旨在把这些数据点从训练好的模型中“抹去”——也就是让模型表现得像从未在这些数据点上训练过。不过，评估遗忘算法的成效颇具挑战。在本研究中，我们基于以下几个维度提出了机器遗忘的 RESTOR 框架：（1）聚焦于现实世界事实知识的任务设定；（2）模拟可能需要遗忘的各类数据点的多种损坏场景；（3）评估指标，不光强调忘掉不良知识，还注重恢复模型在碰到这些数据点之前的初始状态，即恢复性遗忘。RESTOR 有助于挖掘有关热门遗忘算法的一些新颖见解，以及它们的运作机理——比如，发现某些算法只是着重于遗忘要遗忘的知识，而且定位遗忘目标能够提升遗忘性能。代码/数据可在 github.com/k1rezaei/restor 上获取。

> Large language models trained on web-scale corpora can memorize undesirable datapoints such as incorrect facts, copyrighted content or sensitive data. Recently, many machine unlearning methods have been proposed that aim to 'erase' these datapoints from trained models -- that is, revert model behavior to be similar to a model that had never been trained on these datapoints. However, evaluating the success of unlearning algorithms remains challenging. In this work, we propose the RESTOR framework for machine unlearning based on the following dimensions: (1) a task setting that focuses on real-world factual knowledge, (2) a variety of corruption scenarios that emulate different kinds of datapoints that might need to be unlearned, and (3) evaluation metrics that emphasize not just forgetting undesirable knowledge, but also recovering the model's original state before encountering these datapoints, or restorative unlearning. RESTOR helps uncover several novel insights about popular unlearning algorithms, and the mechanisms through which they operate -- for instance, identifying that some algorithms merely emphasize forgetting the knowledge to be unlearned, and that localizing unlearning targets can enhance unlearning performance. Code/data is available at github.com/k1rezaei/restor.

[Arxiv](https://arxiv.org/abs/2411.00204)