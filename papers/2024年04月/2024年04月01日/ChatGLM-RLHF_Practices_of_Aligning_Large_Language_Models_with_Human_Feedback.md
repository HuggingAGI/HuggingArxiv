# ChatGLM-RLHF：探索大型语言模型与人类反馈融合的实践之道

发布时间：2024年04月01日

`LLM应用` `人工智能` `对话系统`

> ChatGLM-RLHF: Practices of Aligning Large Language Models with Human Feedback

# 摘要

> ChatGLM，一款基于 ChatGLM 系列大型语言模型的免费 AI 服务，通过本文介绍的 ChatGLM-RLHF 流程，即基于人类反馈的强化学习系统，进一步提升了与人类偏好的契合度。该流程涵盖三大核心环节：搜集人类偏好数据、奖励模型训练和策略优化。在 ChatGLM-RLHF 融入生产环节的过程中，我们面临并克服了众多前所未遇的挑战。我们采取了多种策略，包括减少奖励差异以实现大规模训练的稳定性、采用融合梯度下降技术的模型并行化，以及制定正则化约束防止 LLMs 发生灾难性遗忘。实验结果显示，ChatGLM-RLHF 在对齐任务上的表现显著优于 ChatGLM 的监督微调版本，如在中文对齐任务中平均胜率高出 15%。本研究不仅分享了我们让 LLMs 与人类偏好对齐的实践经验，还深入探讨了 RLHF 实施过程中的挑战与应对之道。

> ChatGLM is a free-to-use AI service powered by the ChatGLM family of large language models (LLMs). In this paper, we present the ChatGLM-RLHF pipeline -- a reinforcement learning from human feedback (RLHF) system -- designed to enhance ChatGLM's alignment with human preferences. ChatGLM-RLHF encompasses three major components: the collection of human preference data, the training of the reward model, and the optimization of policies. Throughout the process of integrating ChatGLM-RLHF into production, we encountered and addressed several unprecedented challenges. We introduce the strategies to mitigate reward variance for stabilized large-scale training, implement model parallelism with fused gradient-descent, and design regularization constraints to avoid catastrophic forgetting in LLMs. Experiments show that ChatGLM-RLHF brings significant improvements in alignment tasks compared to the supervised fine-tuned (SFT) version of ChatGLM. For instance, it achieves on average 15\% more wins against ChatGLM-SFT in Chinese alignment tasks. The work presents our practices of aligning LLMs with human preferences, offering insights into the challenges and solutions in RLHF implementations.

[Arxiv](https://arxiv.org/abs/2404.00934)