# 超越独立同分布：从指令间的交互与依赖出发，优化指令学习

发布时间：2024年09月11日

`LLM理论` `人工智能`

> Beyond IID: Optimizing Instruction Learning from the Perspective of Instruction Interaction and Dependency

# 摘要

> 随着指令数据集的丰富，如何有效选择和整合这些指令以微调 LLM 成为一大挑战。以往研究多侧重于挑选高质量的单个指令，却忽视了不同指令间的交互与依赖，导致选择策略不尽如人意。此外，这些交互模式的本质仍待深入探索，更遑论据此优化指令集。为此，本文系统探讨了指令间的交互与依赖模式，并采用线性规划方法优化指令集，同时借助指令依赖分类法改进 SFT 的学习模式。实验结果显示，在多个 LLM 和广泛基准测试中，性能均超越了强基线。

> With the availability of various instruction datasets, a pivotal challenge is how to effectively select and integrate these instructions to fine-tune large language models (LLMs). Previous research mainly focuses on selecting individual high-quality instructions. However, these works overlooked the joint interactions and dependencies between different categories of instructions, leading to suboptimal selection strategies. Moreover, the nature of these interaction patterns remains largely unexplored, let alone optimize the instruction set with regard to them. To fill these gaps, in this paper, we: (1) systemically investigate interaction and dependency patterns between different categories of instructions, (2) manage to optimize the instruction set concerning the interaction patterns using a linear programming-based method, and optimize the learning schema of SFT using an instruction dependency taxonomy guided curriculum learning. Experimental results across different LLMs demonstrate improved performance over strong baselines on widely adopted benchmarks.

[Arxiv](https://arxiv.org/abs/2409.07045)