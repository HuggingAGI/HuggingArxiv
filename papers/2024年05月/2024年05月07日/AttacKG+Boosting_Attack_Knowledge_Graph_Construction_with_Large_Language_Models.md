# AttacKG+：借助大型语言模型，强化攻击知识图谱的构建能力

发布时间：2024年05月07日

`Agent

这篇论文提出了一种基于大型语言模型（LLMs）的全自动框架AttacKG+，用于将网络威胁情报报告转化为结构化的攻击知识图谱。这个框架可以被视为一个智能代理（Agent），因为它能够自动处理输入数据（网络威胁情报报告），并生成有用的输出（结构化的攻击知识图谱）。此外，该框架通过LLMs赋能的指令提示和情境学习，实现了重写、解析、标识和摘要四个模块的连续操作，这进一步强调了其作为智能代理的特性，因为它能够执行一系列复杂的任务来完成其目标。因此，这篇论文属于Agent分类。` `网络安全` `威胁情报分析`

> AttacKG+:Boosting Attack Knowledge Graph Construction with Large Language Models

# 摘要

> 我们提出了一种基于大型语言模型（LLMs）的全自动框架AttacKG+，用于将网络威胁情报报告转化为结构化的攻击知识图谱，以描绘网络攻击的演变过程。该框架通过LLMs赋能的指令提示和情境学习，实现了重写、解析、标识和摘要四个模块的连续操作。我们不仅升级了现有的攻击知识图谱模式，还提出了一个更为全面的版本，将网络攻击视为一个时间序列事件，每个时间点都详细记录了攻击的行为、MITRE TTP标签和状态摘要。实验证明，我们的方法不仅满足了威胁分析的信息需求，而且能够准确提取攻击信息，对下游安全实践，如攻击重建，产生了直接的积极影响。所有相关代码和数据集将在论文被接受后公开。

> Attack knowledge graph construction seeks to convert textual cyber threat intelligence (CTI) reports into structured representations, portraying the evolutionary traces of cyber attacks. Even though previous research has proposed various methods to construct attack knowledge graphs, they generally suffer from limited generalization capability to diverse knowledge types as well as requirement of expertise in model design and tuning. Addressing these limitations, we seek to utilize Large Language Models (LLMs), which have achieved enormous success in a broad range of tasks given exceptional capabilities in both language understanding and zero-shot task fulfillment. Thus, we propose a fully automatic LLM-based framework to construct attack knowledge graphs named: AttacKG+. Our framework consists of four consecutive modules: rewriter, parser, identifier, and summarizer, each of which is implemented by instruction prompting and in-context learning empowered by LLMs. Furthermore, we upgrade the existing attack knowledge schema and propose a comprehensive version. We represent a cyber attack as a temporally unfolding event, each temporal step of which encapsulates three layers of representation, including behavior graph, MITRE TTP labels, and state summary. Extensive evaluation demonstrates that: 1) our formulation seamlessly satisfies the information needs in threat event analysis, 2) our construction framework is effective in faithfully and accurately extracting the information defined by AttacKG+, and 3) our attack graph directly benefits downstream security practices such as attack reconstruction. All the code and datasets will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2405.04753)