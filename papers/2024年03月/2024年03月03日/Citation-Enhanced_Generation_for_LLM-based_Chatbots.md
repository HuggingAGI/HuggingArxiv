# [为基于大型语言模型（LLM）的聊天机器人引入引文增强生成技术，旨在提升其对话内容的准确性和可信度。](https://arxiv.org/abs/2402.16063)

发布时间：2024年03月03日

`LLM应用`

> Citation-Enhanced Generation for LLM-based Chatbots

> LLMs在各类场景中展现出非凡的通用智能，特别是在构建聊天机器人方面。不过，基于LLM的聊天机器人常会生成含有臆想内容的回复，大大制约了其实用性。尽管已有诸如增强检索生成和利用人类反馈的强化学习等手段试图减少虚构现象，但多数方法需额外训练和数据标注。本文创新地提出了“后期引用增强生成”（CEG）方案，并融入检索论证机制。区别于先前着重预防生成阶段出现虚构的研究，我们的方法采用事后修正策略，通过检索与生成内容相关的支撑文档，并运用基于自然语言推理的引用生成模块。当生成内容的陈述缺乏依据时，模型将持续重制回复直至所有陈述均有出处支撑。值得注意的是，该方法是一款无需训练、即插即用的插件，能灵活应用于各种LLMs。实验证明，在涉及虚构内容检测及回复重构的多个数据集上，我们的框架在三项基准测试中均超越了当前最先进方法。我们承诺将公开源代码和数据集。

> Large language models (LLMs) exhibit powerful general intelligence across diverse scenarios, including their integration into chatbots. However, a vital challenge of LLM-based chatbots is that they may produce hallucinated content in responses, which significantly limits their applicability. Various efforts have been made to alleviate hallucination, such as retrieval augmented generation and reinforcement learning with human feedback, but most of them require additional training and data annotation. In this paper, we propose a novel post-hoc Citation-Enhanced Generation (CEG) approach combined with retrieval argumentation. Unlike previous studies that focus on preventing hallucinations during generation, our method addresses this issue in a post-hoc way. It incorporates a retrieval module to search for supporting documents relevant to the generated content, and employs a natural language inference-based citation generation module. Once the statements in the generated content lack of reference, our model can regenerate responses until all statements are supported by citations. Note that our method is a training-free plug-and-play plugin that is capable of various LLMs. Experiments on various hallucination-related datasets show our framework outperforms state-of-the-art methods in both hallucination detection and response regeneration on three benchmarks. Our codes and dataset will be publicly available.

[Arxiv](https://arxiv.org/abs/2402.16063)