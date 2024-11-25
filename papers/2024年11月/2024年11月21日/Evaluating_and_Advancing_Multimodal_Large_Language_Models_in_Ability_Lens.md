# 对能力视角下的多模态大型语言模型进行评估与推进

发布时间：2024年11月21日

`LLM应用` `多模态` `语言模型`

> Evaluating and Advancing Multimodal Large Language Models in Ability Lens

# 摘要

> 随着多模态大型语言模型（MLLMs）快速进步，严格评估变得极为重要，能为其发展提供更多指引。在此次工作中，我们着重对MLLMs的基础技能——	extbf{视觉感知}能力进行统一且稳健的评估。我们发现，现有的感知基准测试，各自侧重于不同的问题类型、领域和评估指标，导致评估差异显著，若依赖单个基准测试，会使感知能力的综合评估变得复杂。为解决此问题，我们推出了	extbf{AbilityLens}这一统一基准，用于评估MLLMs的六种关键感知能力，兼顾准确性与稳定性，每种能力涵盖多样的问题类型、领域和指标。在AbilityLens的协助下，我们：（1）明确了当前模型的优劣，突出了稳定性模式，还揭示了开源与闭源模型之间显著的性能差距；（2）引入在线评估模式，该模式揭示了MLLM训练期间有趣的能力冲突和早期收敛现象；（3）设计了一种简单的特定能力模型合并方法，它结合了早期训练阶段的最佳能力检查点，有效缓解了因能力冲突造成的性能下降。该基准测试和在线排行榜即将发布。

> As multimodal large language models (MLLMs) advance rapidly, rigorous evaluation has become essential, providing further guidance for their development. In this work, we focus on a unified and robust evaluation of \textbf{vision perception} abilities, the foundational skill of MLLMs. We find that existing perception benchmarks, each focusing on different question types, domains, and evaluation metrics, introduce significant evaluation variance, complicating comprehensive assessments of perception abilities when relying on any single benchmark. To address this, we introduce \textbf{AbilityLens}, a unified benchmark designed to evaluate MLLMs across six key perception abilities, focusing on both accuracy and stability, with each ability encompassing diverse question types, domains, and metrics. With the assistance of AbilityLens, we: (1) identify the strengths and weaknesses of current models, highlighting stability patterns and revealing a notable performance gap between open-source and closed-source models; (2) introduce an online evaluation mode, which uncovers interesting ability conflict and early convergence phenomena during MLLM training; and (3) design a simple ability-specific model merging method that combines the best ability checkpoint from early training stages, effectively mitigating performance decline due to ability conflict. The benchmark and online leaderboard will be released soon.

[Arxiv](https://arxiv.org/abs/2411.14725)