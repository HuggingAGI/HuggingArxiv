# MM-R$^3$: 探讨多模态大型语言模型 (MLLM) 的一致性问题

发布时间：2024年10月07日

`LLM应用` `人工智能` `多模态学习`

> MM-R$^3$: On (In-)Consistency of Multi-modal Large Language Models (MLLMs)

# 摘要

> 随着 LLM 和多模态 LLM 的兴起，研究者们纷纷探索这些模型在各类任务中的表现。大多数研究通过任务准确性来评估最先进的 MLLM 模型，例如视觉问答和定位。然而，我们的研究聚焦于一个互补的维度——一致性，即模型对语义相似查询产生相似或相同响应的能力。一致性是 MLLM 鲁棒性和信任的基础。人类在响应中表现出高度一致性，AI 系统也应如此。为此，我们提出了 MM-R$^3$ 基准，通过问题重述、图像重塑和上下文推理三项任务，评估 SoTA MLLM 的一致性和准确性。我们发现，一致性与准确性并不总是一致，高准确性模型未必更一致。为此，我们设计了一个适配器模块，通过训练减少不一致性。实验表明，该策略在 BLIP-2 和 LLaVa 1.5M 上分别实现了 5.7% 和 12.5% 的一致性提升。

> With the advent of Large Language Models (LLMs) and Multimodal (Visio-lingual) LLMs, a flurry of research has emerged, analyzing the performance of such models across a diverse array of tasks. While most studies focus on evaluating the capabilities of state-of-the-art (SoTA) MLLM models through task accuracy (e.g., Visual Question Answering, grounding) across various datasets, our work explores the related but complementary aspect of consistency - the ability of an MLLM model to produce semantically similar or identical responses to semantically similar queries. We note that consistency is a fundamental prerequisite (necessary but not sufficient condition) for robustness and trust in MLLMs. Humans, in particular, are known to be highly consistent (even if not always accurate) in their responses, and consistency is inherently expected from AI systems. Armed with this perspective, we propose the MM-R$^3$ benchmark, which analyses the performance in terms of consistency and accuracy in SoTA MLLMs with three tasks: Question Rephrasing, Image Restyling, and Context Reasoning. Our analysis reveals that consistency does not always align with accuracy, indicating that models with higher accuracy are not necessarily more consistent, and vice versa. Furthermore, we propose a simple yet effective mitigation strategy in the form of an adapter module trained to minimize inconsistency across prompts. With our proposed strategy, we are able to achieve absolute improvements of 5.7% and 12.5%, on average on widely used MLLMs such as BLIP-2 and LLaVa 1.5M in terms of consistency over their existing counterparts.

[Arxiv](https://arxiv.org/abs/2410.04778)