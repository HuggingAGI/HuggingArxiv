# MHRC：结合大型语言模型的闭环分散式多异构机器人协作

发布时间：2024年09月24日

`Agent` `机器人技术` `人工智能`

> MHRC: Closed-loop Decentralized Multi-Heterogeneous Robot Collaboration with Large Language Models

# 摘要

> 大型语言模型 (LLM) 与机器人技术的融合，极大地增强了机器人在感知、认知和任务规划方面的能力。通过自然语言接口，我们能够统一表达不同机器人之间的能力差异，促进它们之间的沟通与协作，实现无缝的任务分配。然而，利用 LLM 实现分散的多异构机器人协作任务的研究仍处于起步阶段。本文提出了一种新框架，利用 LLM 实现多异构机器人的分散协作，涵盖移动、操作和移动操作三种机器人，共同完成探索、运输和组织等任务。我们设计了丰富的文本反馈机制和思维链 (CoT) 提示，以提升任务规划效率和系统整体性能。实验结果表明，该框架在不同场景下的有效性和必要性得到了验证。

> The integration of large language models (LLMs) with robotics has significantly advanced robots' abilities in perception, cognition, and task planning. The use of natural language interfaces offers a unified approach for expressing the capability differences of heterogeneous robots, facilitating communication between them, and enabling seamless task allocation and collaboration. Currently, the utilization of LLMs to achieve decentralized multi-heterogeneous robot collaborative tasks remains an under-explored area of research. In this paper, we introduce a novel framework that utilizes LLMs to achieve decentralized collaboration among multiple heterogeneous robots. Our framework supports three robot categories, mobile robots, manipulation robots, and mobile manipulation robots, working together to complete tasks such as exploration, transportation, and organization. We developed a rich set of textual feedback mechanisms and chain-of-thought (CoT) prompts to enhance task planning efficiency and overall system performance. The mobile manipulation robot can adjust its base position flexibly, ensuring optimal conditions for grasping tasks. The manipulation robot can comprehend task requirements, seek assistance when necessary, and handle objects appropriately. Meanwhile, the mobile robot can explore the environment extensively, map object locations, and communicate this information to the mobile manipulation robot, thus improving task execution efficiency. We evaluated the framework using PyBullet, creating scenarios with three different room layouts and three distinct operational tasks. We tested various LLM models and conducted ablation studies to assess the contributions of different modules. The experimental results confirm the effectiveness and necessity of our proposed framework.

[Arxiv](https://arxiv.org/abs/2409.16030)