# 本研究致力于考察LLM（大型语言模型）在对话场景下的非常长期记忆能力。

发布时间：2024年02月27日

`Agent`

> Evaluating Very Long-Term Conversational Memory of LLM Agents

# 摘要

> 当前针对长时段开放对话的研究焦点是评估模型在不超过五轮会话情境下的回复质量。然而，即便长时序LLMs及RAG技术日新月异，它们在极端长对话场景下的效能却尚未被深入探究。为此，我们创新性地设计了一套结合机器与人类协同的流水线式方法，运用LLM架构的智能代理，并将对话根植于个性特征与时间事件图中，从而生成高质量且极为持久的对话。在此基础上，我们赋予每个代理分享和反应图片的能力。这些生成的对话经历严格的人工审核与编辑，确保了对话在长距离上的连贯一致以及与事件图紧密贴合。据此流程，我们成功构建出LoCoMo数据集，其中包括每段平均长达300回合、约9K个词汇量、跨越多达35个会话阶段的超长对话记录。借助LoCoMo数据集，我们搭建了一个综合评测基准，囊括问题解答、事件摘要及多模态对话生成等多项任务，旨在检验模型对长期记忆的掌握程度。实验证明，LLMs在理解冗长对话及其内在的长期时间和因果动态方面面临困难。尽管应用长时序LLMs或RAG等策略有助于性能提升，但这些模型的表现相较于人类仍存在着显著差距。

> Existing works on long-term open-domain dialogues focus on evaluating model responses within contexts spanning no more than five chat sessions. Despite advancements in long-context large language models (LLMs) and retrieval augmented generation (RAG) techniques, their efficacy in very long-term dialogues remains unexplored. To address this research gap, we introduce a machine-human pipeline to generate high-quality, very long-term dialogues by leveraging LLM-based agent architectures and grounding their dialogues on personas and temporal event graphs. Moreover, we equip each agent with the capability of sharing and reacting to images. The generated conversations are verified and edited by human annotators for long-range consistency and grounding to the event graphs. Using this pipeline, we collect LoCoMo, a dataset of very long-term conversations, each encompassing 300 turns and 9K tokens on avg., over up to 35 sessions. Based on LoCoMo, we present a comprehensive evaluation benchmark to measure long-term memory in models, encompassing question answering, event summarization, and multi-modal dialogue generation tasks. Our experimental results indicate that LLMs exhibit challenges in understanding lengthy conversations and comprehending long-range temporal and causal dynamics within dialogues. Employing strategies like long-context LLMs or RAG can offer improvements but these models still substantially lag behind human performance.

[Arxiv](https://arxiv.org/abs/2402.17753)