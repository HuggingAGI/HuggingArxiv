# AlignScore：使用统一对齐函数评估事实一致性

发布时间：2023年05月26日

`LLM应用` `文本生成` `自动评估`

> AlignScore: Evaluating Factual Consistency with a Unified Alignment Function

# 摘要

> 摘要：许多文本生成应用程序要求生成的文本在事实上与输入信息一致。事实一致性的自动评估具有挑战性。以前的工作开发了各种指标，这些指标通常依赖于特定功能，例如在有限数据上训练的自然语言推理（NLI）或问答（QA）。因此，这些指标很难评估在不同任务的不同输入/输出（例如句子、文档）中出现的各种事实不一致（例如矛盾、幻觉）。在本文中，我们提出了 AlignScore，这是一种适用于上述各种事实不一致情况的新的整体指标。AlignScore 基于任意两个文本片段之间的信息对齐的一般函数。至关重要的是，我们通过整合大量不同的数据源开发了对齐函数的统一训练框架，从而从 7 个成熟的任务（NLI、QA、释义、事实验证、信息检索、语义相似性和总结）中获得了 470 万个训练示例。我们在包括 22 个评估数据集的大规模基准上进行了广泛的实验，其中 19 个数据集在对齐训练中从未见过。AlignScore 相对于之前的各种指标有了显著的改进。此外，AlignScore（3.55 亿个参数）与基于 ChatGPT 和 GPT-4 的指标相匹配，甚至表现更优，而后者的规模要大几个数量级。

> 
Abstract:Many text generation applications require the generated text to be factually consistent with input information. Automatic evaluation of factual consistency is challenging. Previous work has developed various metrics that often depend on specific functions, such as natural language inference (NLI) or question answering (QA), trained on limited data. Those metrics thus can hardly assess diverse factual inconsistencies (e.g., contradictions, hallucinations) that occur in varying inputs/outputs (e.g., sentences, documents) from different tasks. In this paper, we propose AlignScore, a new holistic metric that applies to a variety of factual inconsistency scenarios as above. AlignScore is based on a general function of information alignment between two arbitrary text pieces. Crucially, we develop a unified training framework of the alignment function by integrating a large diversity of data sources, resulting in 4.7M training examples from 7 well-established tasks (NLI, QA, paraphrasing, fact verification, information retrieval, semantic similarity, and summarization). We conduct extensive experiments on large-scale benchmarks including 22 evaluation datasets, where 19 of the datasets were never seen in the alignment training. AlignScore achieves substantial improvement over a wide range of previous metrics. Moreover, AlignScore (355M parameters) matches or even outperforms metrics based on ChatGPT and GPT-4 that are orders of magnitude larger.
    

[Arxiv](https://arxiv.org/pdf/2305.16739)