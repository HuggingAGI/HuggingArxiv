# 定向偏好优化中的长度不敏感性

发布时间：2024年09月10日

`LLM理论` `人工智能`

> Length Desensitization in Directed Preference Optimization

# 摘要

> 直接偏好优化 (DPO) 在 RLHF 阶段广泛用于对齐 LLM 与人类偏好，提升其无害性和有效性。然而，DPO 倾向于过度优化冗长性，影响性能和用户体验。本文深入分析 DPO 的优化目标，揭示其隐含奖励与数据长度的强相关性，误导优化方向，导致训练中的长度敏感性和冗长性。为此，我们提出 LD-DPO，通过解耦显式长度偏好，使 DPO 对数据长度去敏感，更有效学习内在偏好。实验使用 Llama2-13B、Llama3-8B 和 Qwen2-7B 在 MT-Bench 和 AlpacaEval 2 等基准上验证，结果显示 LD-DPO 始终优于 DPO 和其他基线方法，响应更简洁，长度减少 10-40\%。深入分析证明 LD-DPO 实现长度去敏感化，更贴近人类真实偏好。

> Direct Preference Optimization (DPO) is widely utilized in the Reinforcement Learning from Human Feedback (RLHF) phase to align Large Language Models (LLMs) with human preferences, thereby enhancing both their harmlessness and efficacy. However, it has been observed that DPO tends to over-optimize for verbosity, which can detrimentally affect both performance and user experience. In this paper, we conduct an in-depth theoretical analysis of DPO's optimization objective and reveal a strong correlation between its implicit reward and data length. This correlation misguides the optimization direction, resulting in length sensitivity during the DPO training and leading to verbosity. To address this issue, we propose a length-desensitization improvement method for DPO, termed LD-DPO. The proposed method aims to desensitize DPO to data length by decoupling explicit length preference, which is relatively insignificant, from the other implicit preferences, thereby enabling more effective learning of the intrinsic preferences. We utilized two settings (Base and Instruct) of Llama2-13B, Llama3-8B, and Qwen2-7B for experimental validation on various benchmarks including MT-Bench and AlpacaEval 2. The experimental results indicate that LD-DPO consistently outperforms DPO and other baseline methods, achieving more concise responses with a 10-40\% reduction in length compared to DPO. We conducted in-depth experimental analyses to demonstrate that LD-DPO can indeed achieve length desensitization and align the model more closely with human-real preferences.

[Arxiv](https://arxiv.org/abs/2409.06411)