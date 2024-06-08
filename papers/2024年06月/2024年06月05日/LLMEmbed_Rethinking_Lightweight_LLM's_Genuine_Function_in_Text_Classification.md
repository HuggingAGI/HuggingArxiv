# LLMEmbed：探索轻量级LLM在文本分类中的核心价值

发布时间：2024年06月05日

`LLM应用

这篇论文介绍了一种新的迁移学习策略——LLMEmbed，它通过使用轻量级的大型语言模型（LLMs）在不同网络深度提取和融合文本嵌入，以简化文本分类任务。这种方法旨在提高效率并减少训练成本，与依赖大型模型和复杂提示策略的方法相比，表现出更好的性能和更低的资源消耗。因此，这篇论文属于LLM应用类别，因为它专注于开发和应用LLMs于特定的实际问题——文本分类。` `文本分类` `迁移学习`

> LLMEmbed: Rethinking Lightweight LLM's Genuine Function in Text Classification

# 摘要

> 大型语言模型（LLMs）的兴起使得提示学习成为研究热点，尤其在文本分类领域。尽管基于提示的改进方法层出不穷，但多数仍依赖于复杂的启发式思维链（CoT），效率并不理想。本文提出了一种新颖的迁移学习策略——LLMEmbed，旨在简化这一挑战性任务。我们通过轻量级LLMs在不同网络深度提取和融合文本嵌入，增强其鲁棒性与区分力，进而训练分类器。实验结果表明，LLMEmbed在公开数据集上表现出色，不仅性能强劲，且训练成本远低于依赖大型模型（如GPT-3）和复杂提示策略的方法。无需微调，LLMEmbed仅用4%的模型参数、1.8%的电力和1.5%的时间，便在公开基准上取得了优异成绩。代码已公开：https://github.com/ChunLiu-cs/LLMEmbed-ACL2024。

> With the booming of Large Language Models (LLMs), prompt-learning has become a promising method mainly researched in various research areas. Recently, many attempts based on prompt-learning have been made to improve the performance of text classification. However, most of these methods are based on heuristic Chain-of-Thought (CoT), and tend to be more complex but less efficient. In this paper, we rethink the LLM-based text classification methodology, propose a simple and effective transfer learning strategy, namely LLMEmbed, to address this classical but challenging task. To illustrate, we first study how to properly extract and fuse the text embeddings via various lightweight LLMs at different network depths to improve their robustness and discrimination, then adapt such embeddings to train the classifier. We perform extensive experiments on publicly available datasets, and the results show that LLMEmbed achieves strong performance while enjoys low training overhead using lightweight LLM backbones compared to recent methods based on larger LLMs, i.e. GPT-3, and sophisticated prompt-based strategies. Our LLMEmbed achieves adequate accuracy on publicly available benchmarks without any fine-tuning while merely use 4% model parameters, 1.8% electricity consumption and 1.5% runtime compared to its counterparts. Code is available at: https://github.com/ChunLiu-cs/LLMEmbed-ACL2024.

![LLMEmbed：探索轻量级LLM在文本分类中的核心价值](../../../paper_images/2406.03725/x1.png)

![LLMEmbed：探索轻量级LLM在文本分类中的核心价值](../../../paper_images/2406.03725/x2.png)

![LLMEmbed：探索轻量级LLM在文本分类中的核心价值](../../../paper_images/2406.03725/x3.png)

[Arxiv](https://arxiv.org/abs/2406.03725)