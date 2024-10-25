# SIKeD：用于数学推理的自引导迭代知识蒸馏

发布时间：2024年10月24日

`LLM应用`

> SIKeD: Self-guided Iterative Knowledge Distillation for mathematical reasoning

# 摘要

> 大型语言模型（LLMs）可以通过教导较小的模型生成解决多步推理任务所需的中间推理过程，将其推理技能转移给它们。虽然 LLMs 可以通过各种策略准确地解决推理任务，即使没有微调，但是较小的模型在提炼时表达能力不足，无法在所有策略上适应 LLMs 的分布，并且倾向于优先选择一种策略而不是其他策略。这种对一种策略的依赖给较小的模型在尝试解决可能对其首选策略有困难的推理任务时带来了挑战。为了解决这个问题，我们提出了一种提炼方法 SIKeD（用于数学推理的自引导迭代知识提炼），其中 LLM 教导较小的模型使用不同的策略来处理任务，并且较小的模型使用其自身生成的策略内输出为给定任务选择最合适的策略。训练以自引导的迭代方式继续，在每次训练迭代中，决定如何将 LLM 数据与自身生成的输出相结合。与传统的提炼方法不同，SIKeD 允许较小的模型学习哪种策略适合给定的任务，同时不断学习使用不同的策略来解决任务。我们在各种数学推理数据集上的实验表明，SIKeD 在不同大小的较小模型中显著优于传统的提炼技术。我们的代码可在：https://github.com/kumar-shridhar/SIKeD 获得。

> Large Language Models (LLMs) can transfer their reasoning skills to smaller models by teaching them to generate the intermediate reasoning process required to solve multistep reasoning tasks. While LLMs can accurately solve reasoning tasks through a variety of strategies, even without fine-tuning, smaller models are not expressive enough to fit the LLMs distribution on all strategies when distilled and tend to prioritize one strategy over the others. This reliance on one strategy poses a challenge for smaller models when attempting to solve reasoning tasks that may be difficult with their preferred strategy. To address this, we propose a distillation method SIKeD (Self-guided Iterative Knowledge Distillation for mathematical reasoning), where the LLM teaches the smaller model to approach a task using different strategies and the smaller model uses its self-generated on-policy outputs to choose the most suitable strategy for the given task. The training continues in a self-guided iterative manner, where for each training iteration, a decision is made on how to combine the LLM data with the self-generated outputs. Unlike traditional distillation methods, SIKeD allows the smaller model to learn which strategy is suitable for a given task while continuously learning to solve a task using different strategies. Our experiments on various mathematical reasoning datasets show that SIKeD significantly outperforms traditional distillation techniques across smaller models of different sizes. Our code is available at: https://github.com/kumar-shridhar/SIKeD

[Arxiv](https://arxiv.org/abs/2410.18574)