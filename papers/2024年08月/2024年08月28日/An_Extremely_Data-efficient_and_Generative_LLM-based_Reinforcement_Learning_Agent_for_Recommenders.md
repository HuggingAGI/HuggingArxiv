# 一款数据高效且生成能力强的基于LLM的强化学习推荐代理

发布时间：2024年08月28日

`Agent` `电子商务` `人工智能`

> An Extremely Data-efficient and Generative LLM-based Reinforcement Learning Agent for Recommenders

# 摘要

> 大型语言模型的进步使得理解网页内容、产品详情和人类指令成为可能。LLM 在强化学习中的应用，如 InstructGPT 的成功，显示了其在奖励模型或策略中的潜力。本项目在 WebShop 环境中评估了多种 RL 方法，旨在通过详细的人类指令训练代理以最大化购买奖励。通过微调 BERT 模型、采用 PPO 和 DPO 等技术，代理在模拟实验中表现出色，证明了低成本、高效率的训练方法。在有限时间内，DPO 代理在无图像情况下，通过短时间训练达到了较高的成功率。

> Recent advancements in large language models (LLMs) have enabled understanding webpage contexts, product details, and human instructions. Utilizing LLMs as the foundational architecture for either reward models or policies in reinforcement learning has gained popularity -- a notable achievement is the success of InstructGPT. RL algorithms have been instrumental in maximizing long-term customer satisfaction and avoiding short-term, myopic goals in industrial recommender systems, which often rely on deep learning models to predict immediate clicks or purchases.
  In this project, several RL methods are implemented and evaluated using the WebShop benchmark environment, data, simulator, and pre-trained model checkpoints. The goal is to train an RL agent to maximize the purchase reward given a detailed human instruction describing a desired product. The RL agents are developed by fine-tuning a pre-trained BERT model with various objectives, learning from preferences without a reward model, and employing contemporary training techniques such as Proximal Policy Optimization (PPO) as used in InstructGPT, and Direct Preference Optimization (DPO). This report also evaluates the RL agents trained using generative trajectories. Evaluations were conducted using Thompson sampling in the WebShop simulator environment.
  The simulated online experiments demonstrate that agents trained on generated trajectories exhibited comparable task performance to those trained using human trajectories. This has demonstrated an example of an extremely low-cost data-efficient way of training reinforcement learning agents. Also, with limited training time (<2hours), without utilizing any images, a DPO agent achieved a 19% success rate after approximately 3000 steps or 30 minutes of training on T4 GPUs, compared to a PPO agent, which reached a 15% success rate.

[Arxiv](https://arxiv.org/abs/2408.16032)