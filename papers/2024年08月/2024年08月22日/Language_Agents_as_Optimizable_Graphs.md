# 语言代理：图形优化的艺术

发布时间：2024年08月22日

`分类：Agent

这篇论文的摘要描述了一种将大型语言模型（LLM）驱动的代理比作计算图的方法，并通过自动图优化器来提升代理的性能。这涉及到节点级别的LLM提示优化和调整图的连接性以提升代理协作。这些内容与Agent领域的研究相关，因为它们涉及到代理的设计、优化和协作。` `人工智能`

> Language Agents as Optimizable Graphs

# 摘要

> 为提升基于大型语言模型（LLM）的问题解决器性能，已提出众多由人工设计的提示工程技术，催生了多样化的代码库。我们通过将LLM驱动的代理比作计算图来整合这些方法。在这些图中，节点负责处理多模态数据或与LLM交互，而边则描绘了操作间的信息流动。这些图可以递归地合并成更复杂的复合图，形成代理间协作的层级结构。我们创新的自动图优化器通过（1）优化节点级别的LLM提示（节点优化）和（2）调整图的连接性以提升代理协作（边优化）。实验证明，我们的框架能够有效地开发、整合并自动提升各类LLM代理的性能。相关代码已在 https://github.com/metauto-ai/gptswarm 上发布。

> Various human-designed prompt engineering techniques have been proposed to improve problem solvers based on Large Language Models (LLMs), yielding many disparate code bases. We unify these approaches by describing LLM-based agents as computational graphs. The nodes implement functions to process multimodal data or query LLMs, and the edges describe the information flow between operations. Graphs can be recursively combined into larger composite graphs representing hierarchies of inter-agent collaboration (where edges connect operations of different agents). Our novel automatic graph optimizers (1) refine node-level LLM prompts (node optimization) and (2) improve agent orchestration by changing graph connectivity (edge optimization). Experiments demonstrate that our framework can be used to efficiently develop, integrate, and automatically improve various LLM agents. The code can be found at https://github.com/metauto-ai/gptswarm.

[Arxiv](https://arxiv.org/abs/2402.16823)