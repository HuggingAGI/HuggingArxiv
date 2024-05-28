# AutoManual：借助大型语言模型代理的交互式环境学习，智能生成操作手册

发布时间：2024年05月25日

`Agent

这篇论文介绍了一个名为AutoManual的框架，该框架旨在增强基于大型语言模型（LLM）的代理的自主学习和适应新环境的能力。通过引入两个代理（规划者和构建者）以及一种新的“案例条件提示”策略，该框架能够优化环境知识的细化，并生成全面的行动指南。这种方法不仅提高了LLM代理的适应性，还保持了指南的人类可读性，并在ALFWorld基准测试中取得了显著的成功率提升。因此，这篇论文更符合Agent分类，因为它专注于开发和优化基于LLM的代理系统。` `自动化` `人工智能`

> AutoManual: Generating Instruction Manuals by LLM Agents via Interactive Environmental Learning

# 摘要

> 基于大型语言模型（LLM）的代理在跨领域任务自主完成方面展现出潜力，但通常需要精心设计和专家提示，这限制了其适应性。我们提出的AutoManual框架，使LLM代理能通过交互自主学习并适应新环境。该框架将环境知识细化为多样规则，并通过两个代理在线优化：规划者根据规则制定行动计划，构建者则通过结构化系统更新规则，同时采用“案例条件提示”策略减少幻觉。最终，制定者将规则整合成全面指南，既提升适应性，又指导较小LLM的规划，且保持人类可读性。仅凭一次简单演示，AutoManual在ALFWorld基准上将任务成功率提升至GPT-4-turbo的97.4%和GPT-3.5-turbo的86.2%。源代码即将发布。

> Large Language Models (LLM) based agents have shown promise in autonomously completing tasks across various domains, e.g., robotics, games, and web navigation. However, these agents typically require elaborate design and expert prompts to solve tasks in specific domains, which limits their adaptability. We introduce AutoManual, a framework enabling LLM agents to autonomously build their understanding through interaction and adapt to new environments. AutoManual categorizes environmental knowledge into diverse rules and optimizes them in an online fashion by two agents: 1) The Planner codes actionable plans based on current rules for interacting with the environment. 2) The Builder updates the rules through a well-structured rule system that facilitates online rule management and essential detail retention. To mitigate hallucinations in managing rules, we introduce \textit{case-conditioned prompting} strategy for the Builder. Finally, the Formulator agent compiles these rules into a comprehensive manual. The self-generated manual can not only improve the adaptability but also guide the planning of smaller LLMs while being human-readable. Given only one simple demonstration, AutoManual significantly improves task success rates, achieving 97.4\% with GPT-4-turbo and 86.2\% with GPT-3.5-turbo on ALFWorld benchmark tasks. The source code will be available soon.

![AutoManual：借助大型语言模型代理的交互式环境学习，智能生成操作手册](../../../paper_images/2405.16247/x1.png)

![AutoManual：借助大型语言模型代理的交互式环境学习，智能生成操作手册](../../../paper_images/2405.16247/x2.png)

![AutoManual：借助大型语言模型代理的交互式环境学习，智能生成操作手册](../../../paper_images/2405.16247/x3.png)

![AutoManual：借助大型语言模型代理的交互式环境学习，智能生成操作手册](../../../paper_images/2405.16247/cross_task.png)

![AutoManual：借助大型语言模型代理的交互式环境学习，智能生成操作手册](../../../paper_images/2405.16247/miniwob.png)

![AutoManual：借助大型语言模型代理的交互式环境学习，智能生成操作手册](../../../paper_images/2405.16247/x4.png)

![AutoManual：借助大型语言模型代理的交互式环境学习，智能生成操作手册](../../../paper_images/2405.16247/x5.png)

[Arxiv](https://arxiv.org/abs/2405.16247)