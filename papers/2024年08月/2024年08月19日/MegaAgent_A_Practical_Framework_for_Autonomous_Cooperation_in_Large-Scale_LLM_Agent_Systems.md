# MegaAgent：为大型 LLM 代理系统量身打造的自主合作实用框架

发布时间：2024年08月19日

`Agent` `人工智能` `软件开发`

> MegaAgent: A Practical Framework for Autonomous Cooperation in Large-Scale LLM Agent Systems

# 摘要

> 随着大型语言模型的兴起，LLM 驱动的多代理系统应运而生，旨在解决现实世界的复杂任务。然而，这些系统的代理通常遵循固定的标准操作程序，缺乏自主性和灵活性，且忽视了代理间有效合作的重要性。为此，我们推出了 MegaAgent 框架，专为大规模 LLM 代理系统中的自主合作而设计。MegaAgent 通过动态生成代理，自动分配任务，系统化规划与监控，以及管理并发操作，展现了其高度自主性。此外，其分层结构和系统级并行设计进一步提升了性能和通信效率。通过五子棋游戏开发和国家政策模拟，我们验证了 MegaAgent 的卓越性能，它不仅超越了现有系统，还能迅速扩展至 590 个代理，同时确保高效合作。MegaAgent 作为首个无预设 SOP 的自主大规模 LLM-MA 系统，为该领域的深入研究开辟了新道路。代码已公开，详见 https://anonymous.4open.science/r/MegaAgent-81F3。

> With the emergence of large language models (LLMs), LLM-powered multi-agent systems (LLM-MA systems) have been proposed to tackle real-world tasks. However, their agents mostly follow predefined Standard Operating Procedures (SOPs) that remain unchanged across the whole interaction, lacking autonomy and scalability. Additionally, current solutions often overlook the necessity for effective agent cooperation. To address the above limitations, we propose MegaAgent, a practical framework designed for autonomous cooperation in large-scale LLM Agent systems. MegaAgent leverages the autonomy of agents to dynamically generate agents based on task requirements, incorporating features such as automatically dividing tasks, systematic planning and monitoring of agent activities, and managing concurrent operations. In addition, MegaAgent is designed with a hierarchical structure and employs system-level parallelism to enhance performance and boost communication. We demonstrate the effectiveness of MegaAgent through Gobang game development, showing that it outperforms popular LLM-MA systems; and national policy simulation, demonstrating its high autonomy and potential to rapidly scale up to 590 agents while ensuring effective cooperation among them. Our results indicate that MegaAgent is the first autonomous large-scale LLM-MA system with no pre-defined SOPs, high effectiveness and scalability, paving the way for further research in this field. Our code is at https://anonymous.4open.science/r/MegaAgent-81F3.

[Arxiv](https://arxiv.org/abs/2408.09955)