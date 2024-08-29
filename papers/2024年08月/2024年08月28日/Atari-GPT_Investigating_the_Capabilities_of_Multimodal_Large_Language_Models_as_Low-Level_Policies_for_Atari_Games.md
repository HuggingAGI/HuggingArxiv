# Atari-GPT：探索多模态大型语言模型在 Atari 游戏中作为低级策略的潜力

发布时间：2024年08月28日

`LLM应用` `人工智能`

> Atari-GPT: Investigating the Capabilities of Multimodal Large Language Models as Low-Level Policies for Atari Games

# 摘要

> 大型语言模型（LLMs）的最新进展已将其能力扩展到多模态领域，整合视觉、听觉和文本数据。尽管在高级规划方面得到了广泛探索，但它们作为低级控制器的潜力仍未得到充分利用。本文探讨了多模态LLMs在Atari视频游戏领域作为低级控制器的应用，并将Atari游戏性能引入作为评估其执行低级控制任务能力的新基准。与传统RL和IL方法不同，这些LLMs利用现有多模态知识直接与游戏环境互动。我们的研究评估了多个多模态LLMs与传统RL代理、人类玩家和随机代理的性能，重点关注它们理解和与复杂视觉场景互动以及制定战略反应的能力。此外，通过加入人类演示的游戏轨迹来增强模型的上下文理解，我们考察了情境学习（ICL）的影响。通过这项调查，我们旨在确定多模态LLMs在多大程度上可以利用其广泛训练来有效发挥低级控制器的作用，从而重新定义动态和视觉复杂环境中的潜在应用。更多结果和视频可在我们的项目网页上查看：https://sites.google.com/view/atari-gpt/。

> Recent advancements in large language models (LLMs) have expanded their capabilities beyond traditional text-based tasks to multimodal domains, integrating visual, auditory, and textual data. While multimodal LLMs have been extensively explored for high-level planning in domains like robotics and games, their potential as low-level controllers remains largely untapped. This paper explores the application of multimodal LLMs as low-level controllers in the domain of Atari video games, introducing Atari game performance as a new benchmark for evaluating the ability of multimodal LLMs to perform low-level control tasks. Unlike traditional reinforcement learning (RL) and imitation learning (IL) methods that require extensive computational resources as well as reward function specification, these LLMs utilize pre-existing multimodal knowledge to directly engage with game environments. Our study assesses multiple multimodal LLMs performance against traditional RL agents, human players, and random agents, focusing on their ability to understand and interact with complex visual scenes and formulate strategic responses. Additionally, we examine the impact of In-Context Learning (ICL) by incorporating human-demonstrated game-play trajectories to enhance the models contextual understanding. Through this investigation, we aim to determine the extent to which multimodal LLMs can leverage their extensive training to effectively function as low-level controllers, thereby redefining potential applications in dynamic and visually complex environments. Additional results and videos are available at our project webpage: https://sites.google.com/view/atari-gpt/.

[Arxiv](https://arxiv.org/abs/2408.15950)