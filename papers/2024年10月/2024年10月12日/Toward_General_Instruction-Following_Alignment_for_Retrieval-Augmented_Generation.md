# 迈向通用指令遵循与检索增强生成的对齐

发布时间：2024年10月12日

`RAG` `人工智能` `问答系统`

> Toward General Instruction-Following Alignment for Retrieval-Augmented Generation

# 摘要

> 遵循自然指令对 RAG 系统的有效应用至关重要。尽管 LLM 有所进步，但在 RAG 领域内评估和改进指令遵循的研究仍有限。为此，我们提出了 VIF-RAG，首个自动化、可扩展且可验证的合成管道，用于 RAG 系统中的指令遵循对齐。我们首先手动创建了一组原子指令 (<100)，并开发组合规则合成和验证复杂指令。接着，我们使用监督模型重写指令，并通过 Python 执行器自动验证指令质量。最后，我们将这些指令与 RAG 和通用数据样本集成，通过自动化过程扩展到高质量的 VIF-RAG-QA 数据集 (>100k)。为缩小 RAG 系统指令遵循自动评估的差距，我们引入了 FollowRAG 基准，包含约 3K 测试样本，涵盖 22 类通用指令约束和四个知识密集型 QA 数据集。由于其稳健的管道设计，FollowRAG 可无缝集成到不同 RAG 基准中。使用 FollowRAG 和八个广泛使用的 IF 和基础能力基准，我们展示了 VIF-RAG 显著提升了 LLM 在广泛通用指令约束下的性能，同时在 RAG 场景中有效利用其能力。进一步分析为实现 RAG 系统中的 IF 对齐提供了实用见解。我们的代码和数据集已在 https://FollowRAG.github.io 发布。

> Following natural instructions is crucial for the effective application of Retrieval-Augmented Generation (RAG) systems. Despite recent advancements in Large Language Models (LLMs), research on assessing and improving instruction-following (IF) alignment within the RAG domain remains limited. To address this issue, we propose VIF-RAG, the first automated, scalable, and verifiable synthetic pipeline for instruction-following alignment in RAG systems. We start by manually crafting a minimal set of atomic instructions (<100) and developing combination rules to synthesize and verify complex instructions for a seed set. We then use supervised models for instruction rewriting while simultaneously generating code to automate the verification of instruction quality via a Python executor. Finally, we integrate these instructions with extensive RAG and general data samples, scaling up to a high-quality VIF-RAG-QA dataset (>100k) through automated processes. To further bridge the gap in instruction-following auto-evaluation for RAG systems, we introduce FollowRAG Benchmark, which includes approximately 3K test samples, covering 22 categories of general instruction constraints and four knowledge-intensive QA datasets. Due to its robust pipeline design, FollowRAG can seamlessly integrate with different RAG benchmarks. Using FollowRAG and eight widely-used IF and foundational abilities benchmarks for LLMs, we demonstrate that VIF-RAG markedly enhances LLM performance across a broad range of general instruction constraints while effectively leveraging its capabilities in RAG scenarios. Further analysis offers practical insights for achieving IF alignment in RAG systems. Our code and datasets are released at https://FollowRAG.github.io.

[Arxiv](https://arxiv.org/abs/2410.09584)