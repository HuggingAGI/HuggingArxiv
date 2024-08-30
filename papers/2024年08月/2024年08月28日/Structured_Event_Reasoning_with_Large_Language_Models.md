# 大型语言模型中的结构化事件推理

发布时间：2024年08月28日

`LLM应用` `人工智能`

> Structured Event Reasoning with Large Language Models

# 摘要

> 在AI和NLP领域，对现实生活事件的推理是一项关键挑战，具有广泛的应用价值，但在高风险场景中，推理错误可能带来严重后果。大型语言模型（LLMs）虽能处理多样的文本并解答问题，但在复杂事件推理上仍显不足，且因其“黑箱”特性而难以解释。为此，我提出三种结合LLMs与事件结构化表示的方法：一是基于语言的子事件关系表示，通过微调LLMs学习；二是半符号的实体状态表示，通过少量提示预测和利用；三是全符号表示，通过结构化数据训练LLMs预测，并由符号求解器执行。实验表明，这些方法在事件推理任务中不仅超越了端到端LLMs，还提升了可解释性，揭示了LLMs与结构化表示在事件推理及其他领域的协同潜力。

> Reasoning about real-life events is a unifying challenge in AI and NLP that has profound utility in a variety of domains, while fallacy in high-stake applications could be catastrophic. Able to work with diverse text in these domains, large language models (LLMs) have proven capable of answering questions and solving problems. However, I show that end-to-end LLMs still systematically fail to reason about complex events, and they lack interpretability due to their black-box nature. To address these issues, I propose three general approaches to use LLMs in conjunction with a structured representation of events. The first is a language-based representation involving relations of sub-events that can be learned by LLMs via fine-tuning. The second is a semi-symbolic representation involving states of entities that can be predicted and leveraged by LLMs via few-shot prompting. The third is a fully symbolic representation that can be predicted by LLMs trained with structured data and be executed by symbolic solvers. On a suite of event reasoning tasks spanning common-sense inference and planning, I show that each approach greatly outperforms end-to-end LLMs with more interpretability. These results suggest manners of synergy between LLMs and structured representations for event reasoning and beyond.

[Arxiv](https://arxiv.org/abs/2408.16098)