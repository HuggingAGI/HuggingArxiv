# SUPER：评估代理在研究仓库中设置和执行任务的能力

发布时间：2024年09月11日

`LLM应用` `研究社区` `机器学习`

> SUPER: Evaluating Agents on Setting Up and Executing Tasks from Research Repositories

# 摘要

> 随着大型语言模型 (LLM) 在代码编写上的显著进步，它们能否自主重现研究仓库中的成果？这一能力将极大助力研究社区，帮助验证、理解和扩展前人工作。为此，我们推出了 SUPER，首个评估 LLM 从研究仓库中设置和执行任务能力的基准。SUPER 旨在模拟研究人员在处理机器学习和自然语言处理研究仓库时遇到的实际难题。基准包含三类问题：45 个端到端问题，附有专家解决方案；152 个聚焦特定挑战的子问题（如配置训练器）；以及 602 个自动生成的大规模开发问题。我们采用多种评估手段，结合黄金解决方案或其近似值，评估任务成功与进展。结果显示，即使是最先进的模型（GPT-4o），也仅能解决 16.3% 的端到端问题和 46.1% 的场景。这凸显了任务的难度，并表明 SUPER 将成为社区推进和衡量进展的重要工具。

> Given that Large Language Models (LLMs) have made significant progress in writing code, can they now be used to autonomously reproduce results from research repositories? Such a capability would be a boon to the research community, helping researchers validate, understand, and extend prior work. To advance towards this goal, we introduce SUPER, the first benchmark designed to evaluate the capability of LLMs in setting up and executing tasks from research repositories. SUPERaims to capture the realistic challenges faced by researchers working with Machine Learning (ML) and Natural Language Processing (NLP) research repositories. Our benchmark comprises three distinct problem sets: 45 end-to-end problems with annotated expert solutions, 152 sub problems derived from the expert set that focus on specific challenges (e.g., configuring a trainer), and 602 automatically generated problems for larger-scale development. We introduce various evaluation measures to assess both task success and progress, utilizing gold solutions when available or approximations otherwise. We show that state-of-the-art approaches struggle to solve these problems with the best model (GPT-4o) solving only 16.3% of the end-to-end set, and 46.1% of the scenarios. This illustrates the challenge of this task, and suggests that SUPER can serve as a valuable resource for the community to make and measure progress.

[Arxiv](https://arxiv.org/abs/2409.07440)