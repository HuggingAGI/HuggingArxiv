# CodeSAM：借助多代码视图图融入自注意力来实现源代码表示学习

发布时间：2024年11月21日

`LLM应用` `软件工程` `机器学习`

> CodeSAM: Source Code Representation Learning by Infusing Self-Attention with Multi-Code-View Graphs

# 摘要

> 机器学习（ML）在软件工程（SE）领域崭露头角，因其能大幅提升各类 SE 应用的性能。这一进步很大程度上得益于可通用的源代码表示的发展，它们能有效抓取代码的语法和语义特点。近些年来，受自然语言处理（NLP）启发的基于预训练的 Transformer 模型在 SE 任务中成绩斐然。然而，源代码蕴含着嵌入在其语法中的结构和语义特性，可从诸如抽象语法树（AST）、数据流图（DFG）和控制流图（CFG）等结构化的代码视图中提取。这些代码视图能够对 NLP 技术形成补充，进一步优化 SE 任务。可惜的是，当下尚无灵活的框架能切实将任意代码视图有效注入现有的基于 Transformer 的模型。故而，在本项工作中，我们提出了 CodeSAM，这是一个新颖的可扩展框架，借由创建自注意力掩码将多个代码视图融入基于 Transformer 的模型。我们运用 CodeSAM 对像 CodeBERT 这样的小型语言模型（SLM）在语义代码搜索、代码克隆检测和程序分类等下游 SE 任务中进行微调。实验结果显示，与 GraphCodeBERT 和 CodeBERT 等 SLM 相较，在微调时运用单个代码视图或代码视图的组合，此技术在上述三个任务中均提升了下游性能。我们坚信，这些结果表明像 CodeSAM 这样的技术有助于打造紧凑且高效的代码 SLM，适用于资源受限的场景。

> Machine Learning (ML) for software engineering (SE) has gained prominence due to its ability to significantly enhance the performance of various SE applications. This progress is largely attributed to the development of generalizable source code representations that effectively capture the syntactic and semantic characteristics of code. In recent years, pre-trained transformer-based models, inspired by natural language processing (NLP), have shown remarkable success in SE tasks. However, source code contains structural and semantic properties embedded within its grammar, which can be extracted from structured code-views like the Abstract Syntax Tree (AST), Data-Flow Graph (DFG), and Control-Flow Graph (CFG). These code-views can complement NLP techniques, further improving SE tasks. Unfortunately, there are no flexible frameworks to infuse arbitrary code-views into existing transformer-based models effectively. Therefore, in this work, we propose CodeSAM, a novel scalable framework to infuse multiple code-views into transformer-based models by creating self-attention masks. We use CodeSAM to fine-tune a small language model (SLM) like CodeBERT on the downstream SE tasks of semantic code search, code clone detection, and program classification. Experimental results show that by using this technique, we improve downstream performance when compared to SLMs like GraphCodeBERT and CodeBERT on all three tasks by utilizing individual code-views or a combination of code-views during fine-tuning. We believe that these results are indicative that techniques like CodeSAM can help create compact yet performant code SLMs that fit in resource constrained settings.

[Arxiv](https://arxiv.org/abs/2411.14611)