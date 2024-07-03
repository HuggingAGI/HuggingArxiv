# 探究 LLMs 在语义感知过程挖掘任务中的表现

发布时间：2024年07月02日

`LLM应用` `流程挖掘` `人工智能`

> Evaluating the Ability of LLMs to Solve Semantics-Aware Process Mining Tasks

# 摘要

> 流程挖掘领域近期发现，大型语言模型（LLMs）在处理多种流程挖掘任务上展现出巨大潜力。初期研究显示，LLMs不仅能辅助流程分析，甚至在一定程度上能推理流程运作机制。这一特性暗示LLMs可用于那些需要理解流程行为的任务，如（语义）异常检测和下一活动预测，这些任务均需考虑活动含义及其关联。本文探讨了LLMs在处理这类需语义理解的流程挖掘任务上的能力。不同于多数研究仅测试LLMs的即用性能，我们更系统地评估了LLMs在流程挖掘中的应用，包括通过上下文学习和监督微调获取流程挖掘知识的能力。我们定义了三个依赖流程语义理解的挖掘任务，并为其提供了详尽的基准数据集。实验结果显示：（1）LLMs在未微调情况下难以应对复杂流程挖掘任务，即便提供少量示例亦然；（2）然而，经过针对性微调后，LLMs表现出色，持续优于小型编码器基语言模型。

> The process mining community has recently recognized the potential of large language models (LLMs) for tackling various process mining tasks. Initial studies report the capability of LLMs to support process analysis and even, to some extent, that they are able to reason about how processes work. This latter property suggests that LLMs could also be used to tackle process mining tasks that benefit from an understanding of process behavior. Examples of such tasks include (semantic) anomaly detection and next activity prediction, which both involve considerations of the meaning of activities and their inter-relations. In this paper, we investigate the capabilities of LLMs to tackle such semantics-aware process mining tasks. Furthermore, whereas most works on the intersection of LLMs and process mining only focus on testing these models out of the box, we provide a more principled investigation of the utility of LLMs for process mining, including their ability to obtain process mining knowledge post-hoc by means of in-context learning and supervised fine-tuning. Concretely, we define three process mining tasks that benefit from an understanding of process semantics and provide extensive benchmarking datasets for each of them. Our evaluation experiments reveal that (1) LLMs fail to solve challenging process mining tasks out of the box and when provided only a handful of in-context examples, (2) but they yield strong performance when fine-tuned for these tasks, consistently surpassing smaller, encoder-based language models.

[Arxiv](https://arxiv.org/abs/2407.02310)