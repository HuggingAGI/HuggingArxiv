# 利用具有感受野感知注意力加权的提示大型语言模型，推动多模态情感识别达到新极限

发布时间：2024年11月26日

`LLM应用` `对话情感分析` `多媒体`

> Push the Limit of Multi-modal Emotion Recognition by Prompting LLMs with Receptive-Field-Aware Attention Weighting

# 摘要

> 要准确理解对话中的情感，通常得借助外部知识。随着大型语言模型（LLMs）愈发强大，我们不再满足于预训练语言模型那有限的能力。然而，LLMs 要么只能处理文本模态，要么处理多媒体信息的成本过高。我们期望能同时利用 LLMs 的强大能力和多媒体模态的补充特性。在本文中，我们提出了一个名为 Lantern 的框架，它能通过利用具有感受野感知注意力加权的大型语言模型提示来提升某个基础模型的性能。该框架训练了一个多任务基础模型，用于生成情感类别概率和维度分数。这些预测作为参考被输入到 LLMs 中，借助其外部知识和上下文理解来调整每个情感类别的预测概率。我们把对话划分成不同的感受野，每个样本恰好包含在 t 个感受野中。最后，LLMs 的预测与具有感受野感知注意力驱动的加权模块相融合。在实验中，基础模型 CORECT 和 SDT 与 GPT-4 或 Llama-3.1-405B 一同部署在 Lantern 中。在 IEMOCAP 中进行的 4 路和 6 路设置的实验表明，Lantern 能够显著提升当前基础模型的性能，分别高达 1.23％和 1.80％。

> Understanding the emotions in a dialogue usually requires external knowledge to accurately understand the contents. As the LLMs become more and more powerful, we do not want to settle on the limited ability of the pre-trained language model. However, the LLMs either can only process text modality or are too expensive to process the multimedia information. We aim to utilize both the power of LLMs and the supplementary features from the multimedia modalities. In this paper, we present a framework, Lantern, that can improve the performance of a certain vanilla model by prompting large language models with receptive-field-aware attention weighting. This framework trained a multi-task vanilla model to produce probabilities of emotion classes and dimension scores. These predictions are fed into the LLMs as references to adjust the predicted probabilities of each emotion class with its external knowledge and contextual understanding. We slice the dialogue into different receptive fields, and each sample is included in exactly t receptive fields. Finally, the predictions of LLMs are merged with a receptive-field-aware attention-driven weighting module. In the experiments, vanilla models CORECT and SDT are deployed in Lantern with GPT-4 or Llama-3.1-405B. The experiments in IEMOCAP with 4-way and 6-way settings demonstrated that the Lantern can significantly improve the performance of current vanilla models by up to 1.23% and 1.80%.

[Arxiv](https://arxiv.org/abs/2411.17674)