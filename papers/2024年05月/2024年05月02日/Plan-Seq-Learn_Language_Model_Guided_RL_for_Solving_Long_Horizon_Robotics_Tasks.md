# Plan-Seq-Learn：一种由语言模型引导的强化学习方法，专为解决机器人领域的长期任务而设计。

发布时间：2024年05月02日

`分类：Agent` `机器人技术`

> Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks

# 摘要

> 大型语言模型（LLMs）展现出能够为长期机器人任务进行高级规划的能力，但现有技术依赖于一个预先定义的技能库，如抓取、放置等。LLM在规划方面的应用尚未触及如何设计或学习这些技能，尤其在长期任务中，这仍是一个难题。此外，机器人在执行许多任务时需要精细调整行为，这就需要能够灵活修改底层控制动作。是否可以利用LLMs的海量知识来指导高层策略，通过强化学习（RL）策略在线高效解决机器人控制任务，而无需依赖预设技能集？本文提出了Plan-Seq-Learn（PSL），一种模块化方法，它通过运动规划将抽象语言与学习到的低级控制相结合，以解决从零开始的长期机器人任务。PSL在超过25个具有挑战性的机器人任务上取得了业界领先的成绩，这些任务包含多达10个阶段。基于原始视觉输入，PSL在四个基准测试中的成功率超过85%，超越了基于语言、传统和端到端的解决方案。相关视频和代码可在 https://mihdalal.github.io/planseqlearn/ 查看。

> Large Language Models (LLMs) have been shown to be capable of performing high-level planning for long-horizon robotics tasks, yet existing methods require access to a pre-defined skill library (e.g. picking, placing, pulling, pushing, navigating). However, LLM planning does not address how to design or learn those behaviors, which remains challenging particularly in long-horizon settings. Furthermore, for many tasks of interest, the robot needs to be able to adjust its behavior in a fine-grained manner, requiring the agent to be capable of modifying low-level control actions. Can we instead use the internet-scale knowledge from LLMs for high-level policies, guiding reinforcement learning (RL) policies to efficiently solve robotic control tasks online without requiring a pre-determined set of skills? In this paper, we propose Plan-Seq-Learn (PSL): a modular approach that uses motion planning to bridge the gap between abstract language and learned low-level control for solving long-horizon robotics tasks from scratch. We demonstrate that PSL achieves state-of-the-art results on over 25 challenging robotics tasks with up to 10 stages. PSL solves long-horizon tasks from raw visual input spanning four benchmarks at success rates of over 85%, out-performing language-based, classical, and end-to-end approaches. Video results and code at https://mihdalal.github.io/planseqlearn/

[Arxiv](https://arxiv.org/abs/2405.01534)