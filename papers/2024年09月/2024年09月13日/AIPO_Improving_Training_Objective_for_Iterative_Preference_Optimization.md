# AIPO：优化迭代偏好训练目标

发布时间：2024年09月13日

`LLM应用` `人工智能`

> AIPO: Improving Training Objective for Iterative Preference Optimization

# 摘要

> 偏好优化 (PO) 作为近端策略优化 (PPO) 的替代方案，正逐渐成为对齐大型语言模型 (LLM) 的热门选择。最新研究表明，通过合成或部分合成数据迭代对齐 LLM，在学术和 Llama3 等专有模型中扩展 PO 训练取得了显著成果。然而，我们的研究发现，由于迭代过程的特性，PO 中的长度利用问题在迭代偏好优化 (IPO) 中更为突出。本文探讨了使用合成数据的迭代偏好优化，分享了构建优化管道中的关键发现和分析。我们特别关注了迭代过程中的长度利用问题，并提出了共识感知迭代偏好优化 (AIPO) 的训练目标。为验证其有效性，我们在 MT-Bench、AlpacaEval 2.0 和 Arena-Hard 上进行了全面实验，并取得了领先的成绩。相关代码和模型检查点将在 https://github.com/bytedance/AIPO 上公开。

> Preference Optimization (PO), is gaining popularity as an alternative choice of Proximal Policy Optimization (PPO) for aligning Large Language Models (LLMs). Recent research on aligning LLMs iteratively with synthetic or partially synthetic data shows promising results in scaling up PO training for both academic settings and proprietary trained models such as Llama3. Despite its success, our study shows that the length exploitation issue present in PO is even more severe in Iterative Preference Optimization (IPO) due to the iterative nature of the process. In this work, we study iterative preference optimization with synthetic data. We share the findings and analysis along the way of building the iterative preference optimization pipeline. More specifically, we discuss the length exploitation issue during iterative preference optimization and propose our training objective for iterative preference optimization, namely Agreement-aware Iterative Preference Optimization (AIPO). To demonstrate the effectiveness of our method, we conduct comprehensive experiments and achieve state-of-the-art performance on MT-Bench, AlpacaEval 2.0, and Arena-Hard. Our implementation and model checkpoints will be made available at https://github.com/bytedance/AIPO.

[Arxiv](https://arxiv.org/abs/2409.08845)