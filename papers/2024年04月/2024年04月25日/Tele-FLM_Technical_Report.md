# 远程-FLM 技术报告

发布时间：2024年04月25日

`分类：LLM应用` `机器学习`

> Tele-FLM Technical Report

# 摘要

> 大型语言模型（LLMs）以其卓越的语言理解和生成能力，推动了多样化应用的发展。尽管如此，目前尚缺乏一种开源、详尽的方法论，用于以最低的试错成本和计算资源，高效地将LLMs扩展至500亿参数以上。本报告向您介绍Tele-FLM（亦称FLM-2），这是一款52B参数的开源多语言大型语言模型，它不仅具备稳定高效的预训练模式，还在事实判断方面表现出色。在文本语料库上通过BPB的评估，Tele-FLM的多语言语言建模能力遥遥领先。在英文和中文基础模型的评估中，它与那些需要更大规模预训练FLOPs的开源模型如Llama2-70B和DeepSeek-67B相比毫不逊色。我们不仅提供了模型权重，还包括了核心设计理念、工程实践和训练细节，期望这些信息能够惠及学术界和工业界的同仁。

> Large language models (LLMs) have showcased profound capabilities in language understanding and generation, facilitating a wide array of applications. However, there is a notable paucity of detailed, open-sourced methodologies on efficiently scaling LLMs beyond 50 billion parameters with minimum trial-and-error cost and computational resources. In this report, we introduce Tele-FLM (aka FLM-2), a 52B open-sourced multilingual large language model that features a stable, efficient pre-training paradigm and enhanced factual judgment capabilities. Tele-FLM demonstrates superior multilingual language modeling abilities, measured by BPB on textual corpus. Besides, in both English and Chinese foundation model evaluation, it is comparable to strong open-sourced models that involve larger pre-training FLOPs, such as Llama2-70B and DeepSeek-67B. In addition to the model weights, we share the core designs, engineering practices, and training details, which we expect to benefit both the academic and industrial communities.

[Arxiv](https://arxiv.org/abs/2404.16645)