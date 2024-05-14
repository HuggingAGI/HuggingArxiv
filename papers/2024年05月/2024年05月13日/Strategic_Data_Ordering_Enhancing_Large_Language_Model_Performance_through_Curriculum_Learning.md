# 策略性数据排序：借助课程学习提升大型语言模型的效能在这项研究中，我们探讨了通过精心设计的数据排序策略，即课程学习，来增强大型语言模型性能的方法。课程学习是一种模仿人类教育过程的机器学习方法，它通过逐步增加任务难度来训练模型，从而使模型能够更有效地学习复杂的概念。我们的研究结果表明，合理安排数据顺序可以显著提高模型在各种语言任务中的表现，为优化大型语言模型的训练提供了新的视角。

发布时间：2024年05月13日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的训练策略，特别是基于课程学习的训练方法，以及如何通过优化训练数据的组织来提升模型性能。这种方法关注的是模型训练的理论和方法论层面，而不是特定的应用场景或代理（Agent）的设计，也不是关于检索增强生成（RAG）的具体实现。因此，它更符合LLM理论的分类。` `机器学习`

> Strategic Data Ordering: Enhancing Large Language Model Performance through Curriculum Learning

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，文本理解和生成能力得到了显著提升，但计算资源的挑战也随之而来。本研究提出了一种基于课程学习的训练策略，它从易到难，逐步提升任务复杂度，并利用提示长度、注意力评分和损失值等指标来优化训练数据的组织。实验结果显示，与传统随机数据排序相比，这种策略在Mistral-7B和Gemma-7B模型上带来了轻微的性能提升。特别地，我们发现，依据我们提出的注意力标准对数据进行排序，通常能够获得更佳的性能。这一方法在不扩大模型规模或增加数据集大小的情况下，有效提升了LLM的性能，为解决LLM训练中的可扩展性问题提供了一条可持续的路径。

> The rapid advancement of Large Language Models (LLMs) has improved text understanding and generation but poses challenges in computational resources. This study proposes a curriculum learning-inspired, data-centric training strategy that begins with simpler tasks and progresses to more complex ones, using criteria such as prompt length, attention scores, and loss values to structure the training data. Experiments with Mistral-7B (Jiang et al., 2023) and Gemma-7B (Team et al., 2024) models demonstrate that curriculum learning slightly improves performance compared to traditional random data shuffling. Notably, we observed that sorting data based on our proposed attention criteria generally led to better performance. This approach offers a sustainable method to enhance LLM performance without increasing model size or dataset volume, addressing scalability challenges in LLM training.

[Arxiv](https://arxiv.org/abs/2405.07490)