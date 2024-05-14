# 融合意图洞察与行为规划，精妙演绎人类指令至行为树之生成

发布时间：2024年05月13日

`Agent

这篇论文探讨了如何利用大型语言模型（LLMs）来解析高级指令中的目标，并通过最优行为树扩展算法（OBTEA）构建针对特定目标的高效行为树（BT）。这种方法旨在提高机器人在家庭或工业环境中执行任务的适应性和可靠性。论文提出的两阶段框架将意图理解与最优行为规划相结合，通过实验证明了LLMs在生成准确目标方面的能力，以及OBTEA在性能上的优越性。这种方法可以被视为一种智能代理（Agent）的设计和实现，因为它涉及理解和执行人类指令的任务，因此归类为Agent。` `机器人技术` `自动化控制`

> Integrating Intent Understanding and Optimal Behavior Planning for Behavior Tree Generation from Human Instructions

# 摘要

> 在家庭或工业环境中，机器人执行人类指令任务时，适应性与可靠性至关重要。行为树（BT）因其模块化和反应性而成为这些场景的理想控制架构。然而，现有的BT生成方法要么忽视了自然语言的解释，要么无法确保BT的成功。本文提出了一种两阶段框架，首先利用大型语言模型（LLMs）解析高级指令中的目标，然后通过最优行为树扩展算法（OBTEA）构建针对特定目标的高效BT。我们将目标以一阶逻辑中的良好形式化公式表示，巧妙地连接了意图理解与最优行为规划。在服务机器人上的实验证明了LLMs在生成语法正确且准确解释的目标方面的能力，同时OBTEA在多个指标上超越了基线BT扩展算法，最终证实了我们框架的实际应用潜力。项目网站为https://dids-ei.github.io/Project/LLM-OBTEA/。

> Robots executing tasks following human instructions in domestic or industrial environments essentially require both adaptability and reliability. Behavior Tree (BT) emerges as an appropriate control architecture for these scenarios due to its modularity and reactivity. Existing BT generation methods, however, either do not involve interpreting natural language or cannot theoretically guarantee the BTs' success. This paper proposes a two-stage framework for BT generation, which first employs large language models (LLMs) to interpret goals from high-level instructions, then constructs an efficient goal-specific BT through the Optimal Behavior Tree Expansion Algorithm (OBTEA). We represent goals as well-formed formulas in first-order logic, effectively bridging intent understanding and optimal behavior planning. Experiments in the service robot validate the proficiency of LLMs in producing grammatically correct and accurately interpreted goals, demonstrate OBTEA's superiority over the baseline BT Expansion algorithm in various metrics, and finally confirm the practical deployability of our framework. The project website is https://dids-ei.github.io/Project/LLM-OBTEA/.

[Arxiv](https://arxiv.org/abs/2405.07474)