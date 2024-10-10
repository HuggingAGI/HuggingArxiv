# ConceptAgent：利用 LLM 进行先决条件基础和树搜索，实现稳健的任务规划与执行

发布时间：2024年10月08日

`Agent` `机器人` `人工智能`

> ConceptAgent: LLM-Driven Precondition Grounding and Tree Search for Robust Task Planning and Execution

# 摘要

> 在开放世界中进行机器人规划和执行极具挑战，因其状态空间庞大且任务多变。最新感知算法与大型语言模型（LLM）的结合，为解决这些难题提供了新思路。LLM 的常识推理能力，为高效搜索动作空间提供了有力支持。然而，现有研究忽视了 LLM 可能产生的幻觉问题，导致计划执行失败。为此，我们推出了 ConceptAgent，一个自然语言驱动的机器人平台，专为非结构化环境中的任务执行设计。我们聚焦于 LLM 在复杂状态和动作空间中规划的可扩展性与可靠性，提出了创新解决方案，包括谓词接地技术以防止和恢复不可行动作，以及具有自我反思的 LLM 引导蒙特卡洛树搜索。模拟实验显示，ConceptAgent 在多种任务中表现优异，任务完成率高达 19%，远超其他最先进基线。消融研究进一步表明，从基线代理到完全增强的 ConceptAgent，任务完成率提升了 20%，凸显了谓词接地与 LLM 引导树搜索在复杂环境中的重要贡献。

> Robotic planning and execution in open-world environments is a complex problem due to the vast state spaces and high variability of task embodiment. Recent advances in perception algorithms, combined with Large Language Models (LLMs) for planning, offer promising solutions to these challenges, as the common sense reasoning capabilities of LLMs provide a strong heuristic for efficiently searching the action space. However, prior work fails to address the possibility of hallucinations from LLMs, which results in failures to execute the planned actions largely due to logical fallacies at high- or low-levels. To contend with automation failure due to such hallucinations, we introduce ConceptAgent, a natural language-driven robotic platform designed for task execution in unstructured environments. With a focus on scalability and reliability of LLM-based planning in complex state and action spaces, we present innovations designed to limit these shortcomings, including 1) Predicate Grounding to prevent and recover from infeasible actions, and 2) an embodied version of LLM-guided Monte Carlo Tree Search with self reflection. In simulation experiments, ConceptAgent achieved a 19% task completion rate across three room layouts and 30 easy level embodied tasks outperforming other state-of-the-art LLM-driven reasoning baselines that scored 10.26% and 8.11% on the same benchmark. Additionally, ablation studies on moderate to hard embodied tasks revealed a 20% increase in task completion from the baseline agent to the fully enhanced ConceptAgent, highlighting the individual and combined contributions of Predicate Grounding and LLM-guided Tree Search to enable more robust automation in complex state and action spaces.

[Arxiv](https://arxiv.org/abs/2410.06108)