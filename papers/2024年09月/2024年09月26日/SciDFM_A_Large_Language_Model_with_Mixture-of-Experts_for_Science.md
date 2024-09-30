# SciDFM：专为科学领域设计的大语言模型，融合了专家混合技术。

发布时间：2024年09月26日

`LLM应用` `科学研究` `人工智能`

> SciDFM: A Large Language Model with Mixture-of-Experts for Science

# 摘要

> 近期，利用大型语言模型 (LLM) 助力科学发现的热情高涨。然而，多数 LLM 仅限于一般科学知识，缺乏如化学分子和氨基酸序列等特定领域知识。为此，我们推出了 SciDFM，一个从零开始训练的混合专家 LLM，具备大学水平的科学推理能力，并能理解分子和氨基酸序列。我们构建了一个包含多学科科学文献和特定领域数据库数据的大规模训练语料库。通过在大量指令数据上微调预训练模型，我们显著提升了其在下游基准测试中的表现。实验结果显示，SciDFM 在一般科学基准测试（如 SciEval 和 SciQ）中表现出色，并在同类模型中在特定领域基准测试中达到领先水平。我们还分析了专家层的表现，发现专家选择的效果随学科数据的不同而变化。为促进更广泛的研究应用，我们在 https://huggingface.co/OpenDFM/SciDFM-MoE-A5.6B-v1.0 上开源了 SciDFM。

> Recently, there has been a significant upsurge of interest in leveraging large language models (LLMs) to assist scientific discovery. However, most LLMs only focus on general science, while they lack domain-specific knowledge, such as chemical molecules and amino acid sequences. To bridge these gaps, we introduce SciDFM, a mixture-of-experts LLM, which is trained from scratch and is able to conduct college-level scientific reasoning and understand molecules and amino acid sequences. We collect a large-scale training corpus containing numerous scientific papers and books from different disciplines as well as data from domain-specific databases. We further fine-tune the pre-trained model on lots of instruction data to improve performances on downstream benchmarks. From experiment results, we show that SciDFM achieves strong performance on general scientific benchmarks such as SciEval and SciQ, and it reaches a SOTA performance on domain-specific benchmarks among models of similar size. We further analyze the expert layers and show that the results of expert selection vary with data from different disciplines. To benefit the broader research community, we open-source SciDFM at https://huggingface.co/OpenDFM/SciDFM-MoE-A5.6B-v1.0.

[Arxiv](https://arxiv.org/abs/2409.18412)