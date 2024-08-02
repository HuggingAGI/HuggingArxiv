# AgentGen：通过创造环境和任务，提升大型语言模型代理的规划能力

发布时间：2024年08月01日

`Agent` `人工智能` `自动化`

> AgentGen: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation

# 摘要

> 基于大型语言模型的智能体备受瞩目，日益流行。其中，规划能力是智能体的核心，涉及与环境互动并执行动作以达成目标。本文通过指令调优（代理训练）提升LLM的规划能力。最新研究表明，利用专家级轨迹进行调优能有效增强规划能力。然而，现有研究多依赖手动设计的任务和环境，这限制了轨迹的多样性和广泛性。为此，我们探索自动合成多样化环境和逐步难度递增的规划任务。我们提出AgentGen框架，首先生成环境，再基于环境生成任务。为提升环境多样性，我们采用多领域文本段作为合成环境的基础。同时，为确保任务难度多样性，我们设计了双向进化方法Bi-Evol，从易到难逐步合成任务集。评估显示，AgentGen显著提升了LLM的规划能力，如AgentGen调优的Llama-3 8B在性能上超越了GPT-3.5，甚至在某些任务中优于GPT-4。

> Large Language Model (LLM) based agents have garnered significant attention and are becoming increasingly popular. Furthermore, planning ability is a crucial component of an LLM-based agent, involving interaction with the environment and executing actions to complete a planning task, which generally entails achieving a desired goal from an initial state. This paper investigates enhancing the planning abilities of LLMs through instruction tuning, referred to as agent training. Recent studies have demonstrated that utilizing expert-level trajectory for instruction-tuning LLMs effectively enhances their planning capabilities. However, existing work primarily focuses on synthesizing trajectories from manually designed planning tasks and environments. The labor-intensive nature of creating these environments and tasks impedes the generation of sufficiently varied and extensive trajectories. To address this limitation, this paper explores the automated synthesis of diverse environments and a gradual range of planning tasks, from easy to difficult. We introduce a framework, AgentGen, that leverages LLMs first to generate environments and subsequently generate planning tasks conditioned on these environments. Specifically, to improve environmental diversity, we propose using an inspiration corpus composed of various domain-specific text segments as the context for synthesizing environments. Moreover, to increase the difficulty diversity of generated planning tasks, we propose a bidirectional evolution method, Bi-Evol, that evolves planning tasks from easier and harder directions to synthesize a task set with a smoother difficulty curve. The evaluation results derived from AgentBoard show that AgentGen greatly improves LLMs' planning ability, e.g., the AgentGen instruction-tuned Llama-3 8B surpasses GPT-3.5 in overall performance. Moreover, in certain tasks, it even outperforms GPT-4.

[Arxiv](https://arxiv.org/abs/2408.00764)