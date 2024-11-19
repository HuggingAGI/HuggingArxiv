# 大型语言模型可充当用户代理来评估面向任务的对话系统

发布时间：2024年11月15日

`Agent` `对话系统` `模型评估`

> Large Language Models as User-Agents for Evaluating Task-Oriented-Dialogue Systems

# 摘要

> 传统上，离线数据集常被用于评估面向任务的对话（TOD）模型。然而，这类数据集缺乏上下文感知，并非评估对话系统的理想基准。相较而言，具备上下文感知能力的用户代理能够模拟人类对话的多变性和不可预测性，是更优的评估替代方案。此前的研究已借助大型语言模型（LLMs）开发用户代理。我们的工作在此基础上，利用 LLMs 为 TOD 系统的评估创建用户代理。这包括给 LLMs 提供提示，以上下文示例作引导，并追踪用户目标状态。我们对用户代理的多样性和任务完成指标的评估显示，使用更优的提示能提升性能。另外，我们在这一动态框架内提出了用于自动评估 TOD 模型的方法。

> Traditionally, offline datasets have been used to evaluate task-oriented dialogue (TOD) models. These datasets lack context awareness, making them suboptimal benchmarks for conversational systems. In contrast, user-agents, which are context-aware, can simulate the variability and unpredictability of human conversations, making them better alternatives as evaluators. Prior research has utilized large language models (LLMs) to develop user-agents. Our work builds upon this by using LLMs to create user-agents for the evaluation of TOD systems. This involves prompting an LLM, using in-context examples as guidance, and tracking the user-goal state. Our evaluation of diversity and task completion metrics for the user-agents shows improved performance with the use of better prompts. Additionally, we propose methodologies for the automatic evaluation of TOD models within this dynamic framework.

[Arxiv](https://arxiv.org/abs/2411.09972)