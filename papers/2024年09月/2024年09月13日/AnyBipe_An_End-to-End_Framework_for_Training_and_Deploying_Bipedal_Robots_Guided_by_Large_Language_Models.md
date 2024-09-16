# AnyBipe：一个端到端的框架，专为训练和部署由大型语言模型引导的双足机器人而设计。

发布时间：2024年09月13日

`Agent` `机器人` `自动化`

> AnyBipe: An End-to-End Framework for Training and Deploying Bipedal Robots Guided by Large Language Models

# 摘要

> 训练和部署机器人强化学习策略，尤其是在执行特定任务时，面临诸多挑战。尽管近期在奖励函数设计、训练技术、模拟到现实转移及性能分析方面有所突破，但仍需大量人工介入。本文提出一个由大型语言模型 (LLM) 引导的端到端框架，用于训练和部署 RL 策略，并在双足机器人上验证其效果。框架包含三个模块：LLM 引导的奖励函数设计、基于先前研究的 RL 训练及模拟到现实的同态评估。该设计通过简化平台需求，大幅减少人工干预，同时保留整合人工策略和历史数据的可能性。我们详述各模块的构建及其优于传统方法之处，并展示框架自主优化双足机器人运动控制的能力，彰显其独立运作的潜力。

> Training and deploying reinforcement learning (RL) policies for robots, especially in accomplishing specific tasks, presents substantial challenges. Recent advancements have explored diverse reward function designs, training techniques, simulation-to-reality (sim-to-real) transfers, and performance analysis methodologies, yet these still require significant human intervention. This paper introduces an end-to-end framework for training and deploying RL policies, guided by Large Language Models (LLMs), and evaluates its effectiveness on bipedal robots. The framework consists of three interconnected modules: an LLM-guided reward function design module, an RL training module leveraging prior work, and a sim-to-real homomorphic evaluation module. This design significantly reduces the need for human input by utilizing only essential simulation and deployment platforms, with the option to incorporate human-engineered strategies and historical data. We detail the construction of these modules, their advantages over traditional approaches, and demonstrate the framework's capability to autonomously develop and refine controlling strategies for bipedal robot locomotion, showcasing its potential to operate independently of human intervention.

[Arxiv](https://arxiv.org/abs/2409.08904)