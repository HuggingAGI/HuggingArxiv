# 具身代理接口：为具身决策任务对 LLM 进行基准测试

发布时间：2024年10月09日

`Agent` `人工智能` `机器人`

> Embodied Agent Interface: Benchmarking LLMs for Embodied Decision Making

# 摘要

> 我们致力于评估大型语言模型（LLM）在具身决策中的表现。尽管已有大量研究利用 LLM 在具身环境中进行决策，但由于应用领域、目的和输入输出差异，我们对其性能的理解仍不系统。现有评估多依赖最终成功率，难以识别 LLM 的不足和问题所在，阻碍了具身代理的有效利用。为此，我们提出通用接口（具身代理接口），支持任务和模块输入输出的形式化。具体包括：1) 涉及状态和时间目标的广泛具身决策任务；2) 四种常用 LLM 决策模块：目标解释、子目标分解、动作排序和过渡建模；3) 细粒度指标，分解评估为幻觉、可操作性、规划等错误。总体上，我们的基准全面评估 LLM 在各子任务中的表现，揭示具身 AI 系统的优缺点，并为有效利用 LLM 提供指导。

> We aim to evaluate Large Language Models (LLMs) for embodied decision making. While a significant body of work has been leveraging LLMs for decision making in embodied environments, we still lack a systematic understanding of their performance because they are usually applied in different domains, for different purposes, and built based on different inputs and outputs. Furthermore, existing evaluations tend to rely solely on a final success rate, making it difficult to pinpoint what ability is missing in LLMs and where the problem lies, which in turn blocks embodied agents from leveraging LLMs effectively and selectively. To address these limitations, we propose a generalized interface (Embodied Agent Interface) that supports the formalization of various types of tasks and input-output specifications of LLM-based modules. Specifically, it allows us to unify 1) a broad set of embodied decision-making tasks involving both state and temporally extended goals, 2) four commonly-used LLM-based modules for decision making: goal interpretation, subgoal decomposition, action sequencing, and transition modeling, and 3) a collection of fine-grained metrics which break down evaluation into various types of errors, such as hallucination errors, affordance errors, various types of planning errors, etc. Overall, our benchmark offers a comprehensive assessment of LLMs' performance for different subtasks, pinpointing the strengths and weaknesses in LLM-powered embodied AI systems, and providing insights for effective and selective use of LLMs in embodied decision making.

[Arxiv](https://arxiv.org/abs/2410.07166)