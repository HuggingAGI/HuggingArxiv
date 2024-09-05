# 大型语言模型：自定义环境多目标强化学习中的高效奖励函数探索者

发布时间：2024年09月04日

`LLM应用` `人工智能`

> Large Language Models as Efficient Reward Function Searchers for Custom-Environment Multi-Objective Reinforcement Learning

# 摘要

> 本文利用 LLM 设计奖励函数，展示了其在强化学习任务中的巨大潜力。面对复杂环境和多重要求的挑战，我们使 LLM 成为高效的白盒搜索器，突显其强大的语义理解能力。我们为每个用户需求定制奖励组件，并通过奖励评论家精准识别代码形式。LLM 随后为这些组件分配权重，根据训练日志动态调整，确保搜索步长的自适应性。在无人类反馈的水下信息收集任务中，奖励评论家通过单次反馈即能修正代码，避免累积错误。权重的巧妙初始化使得我们无需繁琐搜索即可获得多样化的奖励函数。即便权重出现百倍偏差，也仅需寥寥数次迭代即可达成用户需求。此外，该框架兼容 GPT-3.5 Turbo，无需复杂的数值处理。

> Leveraging large language models (LLMs) for designing reward functions demonstrates significant potential. However, achieving effective design and improvement of reward functions in reinforcement learning (RL) tasks with complex custom environments and multiple requirements presents considerable challenges. In this paper, we enable LLMs to be effective white-box searchers, highlighting their advanced semantic understanding capabilities. Specifically, we generate reward components for each explicit user requirement and employ the reward critic to identify the correct code form. Then, LLMs assign weights to the reward components to balance their values and iteratively search and optimize these weights based on the context provided by the training log analyzer, while adaptively determining the search step size. We applied the framework to an underwater information collection RL task without direct human feedback or reward examples (zero-shot). The reward critic successfully correct the reward code with only one feedback for each requirement, effectively preventing irreparable errors that can occur when reward function feedback is provided in aggregate. The effective initialization of weights enables the acquisition of different reward functions within the Pareto solution set without weight search. Even in the case where a weight is 100 times off, fewer than four iterations are needed to obtain solutions that meet user requirements. The framework also works well with most prompts utilizing GPT-3.5 Turbo, since it does not require advanced numerical understanding or calculation.

[Arxiv](https://arxiv.org/abs/2409.02428)