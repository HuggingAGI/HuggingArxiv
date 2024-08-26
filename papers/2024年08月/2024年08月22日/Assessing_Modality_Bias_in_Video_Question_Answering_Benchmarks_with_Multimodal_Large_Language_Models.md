# 探究多模态大型语言模型在视频问答基准测试中的模态偏差

发布时间：2024年08月22日

`LLM应用` `视频分析` `人工智能`

> Assessing Modality Bias in Video Question Answering Benchmarks with Multimodal Large Language Models

# 摘要

> 多模态大型语言模型 (MLLMs) 能同时处理视觉、文本和听觉数据，提供补充人类分析的洞察。然而，现有视频问答 (VidQA) 基准和数据集常偏向单一模态，尽管目标是需要整合多种模态的高级推理技能。为此，我们引入了模态重要性分数 (MIS) 来识别这种偏差，旨在评估哪种模态包含回答问题所需信息。我们还提出了一种创新方法，利用最先进的 MLLMs 估计模态重要性，作为人类模态感知判断的代理。通过 MIS，我们揭示了现有数据集中的单模态偏差和真正多模态问题的稀缺性。通过多项消融研究，我们验证了 MIS，评估了 MLLMs 在排列特征集上的性能。结果显示，因数据集模态不平衡，当前模型未能有效整合信息。我们提出的 MLLM 衍生的 MIS 能指导制作模态平衡的数据集，推动多模态学习，增强 MLLMs 理解和利用跨模态协同关系的能力。

> Multimodal large language models (MLLMs) can simultaneously process visual, textual, and auditory data, capturing insights that complement human analysis. However, existing video question-answering (VidQA) benchmarks and datasets often exhibit a bias toward a single modality, despite the goal of requiring advanced reasoning skills that integrate diverse modalities to answer the queries. In this work, we introduce the modality importance score (MIS) to identify such bias. It is designed to assess which modality embeds the necessary information to answer the question. Additionally, we propose an innovative method using state-of-the-art MLLMs to estimate the modality importance, which can serve as a proxy for human judgments of modality perception. With this MIS, we demonstrate the presence of unimodal bias and the scarcity of genuinely multimodal questions in existing datasets. We further validate the modality importance score with multiple ablation studies to evaluate the performance of MLLMs on permuted feature sets. Our results indicate that current models do not effectively integrate information due to modality imbalance in existing datasets. Our proposed MLLM-derived MIS can guide the curation of modality-balanced datasets that advance multimodal learning and enhance MLLMs' capabilities to understand and utilize synergistic relations across modalities.

[Arxiv](https://arxiv.org/abs/2408.12763)