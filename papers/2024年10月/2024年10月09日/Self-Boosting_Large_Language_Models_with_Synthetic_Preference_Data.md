# 通过合成偏好数据，大型语言模型实现自我提升

发布时间：2024年10月09日

`LLM应用` `人工智能`

> Self-Boosting Large Language Models with Synthetic Preference Data

# 摘要

> 通过与人类偏好对齐，LLM 在生成诚实、无害且有帮助的响应方面取得了显著进展。然而，收集高质量的偏好数据既耗资源又需创造力，尤其是在 LLM 的持续改进中。为此，我们推出了 SynPO，一种利用合成偏好数据进行模型对齐的自增强范式。SynPO 通过迭代机制，让自提示生成器创造多样化的提示，并由响应改进器逐步优化模型响应。这种方法使 LLM 能够自主学习其输出的生成奖励，无需大规模的提示和人类偏好注释。经过四次迭代，Llama3-8B 和 Mistral-7B 在指令遵循能力上显著提升，胜率在 AlpacaEval 2.0 和 ArenaHard 上提高了 22.1% 以上。同时，SynPO 还提升了 LLM 在各类任务上的整体表现，Open LLM 排行榜上的平均得分增加了 3.2 到 5.0。

> Through alignment with human preferences, Large Language Models (LLMs) have advanced significantly in generating honest, harmless, and helpful responses. However, collecting high-quality preference data is a resource-intensive and creativity-demanding process, especially for the continual improvement of LLMs. We introduce SynPO, a self-boosting paradigm that leverages synthetic preference data for model alignment. SynPO employs an iterative mechanism wherein a self-prompt generator creates diverse prompts, and a response improver refines model responses progressively. This approach trains LLMs to autonomously learn the generative rewards for their own outputs and eliminates the need for large-scale annotation of prompts and human preferences. After four SynPO iterations, Llama3-8B and Mistral-7B show significant enhancements in instruction-following abilities, achieving over 22.1% win rate improvements on AlpacaEval 2.0 and ArenaHard. Simultaneously, SynPO improves the general performance of LLMs on various tasks, validated by a 3.2 to 5.0 average score increase on the well-recognized Open LLM leaderboard.

[Arxiv](https://arxiv.org/abs/2410.06961)