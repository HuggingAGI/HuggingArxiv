# SWE-Search：借助蒙特卡罗树搜索和迭代改进来强化软件代理

发布时间：2024年10月29日

`Agent` `软件工程` `软件代理`

> SWE-Search: Enhancing Software Agents with Monte Carlo Tree Search and Iterative Refinement

# 摘要

> 软件工程师在复杂多变的环境中工作，必须持续适应不断变化的需求，从经验中反复学习，并依据新的见解重新思考自身的方法。然而，当下基于大型语言模型（LLM）的软件代理往往依赖僵化流程，常常重复无效动作，且不具备评估自身性能或随时间调整策略的能力。为应对这些挑战，我们提出了 SWE-Search，这一多代理框架将蒙特卡罗树搜索（MCTS）与自我改进机制相融合，以提升软件代理在库级软件任务上的表现。SWE-Search 借助融入混合价值函数拓展了传统的 MCTS，该函数利用 LLM 进行数值估算和定性评估。这促成了自我反馈循环，使代理能依据定量数值评估和对所行轨迹的定性自然语言评估，反复优化策略。此框架涵盖用于自适应探索的 SWE-Agent、用于迭代反馈的 Value Agent 以及利于多代理辩论以实现协作决策的 Discriminator Agent。应用于 SWE-bench 基准，相较于不含 MCTS 的标准开源代理，我们的方法在五个模型中实现了 23%的相对性能提升。我们的分析揭示了性能随搜索深度增加而提升的情况，并明确了有助于软件代理有效自我评估的关键要素。此项工作凸显了自我评估驱动的搜索技术在复杂、动态的软件工程环境中增强代理推理和规划的潜力。

> Software engineers operating in complex and dynamic environments must continuously adapt to evolving requirements, learn iteratively from experience, and reconsider their approaches based on new insights. However, current large language model (LLM)-based software agents often rely on rigid processes and tend to repeat ineffective actions without the capacity to evaluate their performance or adapt their strategies over time. To address these challenges, we propose SWE-Search, a multi-agent framework that integrates Monte Carlo Tree Search (MCTS) with a self-improvement mechanism to enhance software agents' performance on repository-level software tasks. SWE-Search extends traditional MCTS by incorporating a hybrid value function that leverages LLMs for both numerical value estimation and qualitative evaluation. This enables self-feedback loops where agents iteratively refine their strategies based on both quantitative numerical evaluations and qualitative natural language assessments of pursued trajectories. The framework includes a SWE-Agent for adaptive exploration, a Value Agent for iterative feedback, and a Discriminator Agent that facilitates multi-agent debate for collaborative decision-making. Applied to the SWE-bench benchmark, our approach demonstrates a 23% relative improvement in performance across five models compared to standard open-source agents without MCTS. Our analysis reveals how performance scales with increased search depth and identifies key factors that facilitate effective self-evaluation in software agents. This work highlights the potential of self-evaluation driven search techniques to enhance agent reasoning and planning in complex, dynamic software engineering environments.

[Arxiv](https://arxiv.org/abs/2410.20285)