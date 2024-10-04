# SEAL：借助语言模型实现语义增强的模仿学习

发布时间：2024年10月03日

`Agent` `机器人` `人工智能`

> SEAL: SEmantic-Augmented Imitation Learning via Language Model

# 摘要

> 分层模仿学习 (HIL) 是解决长时决策任务的有力工具，但面临缺乏详细监督标签和大量专家演示的挑战。我们提出的 SEAL 框架，利用大型语言模型 (LLM) 的语义和世界知识，无需预知任务层次结构，即可生成语义丰富的子目标表示。SEAL 通过双编码器结构，结合监督学习和无监督向量量化，提升子目标表示的鲁棒性，并引入过渡增强的低级规划器，优化子目标过渡的适应性。实验结果显示，SEAL 在专家数据集有限和任务复杂的场景中，显著超越了现有 HIL 和 LLM 规划方法。

> Hierarchical Imitation Learning (HIL) is a promising approach for tackling long-horizon decision-making tasks. While it is a challenging task due to the lack of detailed supervisory labels for sub-goal learning, and reliance on hundreds to thousands of expert demonstrations. In this work, we introduce SEAL, a novel framework that leverages Large Language Models (LLMs)'s powerful semantic and world knowledge for both specifying sub-goal space and pre-labeling states to semantically meaningful sub-goal representations without prior knowledge of task hierarchies. SEAL employs a dual-encoder structure, combining supervised LLM-guided sub-goal learning with unsupervised Vector Quantization (VQ) for more robust sub-goal representations. Additionally, SEAL incorporates a transition-augmented low-level planner for improved adaptation to sub-goal transitions. Our experiments demonstrate that SEAL outperforms state-of-the-art HIL methods and LLM-based planning approaches, particularly in settings with small expert datasets and complex long-horizon tasks.

[Arxiv](https://arxiv.org/abs/2410.02231)