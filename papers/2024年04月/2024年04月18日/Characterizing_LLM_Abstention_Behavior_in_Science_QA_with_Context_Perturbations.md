# 本文通过上下文扰动的方法，探讨了在科学问答领域中大型语言模型的弃权行为特征。

发布时间：2024年04月18日

`LLM理论` `问答系统` `科学教育`

> Characterizing LLM Abstention Behavior in Science QA with Context Perturbations

# 摘要

> 在不确定性面前，模型应选择不回答问题，以防误导用户。本研究探讨了大型语言模型（LLMs）在面对不完整或错误上下文时，能否拒绝回答与上下文相关的科学问题。我们通过多种情境测试了模型的敏感度：去除正确上下文、用无关上下文替代、以及在已有上下文之外增加额外信息。在四个问答（QA）数据集的实验中，我们发现不同模型、不同类型的上下文提供方式，以及问题类型的不同，都会导致性能的显著差异；特别是，许多LLMs在标准问答提示下似乎无法避免回答布尔类型的问题。此外，我们的分析还揭示了放弃回答对问答任务准确度的意外影响。有趣的是，在某些情况下，用无关上下文替换或增加到正确上下文中，可以提升放弃回答的表现，进而提高任务的整体性能。这些发现指出，问答数据集的设计和评估需要改进，以便更有效地评估模型放弃回答的准确性及其对下游任务的影响。

> The correct model response in the face of uncertainty is to abstain from answering a question so as not to mislead the user. In this work, we study the ability of LLMs to abstain from answering context-dependent science questions when provided insufficient or incorrect context. We probe model sensitivity in several settings: removing gold context, replacing gold context with irrelevant context, and providing additional context beyond what is given. In experiments on four QA datasets with four LLMs, we show that performance varies greatly across models, across the type of context provided, and also by question type; in particular, many LLMs seem unable to abstain from answering boolean questions using standard QA prompts. Our analysis also highlights the unexpected impact of abstention performance on QA task accuracy. Counter-intuitively, in some settings, replacing gold context with irrelevant context or adding irrelevant context to gold context can improve abstention performance in a way that results in improvements in task performance. Our results imply that changes are needed in QA dataset design and evaluation to more effectively assess the correctness and downstream impacts of model abstention.

[Arxiv](https://arxiv.org/abs/2404.12452)