# DialSim：实时模拟器，专为评估对话代理在长期对话中的理解能力而设计

发布时间：2024年06月18日

`Agent

这篇论文介绍了一个名为 DialSim 的实时对话模拟器，用于评估和分析对话代理（Agent）的能力，特别是在实时互动和多方对话等复杂场景下的表现。论文通过模拟器测试代理的即时反应和长期对话管理能力，并探讨了代理对预设知识的依赖性。因此，这篇论文应归类于Agent，因为它主要关注的是对话代理的评估和改进。` `对话系统`

> DialSim: A Real-Time Simulator for Evaluating Long-Term Dialogue Understanding of Conversational Agents

# 摘要

> 大型语言模型（LLMs）的进步已经使对话代理在多个领域（如教育）中大放异彩。然而，这些代理的评估往往忽视了现实对话的复杂性，如实时互动和多方对话。为此，我们推出了DialSim，一个实时对话模拟器，让代理扮演热门电视剧中的角色，应对即兴提问，并区分信息的新旧。DialSim不仅考验代理的即时反应和长期对话管理能力，还通过对抗性场景（如角色名称互换）来检验其对预设知识的依赖。我们通过DialSim评估并剖析了最新对话代理的优劣，为对话AI的未来发展提供了深刻的洞见。DialSim的详细信息可在https://github.com/jiho283/Simulator找到。

> Recent advancements in Large Language Models (LLMs) have significantly enhanced the capabilities of conversational agents, making them applicable to various fields (e.g., education). Despite their progress, the evaluation of the agents often overlooks the complexities of real-world conversations, such as real-time interactions, multi-party dialogues, and extended contextual dependencies. To bridge this gap, we introduce DialSim, a real-time dialogue simulator. In this simulator, an agent is assigned the role of a character from popular TV shows, requiring it to respond to spontaneous questions using past dialogue information and to distinguish between known and unknown information. Key features of DialSim include evaluating the agent's ability to respond within a reasonable time limit, handling long-term multi-party dialogues, and managing adversarial settings (e.g., swap character names) to challenge the agent's reliance on pre-trained knowledge. We utilized this simulator to evaluate the latest conversational agents and analyze their limitations. Our experiments highlight both the strengths and weaknesses of these agents, providing valuable insights for future improvements in the field of conversational AI. DialSim is available at https://github.com/jiho283/Simulator.

![DialSim：实时模拟器，专为评估对话代理在长期对话中的理解能力而设计](../../../paper_images/2406.13144/x1.png)

[Arxiv](https://arxiv.org/abs/2406.13144)