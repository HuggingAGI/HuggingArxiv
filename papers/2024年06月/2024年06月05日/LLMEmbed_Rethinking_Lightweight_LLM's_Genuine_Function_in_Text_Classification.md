# LLMEmbed：探索轻量级大型语言模型在文本分类中的核心价值

发布时间：2024年06月05日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）进行文本分类，并提出了一种名为LLMEmbed的迁移学习策略。这种方法专注于提高文本分类的性能，并且通过实验证明了其在公开数据集上的有效性和效率。因此，这篇论文属于LLM在实际应用中的研究，即LLM应用分类。` `文本分类` `迁移学习`

> LLMEmbed: Rethinking Lightweight LLM's Genuine Function in Text Classification

# 摘要

> 随着大型语言模型（LLMs）的兴起，提示学习已成为提升文本分类性能的热门研究方向。尽管基于启发式思维链（CoT）的方法众多，但它们往往复杂且效率不高。本文中，我们重新审视了基于LLM的文本分类方法，并提出了一种名为LLMEmbed的简洁高效的迁移学习策略。我们首先探讨了如何利用轻量级LLMs在不同网络深度提取和融合文本嵌入，以增强其鲁棒性和区分能力，进而将这些嵌入用于分类器的训练。实验结果表明，LLMEmbed在公开数据集上表现出色，与依赖于更大模型（如GPT-3）和复杂提示策略的方法相比，它不仅性能强劲，而且训练开销更低。我们的方法在无需微调的情况下，仅用4%的模型参数、1.8%的电力消耗和1.5%的运行时间，便在公开基准上取得了优异的准确率。相关代码已公开发布于：https://github.com/ChunLiu-cs/LLMEmbed-ACL2024。

> With the booming of Large Language Models (LLMs), prompt-learning has become a promising method mainly researched in various research areas. Recently, many attempts based on prompt-learning have been made to improve the performance of text classification. However, most of these methods are based on heuristic Chain-of-Thought (CoT), and tend to be more complex but less efficient. In this paper, we rethink the LLM-based text classification methodology, propose a simple and effective transfer learning strategy, namely LLMEmbed, to address this classical but challenging task. To illustrate, we first study how to properly extract and fuse the text embeddings via various lightweight LLMs at different network depths to improve their robustness and discrimination, then adapt such embeddings to train the classifier. We perform extensive experiments on publicly available datasets, and the results show that LLMEmbed achieves strong performance while enjoys low training overhead using lightweight LLM backbones compared to recent methods based on larger LLMs, i.e. GPT-3, and sophisticated prompt-based strategies. Our LLMEmbed achieves adequate accuracy on publicly available benchmarks without any fine-tuning while merely use 4% model parameters, 1.8% electricity consumption and 1.5% runtime compared to its counterparts. Code is available at: https://github.com/ChunLiu-cs/LLMEmbed-ACL2024.

![LLMEmbed：探索轻量级大型语言模型在文本分类中的核心价值](../../../paper_images/2406.03725/x1.png)

![LLMEmbed：探索轻量级大型语言模型在文本分类中的核心价值](../../../paper_images/2406.03725/x2.png)

![LLMEmbed：探索轻量级大型语言模型在文本分类中的核心价值](../../../paper_images/2406.03725/x3.png)

[Arxiv](https://arxiv.org/abs/2406.03725)