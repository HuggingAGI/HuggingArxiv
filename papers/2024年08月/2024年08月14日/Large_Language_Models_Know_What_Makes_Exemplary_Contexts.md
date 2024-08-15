# 大型语言模型深谙何为典范上下文

发布时间：2024年08月14日

`LLM应用` `人工智能` `机器学习`

> Large Language Models Know What Makes Exemplary Contexts

# 摘要

> 随着 LLM 的进步，ICL 已成为一项关键能力，它通过少量示例指导模型执行多样任务，无需大规模参数更新。本文提出的框架让 LLM 能够自主挑选关键上下文示例、排序候选组合，并通过强化学习优化选择与排序。我们设计的参数高效检索头，能在训练后依据模型自身偏好生成优化演示。实验证实了该方法提升 ICL 性能的有效性，并能精准选出任务代表性示例，增强检索多样性。

> In-context learning (ICL) has proven to be a significant capability with the advancement of Large Language models (LLMs). By instructing LLMs using few-shot demonstrative examples, ICL enables them to perform a wide range of tasks without needing to update millions of parameters. This paper presents a unified framework for LLMs that allows them to self-select influential in-context examples to compose their contexts; self-rank candidates with different demonstration compositions; self-optimize the demonstration selection and ordering through reinforcement learning. Specifically, our method designs a parameter-efficient retrieval head that generates the optimized demonstration after training with rewards from LLM's own preference. Experimental results validate the proposed method's effectiveness in enhancing ICL performance. Additionally, our approach effectively identifies and selects the most representative examples for the current task, and includes more diversity in retrieval.

[Arxiv](https://arxiv.org/abs/2408.07505)