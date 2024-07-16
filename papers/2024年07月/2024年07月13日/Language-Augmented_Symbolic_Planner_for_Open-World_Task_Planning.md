# 开放世界任务规划的语言增强符号规划器

发布时间：2024年07月13日

`Agent` `机器人学` `人工智能`

> Language-Augmented Symbolic Planner for Open-World Task Planning

# 摘要

> 长期以来，让机器人代理执行复杂的长期任务一直是机器人学和人工智能领域的追求。尽管大型语言模型（LLM）展现出潜力，但其规划能力仍局限于短期任务，无法替代传统的符号规划方法。而符号规划器在开放世界环境中可能因对完整领域知识的假设而遭遇执行错误。为此，我们提出了一种语言增强的符号规划器（LASP），它融合了预训练的LLM，使传统符号规划器能在知识不完全的开源环境中运作。当遇到执行错误时，LASP能借助LLM根据观察诊断错误原因，并通过与环境的互动逐步构建完成任务所需的知识库。实验证明，LASP在开放世界环境中解决规划问题表现优异，即便在知识存在多处缺口的情况下也能应对自如。

> Enabling robotic agents to perform complex long-horizon tasks has been a long-standing goal in robotics and artificial intelligence (AI). Despite the potential shown by large language models (LLMs), their planning capabilities remain limited to short-horizon tasks and they are unable to replace the symbolic planning approach. Symbolic planners, on the other hand, may encounter execution errors due to their common assumption of complete domain knowledge which is hard to manually prepare for an open-world setting. In this paper, we introduce a Language-Augmented Symbolic Planner (LASP) that integrates pre-trained LLMs to enable conventional symbolic planners to operate in an open-world environment where only incomplete knowledge of action preconditions, objects, and properties is initially available. In case of execution errors, LASP can utilize the LLM to diagnose the cause of the error based on the observation and interact with the environment to incrementally build up its knowledge base necessary for accomplishing the given tasks. Experiments demonstrate that LASP is proficient in solving planning problems in the open-world setting, performing well even in situations where there are multiple gaps in the knowledge.

[Arxiv](https://arxiv.org/abs/2407.09792)