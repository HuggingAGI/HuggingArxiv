# RepairAgent：一款利用大型语言模型技术的自动程序修复智能代理。

发布时间：2024年03月25日

`Agent` `软件工程` `程序修复`

> RepairAgent: An Autonomous, LLM-Based Agent for Program Repair

# 摘要

> 自动化程序修复技术异军突起，有效减轻了软件缺陷对系统稳定性和用户体验的负面影响。本文首次提出了RepairAgent，这是一种基于大型语言模型（LLM）的自主代理，用于应对程序修复的挑战。RepairAgent打破常规，不再依赖固定提示或反馈循环，而是将LLM视为一个能够主动规划和执行修复动作的智能体，通过调用恰当的工具来解决漏洞。它灵活地在收集漏洞信息、准备修复材料和验证修复方案之间切换，并根据已有信息和过往修复尝试的反馈来选择使用哪些工具。RepairAgent的核心贡献在于一套实用的程序修复工具、一种能让LLM与这些工具动态互动的提示格式，以及一个指导代理调用工具的有限状态机。在Defects4J数据集上的测试显示，RepairAgent能独立修复164个漏洞，包括之前技术无法解决的39个。与LLM的互动平均消耗27万令牌/漏洞，按OpenAI GPT-3.5模型的现行收费标准，每个漏洞的成本约为14美分。这项研究开创性地将基于LLM的自主代理应用于程序修复领域，为软件工程领域的代理技术发展开辟了新路径。

> Automated program repair has emerged as a powerful technique to mitigate the impact of software bugs on system reliability and user experience. This paper introduces RepairAgent, the first work to address the program repair challenge through an autonomous agent based on a large language model (LLM). Unlike existing deep learning-based approaches, which prompt a model with a fixed prompt or in a fixed feedback loop, our work treats the LLM as an agent capable of autonomously planning and executing actions to fix bugs by invoking suitable tools. RepairAgent freely interleaves gathering information about the bug, gathering repair ingredients, and validating fixes, while deciding which tools to invoke based on the gathered information and feedback from previous fix attempts. Key contributions that enable RepairAgent include a set of tools that are useful for program repair, a dynamically updated prompt format that allows the LLM to interact with these tools, and a finite state machine that guides the agent in invoking the tools. Our evaluation on the popular Defects4J dataset demonstrates RepairAgent's effectiveness in autonomously repairing 164 bugs, including 39 bugs not fixed by prior techniques. Interacting with the LLM imposes an average cost of 270,000 tokens per bug, which, under the current pricing of OpenAI's GPT-3.5 model, translates to 14 cents of USD per bug. To the best of our knowledge, this work is the first to present an autonomous, LLM-based agent for program repair, paving the way for future agent-based techniques in software engineering.

[Arxiv](https://arxiv.org/abs/2403.17134)