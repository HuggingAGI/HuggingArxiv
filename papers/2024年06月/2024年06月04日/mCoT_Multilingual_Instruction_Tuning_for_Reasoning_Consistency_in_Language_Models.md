# mCoT：通过多语言指令调优，确保语言模型推理的一致性

发布时间：2024年06月04日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在多语言环境下的推理能力，通过创建一个新的多语言数学推理数据集（mCoT-MATH）并进行多语言CoT指令调整，以提升模型在不同语言间的推理一致性。这一研究直接应用于LLMs的性能提升，特别是在多语言环境下的应用，因此属于LLM应用分类。` `人工智能`

> mCoT: Multilingual Instruction Tuning for Reasoning Consistency in Language Models

# 摘要

> 思维链（CoT）技术赋予大型语言模型（LLMs）强大的推理能力，助力其在多种下游任务中表现卓越。然而，当前研究多聚焦于英语，对多语言环境的探索尚显不足，这使得不同语言中推理能力的可靠性成为待解之谜。为此，我们采用流行开源LLMs，深入研究了多语言间的推理一致性。首先，我们创建了首个大规模多语言数学推理数据集mCoT-MATH，涵盖11种语言。接着，通过多语言CoT指令调整，我们提升了模型在不同语言间的推理能力，增强了模型的一致性。尽管现有LLMs在不同语言间表现差异显著，尤其在资源较少的语言上表现不佳，但我们的7B参数模型mCoT在跨语言一致性上表现出色，性能甚至超越或媲美更大规模的闭源和开源模型。

> Large language models (LLMs) with Chain-of-thought (CoT) have recently emerged as a powerful technique for eliciting reasoning to improve various downstream tasks. As most research mainly focuses on English, with few explorations in a multilingual context, the question of how reliable this reasoning capability is in different languages is still open. To address it directly, we study multilingual reasoning consistency across multiple languages, using popular open-source LLMs. First, we compile the first large-scale multilingual math reasoning dataset, mCoT-MATH, covering eleven diverse languages. Then, we introduce multilingual CoT instruction tuning to boost reasoning capability across languages, thereby improving model consistency. While existing LLMs show substantial variation across the languages we consider, and especially low performance for lesser resourced languages, our 7B parameter model mCoT achieves impressive consistency across languages, and superior or comparable performance to close- and open-source models even of much larger sizes.

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x1.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x2.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x3.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x4.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x5.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x6.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x7.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x9.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x10.png)

![mCoT：通过多语言指令调优，确保语言模型推理的一致性](../../../paper_images/2406.02301/x11.png)

[Arxiv](https://arxiv.org/abs/2406.02301)