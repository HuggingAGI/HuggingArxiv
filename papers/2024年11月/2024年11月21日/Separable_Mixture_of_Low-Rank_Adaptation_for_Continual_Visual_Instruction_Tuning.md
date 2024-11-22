# 用于持续视觉指令调优的可分离低秩适应混合

发布时间：2024年11月21日

`LLM应用` `计算机视觉` `持续学习`

> Separable Mixture of Low-Rank Adaptation for Continual Visual Instruction Tuning

# 摘要

> 视觉指令微调（VIT）能让多模态大型语言模型（MLLMs）把众多视觉任务构建成基于语言的指令，从而有效处理这些任务。在此基础上，持续视觉指令微调（CVIT）增强了MLLMs逐步学习新任务的能力，以适应不断变化的功能需求。此前的工作虽通过开发新基准和新方法来减轻灾难性遗忘，从而推动了CVIT的发展，但这些工作大多遵循传统的持续学习范式，忽略了CVIT特有的挑战。我们发现CVIT存在双重形式的灾难性遗忘，即MLLMs不仅会遗忘先前习得的视觉理解，在获取新任务时指令跟随能力也会下降。为应对此问题，我们引入了低秩适应可分离混合（SMoLoRA）框架，它通过两个不同模块实现可分离路由，一个用于视觉理解，另一个用于指令跟随。这种双路由设计能在两个领域进行专门适配，防止遗忘的同时提升性能。此外，我们提出了新的CVIT基准，它超越现有基准，还能评估模型对未见过任务的泛化能力以及处理不同任务中各类指令的能力。大量实验表明，SMoLoRA在减轻双重遗忘、提高对未见过任务的泛化能力以及确保遵循不同指令的稳健性方面，优于现有方法。

> Visual instruction tuning (VIT) enables multimodal large language models (MLLMs) to effectively handle a wide range of vision tasks by framing them as language-based instructions. Building on this, continual visual instruction tuning (CVIT) extends the capability of MLLMs to incrementally learn new tasks, accommodating evolving functionalities. While prior work has advanced CVIT through the development of new benchmarks and approaches to mitigate catastrophic forgetting, these efforts largely follow traditional continual learning paradigms, neglecting the unique challenges specific to CVIT. We identify a dual form of catastrophic forgetting in CVIT, where MLLMs not only forget previously learned visual understanding but also experience a decline in instruction following abilities as they acquire new tasks. To address this, we introduce the Separable Mixture of Low-Rank Adaptation (SMoLoRA) framework, which employs separable routing through two distinct modules - one for visual understanding and another for instruction following. This dual-routing design enables specialized adaptation in both domains, preventing forgetting while improving performance. Furthermore, we propose a novel CVIT benchmark that goes beyond existing benchmarks by additionally evaluating a model's ability to generalize to unseen tasks and handle diverse instructions across various tasks. Extensive experiments demonstrate that SMoLoRA outperforms existing methods in mitigating dual forgetting, improving generalization to unseen tasks, and ensuring robustness in following diverse instructions.

[Arxiv](https://arxiv.org/abs/2411.13949)