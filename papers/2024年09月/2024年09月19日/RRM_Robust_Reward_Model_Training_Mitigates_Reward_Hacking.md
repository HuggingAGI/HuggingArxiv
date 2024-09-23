# RRM：通过鲁棒奖励模型训练，有效缓解奖励黑客攻击问题。

发布时间：2024年09月19日

`LLM理论` `人工智能`

> RRM: Robust Reward Model Training Mitigates Reward Hacking

# 摘要

> 奖励模型 (RMs) 在 LLMs 与人类偏好对齐中至关重要。然而，传统 RM 训练难以区分提示驱动的偏好与无关特征，如响应长度和格式。我们发现当前 RM 训练方法的一个根本局限性，即无法有效区分上下文信号和无关特征。为此，我们引入了一个因果框架，学习与这些特征无关的偏好，并提出了一种新颖的数据增强技术，以消除这些特征。实验表明，我们的方法成功过滤了不希望的特征，产生了一个更强大的奖励模型 (RRM)。RRM 在 RewardBench 上将准确率从 80.61% 提高到 84.15%。此外，使用 RRM 训练的 DPO 策略显著提升了性能，MT-Bench 分数从 7.27 提高到 8.31，AlpacaEval-2 中长度控制的胜率从 33.46% 提高到 52.49%。

> Reward models (RMs) play a pivotal role in aligning large language models (LLMs) with human preferences. However, traditional RM training, which relies on response pairs tied to specific prompts, struggles to disentangle prompt-driven preferences from prompt-independent artifacts, such as response length and format. In this work, we expose a fundamental limitation of current RM training methods, where RMs fail to effectively distinguish between contextual signals and irrelevant artifacts when determining preferences. To address this, we introduce a causal framework that learns preferences independent of these artifacts and propose a novel data augmentation technique designed to eliminate them. Extensive experiments show that our approach successfully filters out undesirable artifacts, yielding a more robust reward model (RRM). Our RRM improves the performance of a pairwise reward model trained on Gemma-2-9b-it, on RewardBench, increasing accuracy from 80.61% to 84.15%. Additionally, we train two DPO policies using both the RM and RRM, demonstrating that the RRM significantly enhances DPO-aligned policies, improving MT-Bench scores from 7.27 to 8.31 and length-controlled win-rates in AlpacaEval-2 from 33.46% to 52.49%.

[Arxiv](https://arxiv.org/abs/2409.13156)