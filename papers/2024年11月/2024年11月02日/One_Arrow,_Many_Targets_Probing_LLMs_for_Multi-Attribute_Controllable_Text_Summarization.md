# 一箭多标：探索大型语言模型实现多属性可控的文本摘要

发布时间：2024年11月02日

`LLM应用` `文本摘要`

> One Arrow, Many Targets: Probing LLMs for Multi-Attribute Controllable Text Summarization

# 摘要

> 文本摘要在自然语言处理（NLP）领域是一项成熟的任务。然而，针对用户需求的可控摘要，只是近来才备受关注。虽然有一些工作对文本摘要的可控性进行了探索，但对于多属性可控摘要（MACS）的研究还很有限。本工作借助大型语言模型（LLMs）及各种学习范式，尤其是低秩适配器来研究 MACS 任务，以此填补这一空白。我们通过试验不同的流行适配器微调策略，来评估所得模型在保留与多个可控属性相关的线索和模式方面的成效。另外，我们提出并评估了一种新颖的分层适配器融合技术，用于整合来自两个不同可控属性的学习成果。随后，我们展示了研究发现，探讨了所遇挑战，并为推进 MACS 任务提出了潜在方向。

> Text summarization is a well-established task within the natural language processing (NLP) community. However, the focus on controllable summarization tailored to user requirements is gaining traction only recently. While several efforts explore controllability in text summarization, the investigation of Multi-Attribute Controllable Summarization (MACS) remains limited. This work addresses this gap by examining the MACS task through the lens of large language models (LLMs), using various learning paradigms, particularly low-rank adapters. We experiment with different popular adapter fine-tuning strategies to assess the effectiveness of the resulting models in retaining cues and patterns associated with multiple controllable attributes. Additionally, we propose and evaluate a novel hierarchical adapter fusion technique to integrate learnings from two distinct controllable attributes. Subsquently, we present our findings, discuss the challenges encountered, and suggest potential avenues for advancing the MACS task.

[Arxiv](https://arxiv.org/abs/2411.01213)