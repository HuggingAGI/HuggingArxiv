# 提升 LLM 代理代码生成：可能性与通过率优先的经验回放策略

发布时间：2024年10月16日

`LLM应用` `软件开发` `人工智能`

> Enhancing LLM Agents for Code Generation with Possibility and Pass-rate Prioritized Experience Replay

# 摘要

> 在代码生成任务中，基于Transformer的LLM通常采用采样和过滤流程。然而，由于单个token错误导致的稀疏奖励问题，模型会不断生成冗余程序，效率低下。为解决这一问题，我们在微调阶段引入了经验回放（ER），存储并回放生成的代码，让LLM从过去经验中学习。我们还提出了BTP管道，包括束搜索采样、测试和优先经验回放三个阶段，利用失败程序并回放高P2Value的程序，以提高效率。P2Value综合考虑了输出可能性和通过率，有效利用了LLM收集的冗余资源。实证结果显示，我们的方法显著提升了LLM在代码生成任务中的性能，超越了现有基线。

> Nowadays transformer-based Large Language Models (LLM) for code generation tasks usually apply sampling and filtering pipelines. Due to the sparse reward problem in code generation tasks caused by one-token incorrectness, transformer-based models will sample redundant programs till they find a correct one, leading to low efficiency. To overcome the challenge, we incorporate Experience Replay (ER) in the fine-tuning phase, where codes and programs produced are stored and will be replayed to give the LLM agent a chance to learn from past experiences. Based on the spirit of ER, we introduce a novel approach called BTP pipeline which consists of three phases: beam search sampling, testing phase, and prioritized experience replay phase. The approach makes use of failed programs collected by code models and replays programs with high Possibility and Pass-rate Prioritized value (P2Value) from the replay buffer to improve efficiency. P2Value comprehensively considers the possibility of transformers' output and pass rate and can make use of the redundant resources caused by the problem that most programs collected by LLMs fail to pass any tests. We empirically apply our approach in several LLMs, demonstrating that it enhances their performance in code generation tasks and surpasses existing baselines.

[Arxiv](https://arxiv.org/abs/2410.12236)