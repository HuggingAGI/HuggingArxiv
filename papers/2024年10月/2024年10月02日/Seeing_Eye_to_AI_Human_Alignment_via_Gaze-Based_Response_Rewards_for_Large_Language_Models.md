# 眼对AI：通过注视响应奖励实现大型语言模型的人类对齐

发布时间：2024年10月02日

`LLM应用` `人工智能`

> Seeing Eye to AI: Human Alignment via Gaze-Based Response Rewards for Large Language Models

# 摘要

> NLP 的进步催生了 GPT、Llama 等 LLM，它们在多任务中表现优异，但需大量微调以符合人类期望。RLHF 是实现对齐的常用方法，但在准确建模人类偏好上存在挑战。本文提出 GazeReward，一种将眼动追踪数据融入奖励模型的新框架，并探讨了其对用户偏好的洞察力。通过消融研究，我们验证了该框架在不同 LLM 和 ET 模型中的有效性，显著提升了 RM 的准确性。这项研究不仅优化了 AI 与人类价值观的对齐，还为未来 NLP 研究开辟了新路径。

> Advancements in Natural Language Processing (NLP), have led to the emergence of Large Language Models (LLMs) such as GPT, Llama, Claude, and Gemini, which excel across a range of tasks but require extensive fine-tuning to align their outputs with human expectations. A widely used method for achieving this alignment is Reinforcement Learning from Human Feedback (RLHF), which, despite its success, faces challenges in accurately modelling human preferences. In this paper, we introduce GazeReward, a novel framework that integrates implicit feedback -- and specifically eye-tracking (ET) data -- into the Reward Model (RM). In addition, we explore how ET-based features can provide insights into user preferences. Through ablation studies we test our framework with different integration methods, LLMs, and ET generator models, demonstrating that our approach significantly improves the accuracy of the RM on established human preference datasets. This work advances the ongoing discussion on optimizing AI alignment with human values, exploring the potential of cognitive data for shaping future NLP research.

[Arxiv](https://arxiv.org/abs/2410.01532)