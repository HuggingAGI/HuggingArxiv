# 梯度本地化改进了语言模型的终身预训练。

发布时间：2024年11月07日

`LLM理论` `持续学习`

> Gradient Localization Improves Lifelong Pretraining of Language Models

# 摘要

> 在网络规模的文本语料库上训练的大型语言模型（LLMs）已被证明能在其参数中捕获世界知识。然而，语言模型存储不同类型知识的机制却知之甚少。在这项工作中，我们研究了与时间敏感实体相关的两种类型的知识，并证明每种类型都局限于 LLMs 内的不同参数集。我们假设，现有持续学习方法中对知识局部性缺乏考虑导致了以下两个方面：新信息的吸收失败，以及先前学习信息的灾难性遗忘。我们观察到，包含对更新和新提及实体的引用的序列在一部分层中表现出较大的梯度范数。我们证明，针对这些相关层的参数更新可以提高包含时间漂移的语言持续预训练的性能。

> Large Language Models (LLMs) trained on web-scale text corpora have been shown to capture world knowledge in their parameters. However, the mechanism by which language models store different types of knowledge is poorly understood. In this work, we examine two types of knowledge relating to temporally sensitive entities and demonstrate that each type is localized to different sets of parameters within the LLMs. We hypothesize that the lack of consideration of the locality of knowledge in existing continual learning methods contributes to both: the failed uptake of new information, and catastrophic forgetting of previously learned information. We observe that sequences containing references to updated and newly mentioned entities exhibit larger gradient norms in a subset of layers. We demonstrate that targeting parameter updates to these relevant layers can improve the performance of continually pretraining on language containing temporal drift.

[Arxiv](https://arxiv.org/abs/2411.04448)