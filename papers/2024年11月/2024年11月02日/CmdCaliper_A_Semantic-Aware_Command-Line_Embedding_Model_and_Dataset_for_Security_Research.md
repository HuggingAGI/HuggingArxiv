# CmdCaliper：一个用于安全研究的具备语义感知的命令行嵌入模型及数据集

发布时间：2024年11月02日

`LLM应用` `网络安全` `数据生成`

> CmdCaliper: A Semantic-Aware Command-Line Embedding Model and Dataset for Security Research

# 摘要

> 这项研究着眼于网络安全中的命令行嵌入，此领域因隐私和法规顾虑而缺乏全面数据集，从而受到阻碍。我们推出了首个类似命令行的数据集，叫做 CyPHER，用于训练和无偏差评估。训练集通过一组大型语言模型（LLMs）生成，涵盖 28,520 个相似的命令行对。我们的测试数据集包含 2,807 个相似的命令行对，均源于真实的命令行数据。
  另外，我们提出了名为 CmdCaliper 的命令行嵌入模型，能够计算与命令行的语义相似度。性能评估显示，最小版本的 CmdCaliper（3000 万参数）在各类任务（如恶意命令行检测和相似命令行检索）中，胜过了参数十倍于它的最先进（SOTA）句子嵌入模型。
  我们的研究探索了在网络安全领域利用 LLMs 进行数据生成的可行性。而且，我们向公众公开了我们提出的命令行数据集、嵌入模型的权重以及所有程序代码。这一进步为未来研究者更高效地开展命令行嵌入工作铺平了道路。

> This research addresses command-line embedding in cybersecurity, a field obstructed by the lack of comprehensive datasets due to privacy and regulation concerns. We propose the first dataset of similar command lines, named CyPHER, for training and unbiased evaluation. The training set is generated using a set of large language models (LLMs) comprising 28,520 similar command-line pairs. Our testing dataset consists of 2,807 similar command-line pairs sourced from authentic command-line data.
  In addition, we propose a command-line embedding model named CmdCaliper, enabling the computation of semantic similarity with command lines. Performance evaluations demonstrate that the smallest version of CmdCaliper (30 million parameters) suppresses state-of-the-art (SOTA) sentence embedding models with ten times more parameters across various tasks (e.g., malicious command-line detection and similar command-line retrieval).
  Our study explores the feasibility of data generation using LLMs in the cybersecurity domain. Furthermore, we release our proposed command-line dataset, embedding models' weights and all program codes to the public. This advancement paves the way for more effective command-line embedding for future researchers.

[Arxiv](https://arxiv.org/abs/2411.01176)