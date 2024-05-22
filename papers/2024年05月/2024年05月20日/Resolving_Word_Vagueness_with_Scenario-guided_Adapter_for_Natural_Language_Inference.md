# 借助场景引导适配器，破解自然语言推理中的词语模糊难题

发布时间：2024年05月20日

`Agent

理由：这篇论文介绍了一种创新的适配器（ScenaFuse），它能够融合预训练的语言知识和视觉信息，以提升自然语言推理（NLI）任务的性能。这种适配器可以被视为一个智能代理（Agent），因为它能够处理和整合多种类型的信息（语言和视觉），并在特定任务（NLI）中做出决策或提供推理。因此，这篇论文更符合Agent分类，因为它描述了一个能够处理多模态信息的智能系统。` `计算机视觉`

> Resolving Word Vagueness with Scenario-guided Adapter for Natural Language Inference

# 摘要

> 自然语言推理（NLI）任务中，传统模型仅依赖语义信息，忽视了情境视觉信息的重要性，这限制了对语言模糊性的全面理解。为此，我们创新性地开发了ScenaFuse适配器，它巧妙融合了预训练的语言知识与视觉信息。通过图像-句子交互模块，我们让视觉与语言在预训练模型中深度互动，并通过图像-句子融合模块自适应地整合两种信息。这一方法不仅弥合了语言与视觉的鸿沟，还显著提升了NLI任务的理解与推理能力。实验证明，ScenaFuse在NLI性能上持续领先。

> Natural Language Inference (NLI) is a crucial task in natural language processing that involves determining the relationship between two sentences, typically referred to as the premise and the hypothesis. However, traditional NLI models solely rely on the semantic information inherent in independent sentences and lack relevant situational visual information, which can hinder a complete understanding of the intended meaning of the sentences due to the ambiguity and vagueness of language. To address this challenge, we propose an innovative ScenaFuse adapter that simultaneously integrates large-scale pre-trained linguistic knowledge and relevant visual information for NLI tasks. Specifically, we first design an image-sentence interaction module to incorporate visuals into the attention mechanism of the pre-trained model, allowing the two modalities to interact comprehensively. Furthermore, we introduce an image-sentence fusion module that can adaptively integrate visual information from images and semantic information from sentences. By incorporating relevant visual information and leveraging linguistic knowledge, our approach bridges the gap between language and vision, leading to improved understanding and inference capabilities in NLI tasks. Extensive benchmark experiments demonstrate that our proposed ScenaFuse, a scenario-guided approach, consistently boosts NLI performance.

[Arxiv](https://arxiv.org/abs/2405.12434)