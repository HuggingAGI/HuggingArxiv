# DySpec：借助动态令牌树结构，实现更快的推测解码

发布时间：2024年10月15日

`LLM理论` `人工智能` `高性能计算`

> DySpec: Faster Speculative Decoding with Dynamic Token Tree Structure

# 摘要

> 尽管推测性解码近期被视为加速 LLM 推理的潜力方向，但其加速与扩展性受限于令牌接受率。现有方法常将预测令牌组织为独立链或固定树，难以适应多样查询分布。本文提出 DySpec，一种采用动态令牌树结构的新型推测解码算法。我们首先通过直观与经验线索，揭示草稿分布与接受率的强相关性。基于此，我们采用贪婪策略，在运行时动态扩展令牌树。理论上，在温和假设下，DySpec 可实现最优结果。实践中，DySpec 的接受率与加速效果优于固定树。DySpec 在各种数据分布与模型大小下，显著提升令牌生成吞吐量并减少延迟，超越了 Specinfer 和 Sequoia 等强劲对手。在低温设置下，DySpec 在 Llama2-70B 上可将吞吐量提升至 9.1 倍，延迟降至 9.4 倍。即使在高温设置下，DySpec 仍能将吞吐量提升至 6.21 倍，尽管每步推测多个令牌的难度增加。

> While speculative decoding has recently appeared as a promising direction for accelerating the inference of large language models (LLMs), the speedup and scalability are strongly bounded by the token acceptance rate. Prevalent methods usually organize predicted tokens as independent chains or fixed token trees, which fails to generalize to diverse query distributions. In this paper, we propose DySpec, a faster speculative decoding algorithm with a novel dynamic token tree structure. We begin by bridging the draft distribution and acceptance rate from intuitive and empirical clues, and successfully show that the two variables are strongly correlated. Based on this, we employ a greedy strategy to dynamically expand the token tree at run time. Theoretically, we show that our method can achieve optimal results under mild assumptions. Empirically, DySpec yields a higher acceptance rate and speedup than fixed trees. DySpec can drastically improve the throughput and reduce the latency of token generation across various data distribution and model sizes, which significantly outperforms strong competitors, including Specinfer and Sequoia. Under low temperature setting, DySpec can improve the throughput up to 9.1$\times$ and reduce the latency up to 9.4$\times$ on Llama2-70B. Under high temperature setting, DySpec can also improve the throughput up to 6.21$\times$, despite the increasing difficulty of speculating more than one token per step for draft model.

[Arxiv](https://arxiv.org/abs/2410.11744)