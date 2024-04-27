# 远程-FLM 技术报告

发布时间：2024年04月25日

`LLM应用` `机器学习`

> Tele-FLM Technical Report

# 摘要

> 大型语言模型（LLMs）以其卓越的语言理解和生成能力，推动了众多应用的发展。尽管如此，目前对于如何高效扩展这些模型至500亿参数以上，同时减少试错成本和计算资源消耗的详尽且开源的方法论却相对匮乏。本报告中，我们推出了Tele-FLM（亦称FLM-2），一个52亿参数的开源多语言大型语言模型，它采用了稳定而高效的预训练方法，并具备了更强的事实判断力。在文本语料库的BPB测试中，Tele-FLM展现了其卓越的多语言建模能力。在英文和中文的基础模型评估中，它与那些拥有更大预训练运算次数（FLOPs）的开源模型，如Llama2-70B和DeepSeek-67B，表现相当。我们不仅提供了模型权重，还包括了核心设计理念、工程实践和训练细节，期待这些信息能够为学术界和工业界带来裨益。

> Large language models (LLMs) have showcased profound capabilities in language understanding and generation, facilitating a wide array of applications. However, there is a notable paucity of detailed, open-sourced methodologies on efficiently scaling LLMs beyond 50 billion parameters with minimum trial-and-error cost and computational resources. In this report, we introduce Tele-FLM (aka FLM-2), a 52B open-sourced multilingual large language model that features a stable, efficient pre-training paradigm and enhanced factual judgment capabilities. Tele-FLM demonstrates superior multilingual language modeling abilities, measured by BPB on textual corpus. Besides, in both English and Chinese foundation model evaluation, it is comparable to strong open-sourced models that involve larger pre-training FLOPs, such as Llama2-70B and DeepSeek-67B. In addition to the model weights, we share the core designs, engineering practices, and training details, which we expect to benefit both the academic and industrial communities.

[Arxiv](https://arxiv.org/abs/2404.16645)