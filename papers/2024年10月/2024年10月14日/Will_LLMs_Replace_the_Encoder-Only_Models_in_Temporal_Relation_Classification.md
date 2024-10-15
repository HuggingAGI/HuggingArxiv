# 大型语言模型（LLMs）是否将取代仅编码器模型，成为时间关系分类的新宠？

发布时间：2024年10月14日

`LLM应用` `时间推理`

> Will LLMs Replace the Encoder-Only Models in Temporal Relation Classification?

# 摘要

> 事件间的时间关系检测主要依赖于 RoBERTa 等仅编码器模型。最近，大型语言模型 (LLM) 在时间推理任务中表现出色，但相关研究仅限于闭源模型，限制了结果的可解释性。我们在此探讨 LLM 在时间关系分类任务中的表现与决策过程。通过对比七种开源与闭源 LLM 在上下文学习和轻量级微调下的性能，我们发现 LLM 在上下文学习中的表现显著不如基于 RoBERTa 的小型模型。进一步分析表明，LLM 的自回归特性使其仅关注序列末尾，导致任务表现受限。我们还对比了两种模型的词嵌入，揭示了预训练差异。相关代码与模型已在 GitHub 上公开。

> The automatic detection of temporal relations among events has been mainly investigated with encoder-only models such as RoBERTa. Large Language Models (LLM) have recently shown promising performance in temporal reasoning tasks such as temporal question answering. Nevertheless, recent studies have tested the LLMs' performance in detecting temporal relations of closed-source models only, limiting the interpretability of those results. In this work, we investigate LLMs' performance and decision process in the Temporal Relation Classification task. First, we assess the performance of seven open and closed-sourced LLMs experimenting with in-context learning and lightweight fine-tuning approaches. Results show that LLMs with in-context learning significantly underperform smaller encoder-only models based on RoBERTa. Then, we delve into the possible reasons for this gap by applying explainable methods. The outcome suggests a limitation of LLMs in this task due to their autoregressive nature, which causes them to focus only on the last part of the sequence. Additionally, we evaluate the word embeddings of these two models to better understand their pre-training differences. The code and the fine-tuned models can be found respectively on GitHub.

[Arxiv](https://arxiv.org/abs/2410.10476)