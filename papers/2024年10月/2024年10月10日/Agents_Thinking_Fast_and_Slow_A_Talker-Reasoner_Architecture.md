# 快速与慢速思考的智能体：一种说者与思考者结合的架构

发布时间：2024年10月10日

`Agent` `人工智能` `健康管理`

> Agents Thinking Fast and Slow: A Talker-Reasoner Architecture

# 摘要

> 大型语言模型让各类代理通过自然对话与用户互动，使其承担起对话和规划/推理的双重任务。对话回应需基于所有信息，行动则需助力目标实现。这种对话与多步骤推理的二分法，类似于卡尼曼提出的“快思考与慢思考”。我们设计了“Talker”代理（系统1），快速直观，负责对话回应；以及“Reasoner”代理（系统2），慢而深思，负责推理规划，调用工具，执行行动，更新代理状态。我们介绍了Talker-Reasoner架构及其优势，如模块化和低延迟，并以睡眠教练代理为例，展示其现实应用价值。

> Large language models have enabled agents of all kinds to interact with users through natural conversation. Consequently, agents now have two jobs: conversing and planning/reasoning. Their conversational responses must be informed by all available information, and their actions must help to achieve goals. This dichotomy between conversing with the user and doing multi-step reasoning and planning can be seen as analogous to the human systems of "thinking fast and slow" as introduced by Kahneman. Our approach is comprised of a "Talker" agent (System 1) that is fast and intuitive, and tasked with synthesizing the conversational response; and a "Reasoner" agent (System 2) that is slower, more deliberative, and more logical, and is tasked with multi-step reasoning and planning, calling tools, performing actions in the world, and thereby producing the new agent state. We describe the new Talker-Reasoner architecture and discuss its advantages, including modularity and decreased latency. We ground the discussion in the context of a sleep coaching agent, in order to demonstrate real-world relevance.

[Arxiv](https://arxiv.org/abs/2410.08328)