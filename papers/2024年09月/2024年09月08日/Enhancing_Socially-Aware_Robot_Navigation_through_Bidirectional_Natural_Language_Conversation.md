# 通过双向自然语言对话，提升机器人导航的社会意识

发布时间：2024年09月08日

`Agent` `机器人` `人机交互`

> Enhancing Socially-Aware Robot Navigation through Bidirectional Natural Language Conversation

# 摘要

> 机器人导航是一个跨领域的重要研究课题。传统方法多侧重于效率和避障，却忽略了共享空间中对人类行为的细致理解。随着服务机器人的普及，如何在复杂环境中实现机器人与人类的互动成为研究重点。社会感知导航应运而生，但现有研究多停留在预测行人运动或发出警报，未能真正促进人机互动。本文提出混合软演员-评论家与大型语言模型（HSAC-LLM），这一创新模型将深度强化学习与大型语言模型结合，既能预测连续动作，也能处理离散动作。HSAC-LLM还能基于自然语言与行人模型实现双向互动。当检测到潜在碰撞时，机器人可主动沟通，获取并执行避让策略。实验表明，HSAC-LLM不仅有效促进人机互动，在导航和避障方面也优于现有算法。这一创新为动态环境中的人机互动提供了新思路。相关视频请访问https://hsacllm.github.io/。

> Robot navigation is an important research field with applications in various domains. However, traditional approaches often prioritize efficiency and obstacle avoidance, neglecting a nuanced understanding of human behavior or intent in shared spaces. With the rise of service robots, there's an increasing emphasis on endowing robots with the capability to navigate and interact in complex real-world environments. Socially aware navigation has recently become a key research area. However, existing work either predicts pedestrian movements or simply emits alert signals to pedestrians, falling short of facilitating genuine interactions between humans and robots. In this paper, we introduce the Hybrid Soft Actor-Critic with Large Language Model (HSAC-LLM), an innovative model designed for socially-aware navigation in robots. This model seamlessly integrates deep reinforcement learning with large language models, enabling it to predict both continuous and discrete actions for navigation. Notably, HSAC-LLM facilitates bidirectional interaction based on natural language with pedestrian models. When a potential collision with pedestrians is detected, the robot can initiate or respond to communications with pedestrians, obtaining and executing subsequent avoidance strategies. Experimental results in 2D simulation, the Gazebo environment, and the real-world environment demonstrate that HSAC-LLM not only efficiently enables interaction with humans but also exhibits superior performance in navigation and obstacle avoidance compared to state-of-the-art DRL algorithms. We believe this innovative paradigm opens up new avenues for effective and socially aware human-robot interactions in dynamic environments. Videos are available at https://hsacllm.github.io/.

[Arxiv](https://arxiv.org/abs/2409.04965)