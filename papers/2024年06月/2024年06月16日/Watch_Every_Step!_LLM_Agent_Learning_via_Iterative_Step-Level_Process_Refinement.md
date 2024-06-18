# 步步为营！通过迭代优化步骤级过程，精进 LLM 代理学习

发布时间：2024年06月16日

`Agent

这篇论文主要讨论了大型语言模型代理在复杂交互任务中的应用，并提出了一个名为迭代步骤级过程细化（IPR）的框架来优化代理的训练过程。该框架通过细致的步骤指导和蒙特卡洛方法评估步骤级奖励，以提高代理在执行任务时的动作效率和准确性。因此，这篇论文更符合Agent分类，因为它专注于代理的设计和优化，而不是理论研究或特定的应用场景。` `人工智能` `自动化`

> Watch Every Step! LLM Agent Learning via Iterative Step-Level Process Refinement

# 摘要

> 大型语言模型代理在复杂交互任务中表现卓越。尽管现有方法通过专家轨迹调整提升了性能，但过分关注结果奖励可能导致因缺乏过程监督而采取错误或次优行动。本文提出的迭代步骤级过程细化（IPR）框架，通过细致的步骤指导优化代理训练。我们运用蒙特卡洛方法评估步骤级奖励，每次迭代中代理沿专家轨迹探索并生成新动作，与专家轨迹的对应步骤比较，以识别差异并生成对比动作对，作为训练数据。实验证明，IPR框架在多个复杂任务中超越了众多强基线，并有效提升了动作效率，适用于多种模型。

> Large language model agents have exhibited exceptional performance across a range of complex interactive tasks. Recent approaches have utilized tuning with expert trajectories to enhance agent performance, yet they primarily concentrate on outcome rewards, which may lead to errors or suboptimal actions due to the absence of process supervision signals. In this paper, we introduce the Iterative step-level Process Refinement (IPR) framework, which provides detailed step-by-step guidance to enhance agent training. Specifically, we adopt the Monte Carlo method to estimate step-level rewards. During each iteration, the agent explores along the expert trajectory and generates new actions. These actions are then evaluated against the corresponding step of expert trajectory using step-level rewards. Such comparison helps identify discrepancies, yielding contrastive action pairs that serve as training data for the agent. Our experiments on three complex agent tasks demonstrate that our framework outperforms a variety of strong baselines. Moreover, our analytical findings highlight the effectiveness of IPR in augmenting action efficiency and its applicability to diverse models.

[Arxiv](https://arxiv.org/abs/2406.11176)