# 一次一个步骤：语言代理是逐步规划者

发布时间：2024年11月13日

`Agent` `语言模型` `规划任务`

> One STEP at a time: Language Agents are Stepwise Planners

# 摘要

> 语言代理在动态环境中显示出有希望的适应性，以执行复杂任务。然而，尽管大型语言模型中嵌入了多种知识，但在需要规划的任务方面，这些代理仍然存在不足。我们引入了 STEP，这是一个新的框架，旨在有效地从以前的经验中学习，以增强语言代理在未来步骤中的规划能力。具体来说，STEP 通过四个相互连接的组件起作用。首先，规划器承担任务，将其分解为子任务并提供相关见解。然后执行器生成行动候选，而评估器确保行动与从以前的经验中学习的规则一致。最后，内存存储经验以告知未来的决策。在 ScienceWorld 基准中，我们的结果表明，STEP 始终优于最先进的模型，总体得分为 67.4，并成功完成 18 个任务中的 12 个。这些发现突出了 STEP 作为增强语言代理规划能力的框架的潜力，为在动态环境中更复杂的任务解决铺平了道路。

> Language agents have shown promising adaptability in dynamic environments to perform complex tasks. However, despite the versatile knowledge embedded in large language models, these agents still fall short when it comes to tasks that require planning. We introduce STEP, a novel framework designed to efficiently learn from previous experiences to enhance the planning capabilities of language agents in future steps. Concretely, STEP functions through four interconnected components. First, the Planner takes on the task, breaks it down into subtasks and provides relevant insights. Then the Executor generates action candidates, while the Evaluator ensures the actions align with learned rules from previous experiences. Lastly, Memory stores experiences to inform future decisions. In the ScienceWorld benchmark, our results show that STEP consistently outperforms state-of-the-art models, achieving an overall score of 67.4 and successfully completing 12 out of 18 tasks. These findings highlight STEP's potential as a framework for enhancing planning capabilities in language agents, paving the way for more sophisticated task-solving in dynamic environments.

[Arxiv](https://arxiv.org/abs/2411.08432)