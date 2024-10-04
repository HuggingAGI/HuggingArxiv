# 双主动学习：从人类反馈中强化学习的新路径

发布时间：2024年10月03日

`LLM理论` `人工智能` `生成式人工智能`

> Dual Active Learning for Reinforcement Learning from Human Feedback

# 摘要

> 将大型语言模型与人类偏好对齐是生成式人工智能进步的关键。我们采用离线强化学习，提出了一种双重主动奖励学习算法，以高效选择对话和教师，并应用悲观 RL 解决对齐问题。理论证明，我们的方法在样本预算下实现了最优性能。实验结果表明，我们的算法优于现有技术，为生成式人工智能的发展提供了有力支持。

> Aligning large language models (LLMs) with human preferences is critical to recent advances in generative artificial intelligence. Reinforcement learning from human feedback (RLHF) is widely applied to achieve this objective. A key step in RLHF is to learn the reward function from human feedback. However, human feedback is costly and time-consuming, making it essential to collect high-quality conversation data for human teachers to label. Additionally, different human teachers have different levels of expertise. It is thus critical to query the most appropriate teacher for their opinions. In this paper, we use offline reinforcement learning (RL) to formulate the alignment problem. Motivated by the idea of $D$-optimal design, we first propose a dual active reward learning algorithm for the simultaneous selection of conversations and teachers. Next, we apply pessimistic RL to solve the alignment problem, based on the learned reward estimator. Theoretically, we show that the reward estimator obtained through our proposed adaptive selection strategy achieves minimal generalized variance asymptotically, and prove that the sub-optimality of our pessimistic policy scales as $O(1/\sqrt{T})$ with a given sample budget $T$. Through simulations and experiments on LLMs, we demonstrate the effectiveness of our algorithm and its superiority over state-of-the-arts.

[Arxiv](https://arxiv.org/abs/2410.02504)