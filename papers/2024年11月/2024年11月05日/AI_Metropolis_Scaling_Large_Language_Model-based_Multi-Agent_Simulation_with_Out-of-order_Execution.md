# AI 大都市：通过乱序执行扩展基于大型语言模型的多智能体模拟

发布时间：2024年11月05日

`Agent` `社会科学`

> AI Metropolis: Scaling Large Language Model-based Multi-Agent Simulation with Out-of-order Execution

# 摘要

> 随着更先进的自然语言理解和推理能力，由大型语言模型（LLM）驱动的代理在模拟环境中越来越多地被开发出来，以执行复杂的任务、与其他代理交互，并展现出与社会科学和游戏相关的新兴行为。然而，由于错误依赖关系导致的有限并行性，当前的多代理模拟经常遭受效率低下的困扰，从而导致性能瓶颈。在本文中，我们引入了 AI 大都会，这是一个通过结合乱序执行调度来提高 LLM 代理模拟效率的模拟引擎。通过动态跟踪代理之间的真实依赖关系，AI 大都会最大限度地减少了错误依赖，增强了并行性，并实现了高效的硬件利用。我们的评估表明，与具有全局同步的标准并行模拟相比，AI 大都会实现了 1.3 倍至 4.15 倍的加速，随着代理数量的增加，接近最佳性能。

> With more advanced natural language understanding and reasoning capabilities, large language model (LLM)-powered agents are increasingly developed in simulated environments to perform complex tasks, interact with other agents, and exhibit emergent behaviors relevant to social science and gaming. However, current multi-agent simulations frequently suffer from inefficiencies due to the limited parallelism caused by false dependencies, resulting in performance bottlenecks. In this paper, we introduce AI Metropolis, a simulation engine that improves the efficiency of LLM agent simulations by incorporating out-of-order execution scheduling. By dynamically tracking real dependencies between agents, AI Metropolis minimizes false dependencies, enhancing parallelism and enabling efficient hardware utilization. Our evaluations demonstrate that AI Metropolis achieves speedups from 1.3x to 4.15x over standard parallel simulation with global synchronization, approaching optimal performance as the number of agents increases.

[Arxiv](https://arxiv.org/abs/2411.03519)