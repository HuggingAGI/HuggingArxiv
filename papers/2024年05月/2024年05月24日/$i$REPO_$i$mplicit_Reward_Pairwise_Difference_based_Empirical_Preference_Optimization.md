# $i$REPO：利用隐式奖励的成对差异进行经验偏好优化

发布时间：2024年05月24日

`LLM理论

这篇论文主要探讨了大型语言模型（LLM）的对齐问题，并提出了一种新的对齐框架$i$REPO。该框架通过隐式奖励成对差异回归进行经验偏好优化，利用自生成的数据集来迭代优化对齐策略。这种研究属于LLM理论范畴，因为它关注的是如何改进LLM的内部机制以更好地符合人类预期，而不是直接应用LLM于某个特定任务或领域。此外，论文中提出的算法和实验验证也是理论研究的一部分，旨在理解和改进LLM的工作原理。` `人工智能`

> $i$REPO: $i$mplicit Reward Pairwise Difference based Empirical Preference Optimization

# 摘要

> 尽管大型语言模型（LLM）功能强大，但有时其输出与人类预期不符，需要进行对齐以避免传播错误或偏见信息。传统的基于强化学习的对齐方法面临稳定性挑战，而偏好优化方法则因过度依赖预先收集的硬标签数据集而受限。本文提出了一种名为$i$REPO的新型对齐框架，它通过隐式奖励成对差异回归进行经验偏好优化，利用经验人类（或AI注释者）偏好标记的自生成数据集，通过创新的回归损失函数迭代优化对齐策略。我们还开发了一种新算法，该算法在理想条件下确保最佳效果，并在非理想条件下提供实际性能差距。实验证明，$i$REPO在Phi-2和Mistral-7B模型上有效实现了自我对齐，并在语言模型评估和多轮基准测试中超越了现有方法。

> While astonishingly capable, large Language Models (LLM) can sometimes produce outputs that deviate from human expectations. Such deviations necessitate an alignment phase to prevent disseminating untruthful, toxic, or biased information. Traditional alignment methods based on reinforcement learning often struggle with the identified instability, whereas preference optimization methods are limited by their overfitting to pre-collected hard-label datasets. In this paper, we propose a novel LLM alignment framework named $i$REPO, which utilizes implicit Reward pairwise difference regression for Empirical Preference Optimization. Particularly, $i$REPO employs self-generated datasets labelled by empirical human (or AI annotator) preference to iteratively refine the aligned policy through a novel regression-based loss function. Furthermore, we introduce an innovative algorithm backed by theoretical guarantees for achieving optimal results under ideal assumptions and providing a practical performance-gap result without such assumptions. Experimental results with Phi-2 and Mistral-7B demonstrate that $i$REPO effectively achieves self-alignment using soft-label, self-generated responses and the logit of empirical AI annotators. Furthermore, our approach surpasses preference optimization baselines in evaluations using the Language Model Evaluation Harness and Multi-turn benchmarks.

![$i$REPO：利用隐式奖励的成对差异进行经验偏好优化](../../../paper_images/2405.15230/x1.png)

![$i$REPO：利用隐式奖励的成对差异进行经验偏好优化](../../../paper_images/2405.15230/x2.png)

![$i$REPO：利用隐式奖励的成对差异进行经验偏好优化](../../../paper_images/2405.15230/x3.png)

![$i$REPO：利用隐式奖励的成对差异进行经验偏好优化](../../../paper_images/2405.15230/x4.png)

[Arxiv](https://arxiv.org/abs/2405.15230)