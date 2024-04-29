# 本文介绍了一种新颖的方法，即通过扭曲的顺序蒙特卡洛（Twisted Sequential Monte Carlo）技术，来增强语言模型中的概率推断能力。

发布时间：2024年04月26日

`分类：LLM理论` `人工智能`

> Probabilistic Inference in Language Models via Twisted Sequential Monte Carlo

# 摘要

> 大型语言模型（LLMs）的多项能力和安全技术，如RLHF、自动化红队对抗、提示设计和填充技术，本质上是从由奖励或潜能函数定义的未归一化目标分布中进行抽样。本研究中，我们采用了序列蒙特卡洛（SMC）方法来解决这些概率推断难题。我们特别利用学习到的扭曲函数来预测每个时间点潜能的期望未来值，从而将推断计算的重点放在有潜力的部分序列上。我们提出了一种创新的对比学习方法来训练这些扭曲函数，并与软强化学习领域的丰富文献建立了联系。此外，我们还展示了一种评估语言模型推断精度的新方法，即利用双向SMC界限来估计对数划分函数，进而计算推断分布与目标分布之间的KL散度。我们应用这些推断评估技术，证明了扭曲SMC在从预训练模型中抽取不良输出、生成情感多样的评论以及执行填充任务方面的有效性。

> Numerous capability and safety techniques of Large Language Models (LLMs), including RLHF, automated red-teaming, prompt engineering, and infilling, can be cast as sampling from an unnormalized target distribution defined by a given reward or potential function over the full sequence. In this work, we leverage the rich toolkit of Sequential Monte Carlo (SMC) for these probabilistic inference problems. In particular, we use learned twist functions to estimate the expected future value of the potential at each timestep, which enables us to focus inference-time computation on promising partial sequences. We propose a novel contrastive method for learning the twist functions, and establish connections with the rich literature of soft reinforcement learning. As a complementary application of our twisted SMC framework, we present methods for evaluating the accuracy of language model inference techniques using novel bidirectional SMC bounds on the log partition function. These bounds can be used to estimate the KL divergence between the inference and target distributions in both directions. We apply our inference evaluation techniques to show that twisted SMC is effective for sampling undesirable outputs from a pretrained model (a useful component of harmlessness training and automated red-teaming), generating reviews with varied sentiment, and performing infilling tasks.

[Arxiv](https://arxiv.org/abs/2404.17546)