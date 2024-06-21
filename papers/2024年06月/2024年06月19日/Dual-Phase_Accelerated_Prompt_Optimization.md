# 双阶段加速提示优化策略

发布时间：2024年06月19日

`Agent

这篇论文主要关注的是无梯度提示优化技术，这是一种用于提升闭源大型语言模型性能的方法。论文提出了一种双阶段策略，通过生成高质量的初始提示和迭代优化提示来加速优化过程。这种方法涉及到对语言模型的主动调整和优化，类似于一个智能代理（Agent）在执行任务时的行为，因此将其归类为Agent。` `机器学习`

> Dual-Phase Accelerated Prompt Optimization

# 摘要

> 无梯度提示优化技术在提升闭源大型语言模型性能方面取得了显著进步。然而，现有方法往往忽略了高质量提示初始化的重要性，以及如何找到有效的优化方向，这导致为了达到满意性能，需要进行大量的优化步骤。为此，我们提出了一种双阶段策略，旨在加速提示优化过程，解决低收敛率问题。首先，我们通过精心设计的元指令生成高质量的初始提示，深入挖掘任务特异性信息；接着，在句子级别上迭代优化提示，利用以往的调优经验，扩展提示候选集，并采纳有效的提示。在八个数据集上的实验结果表明，我们的方法能够在不到五个优化步骤内，持续提升准确性，超越现有基线。

> Gradient-free prompt optimization methods have made significant strides in enhancing the performance of closed-source Large Language Models (LLMs) across a wide range of tasks. However, existing approaches make light of the importance of high-quality prompt initialization and the identification of effective optimization directions, thus resulting in substantial optimization steps to obtain satisfactory performance. In this light, we aim to accelerate prompt optimization process to tackle the challenge of low convergence rate. We propose a dual-phase approach which starts with generating high-quality initial prompts by adopting a well-designed meta-instruction to delve into task-specific information, and iteratively optimize the prompts at the sentence level, leveraging previous tuning experience to expand prompt candidates and accept effective ones. Extensive experiments on eight datasets demonstrate the effectiveness of our proposed method, achieving a consistent accuracy gain over baselines with less than five optimization steps.

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x1.png)

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x2.png)

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x3.png)

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x4.png)

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x5.png)

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x6.png)

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x7.png)

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x8.png)

![双阶段加速提示优化策略](../../../paper_images/2406.13443/x9.png)

[Arxiv](https://arxiv.org/abs/2406.13443)