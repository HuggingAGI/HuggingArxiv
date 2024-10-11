# 火星：开放世界中的情境归纳推理

发布时间：2024年10月10日

`Agent` `人工智能` `游戏开发`

> Mars: Situated Inductive Reasoning in an Open-World Environment

# 摘要

> 大型语言模型 (LLM) 在知识密集型任务中表现出色，但大多依赖预存储知识。本文设计了 Mars，一个专为情境归纳推理打造的交互环境，通过修改地形、生存设置和任务依赖性，引入反常识游戏机制。在 Mars 中，代理需与环境互动，推导规则并执行决策任务。实验显示，基于 RL 和 LLM 的方法在此基准上均表现不佳。我们探索了“从反思中归纳”，指导代理从历史轨迹中进行推理，结果显示其重要性。通过 Mars，我们旨在推动情境归纳推理的发展，为下一代适应性强、情境敏感的 AI 系统奠定基础。

> Large Language Models (LLMs) trained on massive corpora have shown remarkable success in knowledge-intensive tasks. Yet, most of them rely on pre-stored knowledge. Inducing new general knowledge from a specific environment and performing reasoning with the acquired knowledge -- \textit{situated inductive reasoning}, is crucial and challenging for machine intelligence. In this paper, we design Mars, an interactive environment devised for situated inductive reasoning. It introduces counter-commonsense game mechanisms by modifying terrain, survival setting and task dependency while adhering to certain principles. In Mars, agents need to actively interact with their surroundings, derive useful rules and perform decision-making tasks in specific contexts. We conduct experiments on various RL-based and LLM-based methods, finding that they all struggle on this challenging situated inductive reasoning benchmark. Furthermore, we explore \textit{Induction from Reflection}, where we instruct agents to perform inductive reasoning from history trajectory. The superior performance underscores the importance of inductive reasoning in Mars. Through Mars, we aim to galvanize advancements in situated inductive reasoning and set the stage for developing the next generation of AI systems that can reason in an adaptive and context-sensitive way.

[Arxiv](https://arxiv.org/abs/2410.08126)