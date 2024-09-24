# 多语言机器翻译任务中解码器专用模型的缩放法则

发布时间：2024年09月23日

`LLM理论` `机器翻译`

> Scaling Laws of Decoder-Only Models on the Multilingual Machine Translation Task

# 摘要

> 近期研究显示，仅解码器模型在多项 NLP 任务中表现出色，包括翻译。然而，机器翻译领域仍以基于 Transformer 的编码器-解码器模型为主。尽管编码器-解码器模型的缩放法则已得到充分研究，但仅解码器模型却鲜少关注。本研究聚焦于仅解码器模型在多语言和多领域翻译任务中的缩放法则。我们训练了六个参数规模从 70M 到 7B 的仅解码器模型，并进行了一系列实验。结果表明，仅解码器模型的损失可通过类似大型语言模型的缩放法则估算，但该法则在应用于超大模型或不同数据分布时存在局限。此外，我们探讨了不同缩放方法，发现扩展模型深度和宽度虽能带来相似的测试损失改进，但对模型效率的影响各异。

> Recent studies have showcased remarkable capabilities of decoder-only models in many NLP tasks, including translation. Yet, the machine translation field has been largely dominated by encoder-decoder models based on the Transformer architecture. As a consequence, scaling laws of encoder-decoder models for neural machine translation have already been well studied, but decoder-only models have received less attention. This work explores the scaling laws of decoder-only models on the multilingual and multidomain translation task. We trained a collection of six decoder-only models, ranging from 70M to 7B parameters, on a sentence-level, multilingual and multidomain dataset. We conducted a series of experiments showing that the loss of decoder-only models can be estimated using a scaling law similar to the one discovered for large language models, but we also show that this scaling law has difficulties to generalize to too large models or to a different data distribution. We also study different scaling methods and show that scaling the depth and the width of a model lead to similar test loss improvements, but with different impact on the model's efficiency.

[Arxiv](https://arxiv.org/abs/2409.15051)