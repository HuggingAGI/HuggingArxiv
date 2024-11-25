# 揭开自我评估的大型语言模型里的上下文感知准则

发布时间：2024年10月28日

`LLM应用` `语言模型` `评估框架`

> Unveiling Context-Aware Criteria in Self-Assessing LLMs

# 摘要

> 大型语言模型（LLMs）用作评估者备受关注，因其在长篇回答评估方面有望比肩人类水平。但当下的 LLM 评估者过度依赖静态的、人为设定的标准，这限制了它们在各类生成任务中的泛化能力以及结合特定上下文知识的能力。本文中，我们提出了一种新颖的自我评估 LLM 框架，将上下文感知标准（SALC）与针对每个评估实例定制的动态知识相融合。这种实例级知识通过提供相关且具上下文感知的见解，指明当前实例特有的重要标准，进而提升了 LLM 评估者的性能。此外，所提框架无需依赖预先设定的人为标准就能无缝适配各种任务，提供了更灵活的评估方式。实证评估显示，我们的方法显著优于现有的基线评估框架，在各类数据集中平均提升了 4.8％。再者，借助知识蒸馏技术，我们对较小语言模型进行微调用于标准生成和评估，以更低成本实现了与较大模型相当甚至更优的性能。我们的方法在 AlpacaEval2 排行榜的 LC 胜率方面也有进步，用于直接偏好优化（DPO）中的偏好数据生成时最高可达 12％，凸显了其作为强大且可扩展评估框架的有效性。

> The use of large language models (LLMs) as evaluators has garnered significant attention due to their potential to rival human-level evaluations in long-form response assessments. However, current LLM evaluators rely heavily on static, human-defined criteria, limiting their ability to generalize across diverse generative tasks and incorporate context-specific knowledge. In this paper, we propose a novel Self-Assessing LLM framework that integrates Context-Aware Criteria (SALC) with dynamic knowledge tailored to each evaluation instance. This instance-level knowledge enhances the LLM evaluator's performance by providing relevant and context-aware insights that pinpoint the important criteria specific to the current instance. Additionally, the proposed framework adapts seamlessly to various tasks without relying on predefined human criteria, offering a more flexible evaluation approach. Empirical evaluations demonstrate that our approach significantly outperforms existing baseline evaluation frameworks, yielding improvements on average 4.8% across a wide variety of datasets. Furthermore, by leveraging knowledge distillation techniques, we fine-tuned smaller language models for criteria generation and evaluation, achieving comparable or superior performance to larger models with much lower cost. Our method also exhibits a improvement in LC Win-Rate in AlpacaEval2 leaderboard up to a 12% when employed for preference data generation in Direct Preference Optimization (DPO), underscoring its efficacy as a robust and scalable evaluation framework.

[Arxiv](https://arxiv.org/abs/2410.21545)