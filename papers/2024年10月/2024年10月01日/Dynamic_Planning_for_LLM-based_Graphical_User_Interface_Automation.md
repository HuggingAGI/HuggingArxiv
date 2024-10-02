# LLM 图形用户界面自动化的动态规划

发布时间：2024年10月01日

`Agent` `智能手机` `人工智能`

> Dynamic Planning for LLM-based Graphical User Interface Automation

# 摘要

> 大型语言模型 (LLM) 的兴起，推动了基于 LLM 的自主代理在智能手机图形用户界面 (GUI) 中的应用研究。这些代理在接收到任务目标后，会在 GUI 环境中模拟人类行为直至任务完成。然而，如何制定有效计划来指导 GUI 任务中的行为预测，仍是一个关键挑战。尽管计划已被证明是将复杂任务分解为一系列步骤的有效方法，但考虑到环境 GUI 在行为执行后的动态变化，动态调整计划显得尤为重要。我们发现，广泛使用的 ReAct 方法因历史对话过长而失效。为此，我们提出了“思想动态规划”(D-PoT) 方法，该方法能根据环境反馈和执行历史动态调整规划。实验结果显示，D-PoT 在准确性上显著优于 GPT-4V 基线，提升了 12.7%。分析表明，动态规划不仅适用于不同 LLM，还能有效减少幻觉并适应新任务。代码已公开，详见 https://github.com/sqzhang-lazy/D-PoT。

> The advent of large language models (LLMs) has spurred considerable interest in advancing autonomous LLMs-based agents, particularly in intriguing applications within smartphone graphical user interfaces (GUIs). When presented with a task goal, these agents typically emulate human actions within a GUI environment until the task is completed. However, a key challenge lies in devising effective plans to guide action prediction in GUI tasks, though planning have been widely recognized as effective for decomposing complex tasks into a series of steps. Specifically, given the dynamic nature of environmental GUIs following action execution, it is crucial to dynamically adapt plans based on environmental feedback and action history.We show that the widely-used ReAct approach fails due to the excessively long historical dialogues. To address this challenge, we propose a novel approach called Dynamic Planning of Thoughts (D-PoT) for LLM-based GUI agents.D-PoT involves the dynamic adjustment of planning based on the environmental feedback and execution history. Experimental results reveal that the proposed D-PoT significantly surpassed the strong GPT-4V baseline by +12.7% (34.66% $\rightarrow$ 47.36%) in accuracy. The analysis highlights the generality of dynamic planning in different backbone LLMs, as well as the benefits in mitigating hallucinations and adapting to unseen tasks. Code is available at https://github.com/sqzhang-lazy/D-PoT.

[Arxiv](https://arxiv.org/abs/2410.00467)