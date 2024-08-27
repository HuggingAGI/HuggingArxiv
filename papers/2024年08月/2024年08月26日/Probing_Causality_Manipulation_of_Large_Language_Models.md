# 探索大型语言模型中的因果操控机制

发布时间：2024年08月26日

`LLM理论` `人工智能`

> Probing Causality Manipulation of Large Language Models

# 摘要

> 大型语言模型（LLM）在自然语言处理领域展现出多样能力，包括因果关系问题的处理。然而，由于预训练模型多基于统计关联而非因果分析，LLM 对因果关系的掌握并不直观。为此，本文创新性地提出通过分层快捷方式来探测模型对因果关系的处理，并结合检索增强生成（RAG）与上下文学习（ICL）在特定因果分类任务中进行实验。实验涵盖了GPT-4等主流LLM及特定领域模型，结果显示LLM虽能识别因果相关实体及直接关系，但缺乏对因果的深入认知，仅视其为语句全局语义的一环。

> Large language models (LLMs) have shown various ability on natural language processing, including problems about causality. It is not intuitive for LLMs to command causality, since pretrained models usually work on statistical associations, and do not focus on causes and effects in sentences. So that probing internal manipulation of causality is necessary for LLMs. This paper proposes a novel approach to probe causality manipulation hierarchically, by providing different shortcuts to models and observe behaviors. We exploit retrieval augmented generation (RAG) and in-context learning (ICL) for models on a designed causality classification task. We conduct experiments on mainstream LLMs, including GPT-4 and some smaller and domain-specific models. Our results suggest that LLMs can detect entities related to causality and recognize direct causal relationships. However, LLMs lack specialized cognition for causality, merely treating them as part of the global semantic of the sentence.

[Arxiv](https://arxiv.org/abs/2408.14380)