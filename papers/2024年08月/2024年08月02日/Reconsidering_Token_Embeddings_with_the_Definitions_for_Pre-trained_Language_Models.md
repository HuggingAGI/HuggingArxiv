# 探讨预训练语言模型中 Token Embeddings 的重新定义

发布时间：2024年08月02日

`LLM应用` `机器学习`

> Reconsidering Token Embeddings with the Definitions for Pre-trained Language Models

# 摘要

> 在自然语言处理领域，基于词元共现统计的嵌入学习在预训练和微调中表现出色。但最新研究发现，这些嵌入存在各向异性问题，导致低频词元的语义信息丢失。本研究深入探讨了BART-large模型的微调过程，并展示了其抗退化能力。以此为基础，我们创新提出DefinitionEMB方法，通过利用定义构建各向同性且富含语义的词元嵌入，确保微调时的鲁棒性。实验结果显示，借助Wiktionary定义构建的嵌入不仅提升了RoBERTa-base和BART-large模型的性能，还显著改善了低频词元在多个GLUE和文本摘要任务中的表现。

> Learning token embeddings based on token co-occurrence statistics has proven effective for both pre-training and fine-tuning in natural language processing. However, recent studies have pointed out the distribution of learned embeddings degenerates into anisotropy, and even pre-trained language models (PLMs) suffer from a loss of semantics-related information in embeddings for low-frequency tokens. This study first analyzes fine-tuning dynamics of a PLM, BART-large, and demonstrates its robustness against degeneration. On the basis of this finding, we propose DefinitionEMB, a method that utilizes definitions to construct isotropically distributed and semantics-related token embeddings for PLMs while maintaining original robustness during fine-tuning. Our experiments demonstrate the effectiveness of leveraging definitions from Wiktionary to construct such embeddings for RoBERTa-base and BART-large. Furthermore, the constructed embeddings for low-frequency tokens improve the performance of these models across various GLUE and four text summarization datasets.

[Arxiv](https://arxiv.org/abs/2408.01308)