# EcoAct：经济主体决定何时注册何种行动

发布时间：2024年11月03日

`Agent` `语言模型`

> EcoAct: Economic Agent Determines When to Register What Action

# 摘要

> 最近的进展使大型语言模型（LLMs）能够作为可以使用外部工具执行动作的代理。这需要注册，即在采取行动之前将工具信息整合到 LLM 上下文中。当前的方法不加区分地将所有候选工具纳入代理的上下文，并在多个推理步骤中保留它们。这个过程对于 LLM 代理来说仍然是不透明的，并且没有整合到他们的推理程序中，由于不相关工具增加了上下文长度而导致效率低下。为了解决这个问题，我们引入了 EcoAct，一种工具使用算法，允许 LLMs 根据需要有选择地注册工具，优化上下文使用。通过将工具注册过程集成到推理程序中，EcoAct 在多个步骤推理任务中降低了超过 50％的计算成本，同时保持性能，这通过广泛的实验得到证明。此外，它可以插入到任何推理管道中，只需对提示进行少量修改，使其适用于现在和未来的 LLM 代理。

> Recent advancements have enabled Large Language Models (LLMs) to function as agents that can perform actions using external tools. This requires registering, i.e., integrating tool information into the LLM context prior to taking actions. Current methods indiscriminately incorporate all candidate tools into the agent's context and retain them across multiple reasoning steps. This process remains opaque to LLM agents and is not integrated into their reasoning procedures, leading to inefficiencies due to increased context length from irrelevant tools. To address this, we introduce EcoAct, a tool using algorithm that allows LLMs to selectively register tools as needed, optimizing context use. By integrating the tool registration process into the reasoning procedure, EcoAct reduces computational costs by over 50% in multiple steps reasoning tasks while maintaining performance, as demonstrated through extensive experiments. Moreover, it can be plugged into any reasoning pipeline with only minor modifications to the prompt, making it applicable to LLM agents now and future.

[Arxiv](https://arxiv.org/abs/2411.01643)