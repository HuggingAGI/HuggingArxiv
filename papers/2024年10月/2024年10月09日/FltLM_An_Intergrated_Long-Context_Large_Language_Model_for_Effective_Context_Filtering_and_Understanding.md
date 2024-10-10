# FltLM：一款集成长上下文的大型语言模型，专为高效上下文过滤与理解而设计。

发布时间：2024年10月09日

`LLM应用` `问答系统`

> FltLM: An Intergrated Long-Context Large Language Model for Effective Context Filtering and Understanding

# 摘要

> 长上下文大型语言模型 (LLM) 的发展极大地推动了自然语言处理，但仍面临两大难题：中间信息丢失和注意力分散。为此，我们推出了上下文过滤语言模型 (FltLM)，通过创新的软掩码机制，动态过滤无关内容，聚焦关键信息，提升多文档问答 (QA) 能力。FltLM 不仅解决了上述难题，还简化了模型运行流程。实验证明，FltLM 在复杂 QA 任务中表现卓越，为长上下文自然语言理解提供了更精准可靠的解决方案。

> The development of Long-Context Large Language Models (LLMs) has markedly advanced natural language processing by facilitating the process of textual data across long documents and multiple corpora. However, Long-Context LLMs still face two critical challenges: The lost in the middle phenomenon, where crucial middle-context information is likely to be missed, and the distraction issue that the models lose focus due to overly extended contexts. To address these challenges, we propose the Context Filtering Language Model (FltLM), a novel integrated Long-Context LLM which enhances the ability of the model on multi-document question-answering (QA) tasks. Specifically, FltLM innovatively incorporates a context filter with a soft mask mechanism, identifying and dynamically excluding irrelevant content to concentrate on pertinent information for better comprehension and reasoning. Our approach not only mitigates these two challenges, but also enables the model to operate conveniently in a single forward pass. Experimental results demonstrate that FltLM significantly outperforms supervised fine-tuning and retrieval-based methods in complex QA scenarios, suggesting a promising solution for more accurate and reliable long-context natural language understanding applications.

[Arxiv](https://arxiv.org/abs/2410.06886)