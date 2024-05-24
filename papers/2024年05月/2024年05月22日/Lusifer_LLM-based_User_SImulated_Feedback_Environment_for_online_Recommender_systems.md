# Lusifer：大型语言模型驱动的用户模拟反馈环境，专为在线推荐系统设计

发布时间：2024年05月22日

`Agent

理由：这篇论文介绍了一个名为 Lusifer 的环境，它利用大型语言模型（LLMs）来模拟用户反馈，以解决基于强化学习的推荐系统在训练时缺乏动态和真实用户交互的问题。Lusifer 通过整合用户档案和交互历史来模拟用户对推荐项目的反应和行为，并且能够更新用户档案以反映用户特征的动态变化。这个环境可以被视为一个智能代理（Agent），因为它能够模拟用户行为并与之交互，从而在推荐系统中起到关键作用。因此，这篇论文更适合归类为Agent。` `推荐系统` `用户模拟`

> Lusifer: LLM-based User SImulated Feedback Environment for online Recommender systems

# 摘要

> 基于强化学习的推荐系统在训练时往往因缺乏动态和真实的用户交互而受阻。Lusifer，这一新颖的环境，借助大型语言模型（LLMs）的力量，通过模拟用户反馈巧妙地克服了这一难题。它通过整合用户档案和交互历史，精准模拟用户对推荐项目的反应和行为，并且每次评分后都会更新用户档案，以捕捉用户特征的动态变化。以MovieLens100K数据集为实验基础，Lusifer成功展示了其对用户行为和偏好的精准模拟。本文详细阐述了Lusifer的工作流程，涵盖了提示生成和用户档案的迭代更新。未来，Lusifer不仅能够验证其生成真实动态反馈的能力，还可作为训练强化学习系统的理想环境，为在线推荐系统中的用户模拟提供一个既可扩展又可调节的框架。

> Training reinforcement learning-based recommender systems are often hindered by the lack of dynamic and realistic user interactions. Lusifer, a novel environment leveraging Large Language Models (LLMs), addresses this limitation by generating simulated user feedback. It synthesizes user profiles and interaction histories to simulate responses and behaviors toward recommended items. In addition, user profiles are updated after each rating to reflect evolving user characteristics. Using the MovieLens100K dataset as proof of concept, Lusifer demonstrates accurate emulation of user behavior and preferences. This paper presents Lusifer's operational pipeline, including prompt generation and iterative user profile updates. While validating Lusifer's ability to produce realistic dynamic feedback, future research could utilize this environment to train reinforcement learning systems, offering a scalable and adjustable framework for user simulation in online recommender systems.

[Arxiv](https://arxiv.org/abs/2405.13362)