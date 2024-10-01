# 探讨 OpenAI o1 模型的规划能力：可行性、最优性及可推广性

发布时间：2024年09月29日

`LLM应用` `人工智能`

> On The Planning Abilities of OpenAI's o1 Models: Feasibility, Optimality, and Generalizability

# 摘要

> 最近，大型语言模型（LLM）在复杂推理任务中的表现令人瞩目，但其在规划方面的潜力仍待挖掘。本研究聚焦于 OpenAI 的 o1 模型，通过一系列基准任务，评估其在规划中的可行性、最优性和泛化性。实证结果显示，o1-preview 在自我评估和遵循约束方面表现出色，但在决策和内存管理上存在瓶颈，尤其是在空间推理任务中。尽管 o1-preview 在遵守任务约束和状态转换上超越了 GPT-4，但其生成的解决方案常含冗余，且在复杂空间任务中的泛化能力有限。这项初步研究揭示了 LLM 在规划中的局限，为未来研究指明了改进方向，包括优化内存管理、决策机制和泛化能力。

> Recent advancements in Large Language Models (LLMs) have showcased their ability to perform complex reasoning tasks, but their effectiveness in planning remains underexplored. In this study, we evaluate the planning capabilities of OpenAI's o1 models across a variety of benchmark tasks, focusing on three key aspects: feasibility, optimality, and generalizability. Through empirical evaluations on constraint-heavy tasks (e.g., $\textit{Barman}$, $\textit{Tyreworld}$) and spatially complex environments (e.g., $\textit{Termes}$, $\textit{Floortile}$), we highlight o1-preview's strengths in self-evaluation and constraint-following, while also identifying bottlenecks in decision-making and memory management, particularly in tasks requiring robust spatial reasoning. Our results reveal that o1-preview outperforms GPT-4 in adhering to task constraints and managing state transitions in structured environments. However, the model often generates suboptimal solutions with redundant actions and struggles to generalize effectively in spatially complex tasks. This pilot study provides foundational insights into the planning limitations of LLMs, offering key directions for future research on improving memory management, decision-making, and generalization in LLM-based planning.

[Arxiv](https://arxiv.org/abs/2409.19924)