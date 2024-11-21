# 大型语言模型反馈下决策代理的在线内在奖励

发布时间：2024年10月30日

`LLM应用`

> Online Intrinsic Rewards for Decision Making Agents from Large Language Model Feedback

# 摘要

> 自动从自然语言描述中合成密集奖励在强化学习（RL）领域是一种颇具前景的范式，可应用于稀疏奖励问题、开放式探索以及分层技能设计。近期的相关工作借助大型语言模型（LLMs）的先验知识取得了不错的进展。然而，这些方法存在显著的局限性：要么难以拓展到需要数十亿环境样本的问题；要么局限于能用紧凑代码表达的奖励函数，这可能需要源代码，且难以捕捉细微语义；要么需要多样化的离线数据集，而这类数据集可能不存在或难以收集。在本研究中，我们通过算法和系统层面的贡献相结合来应对这些限制。我们提出了 ONI 这一分布式架构，它利用 LLM 反馈同时学习 RL 策略和内在奖励函数。我们的方法通过异步 LLM 服务器为代理收集的经验进行标注，然后将其提炼为内在奖励模型。我们探索了一系列不同复杂程度的奖励建模算法选择，包括哈希、分类和排序模型。通过研究它们的相对权衡，我们阐明了关于稀疏奖励问题内在奖励设计的相关问题。我们的方法在 NetHack 学习环境中的一系列颇具挑战性的稀疏奖励任务中，仅依靠代理收集的经验，以一个简单的统一流程实现了前沿性能，无需外部数据集或源代码。我们的代码将在 url{URL} 提供（即将上线）。

> Automatically synthesizing dense rewards from natural language descriptions is a promising paradigm in reinforcement learning (RL), with applications to sparse reward problems, open-ended exploration, and hierarchical skill design. Recent works have made promising steps by exploiting the prior knowledge of large language models (LLMs). However, these approaches suffer from important limitations: they are either not scalable to problems requiring billions of environment samples; or are limited to reward functions expressible by compact code, which may require source code and have difficulty capturing nuanced semantics; or require a diverse offline dataset, which may not exist or be impossible to collect. In this work, we address these limitations through a combination of algorithmic and systems-level contributions. We propose ONI, a distributed architecture that simultaneously learns an RL policy and an intrinsic reward function using LLM feedback. Our approach annotates the agent's collected experience via an asynchronous LLM server, which is then distilled into an intrinsic reward model. We explore a range of algorithmic choices for reward modeling with varying complexity, including hashing, classification, and ranking models. By studying their relative tradeoffs, we shed light on questions regarding intrinsic reward design for sparse reward problems. Our approach achieves state-of-the-art performance across a range of challenging, sparse reward tasks from the NetHack Learning Environment in a simple unified process, solely using the agent's gathered experience, without requiring external datasets nor source code. We make our code available at url{URL} (coming soon).

[Arxiv](https://arxiv.org/abs/2410.23022)