# 本研究深入探讨了状态空间模型与先进训练技术在序列推荐领域的应用，通过比较分析，揭示了其在效率与性能方面的表现。

发布时间：2024年08月10日

`LLM应用` `电子商务` `人工智能`

> Exploring Applications of State Space Models and Advanced Training Techniques in Sequential Recommendations: A Comparative Study on Efficiency and Performance

# 摘要

> 推荐系统致力于捕捉用户偏好的动态变化及历史行为与元数据间的顺序依赖。基于Transformer的模型虽在顺序推荐中表现出色，但其状态增长与序列长度成正比，导致内存和推理成本高昂。我们探索了三个创新方向：利用状态空间模型（SSM）提升速度，实现低成本的SOTA结果；通过单体偏好优化无参考模型（ORPO）结合大型语言模型（LLMs）提升推荐质量；以及采用自适应算法降低成本，加速训练进程。

> Recommender systems aim to estimate the dynamically changing user preferences and sequential dependencies between historical user behaviour and metadata. Although transformer-based models have proven to be effective in sequential recommendations, their state growth is proportional to the length of the sequence that is being processed, which makes them expensive in terms of memory and inference costs. Our research focused on three promising directions in sequential recommendations: enhancing speed through the use of State Space Models (SSM), as they can achieve SOTA results in the sequential recommendations domain with lower latency, memory, and inference costs, as proposed by arXiv:2403.03900 improving the quality of recommendations with Large Language Models (LLMs) via Monolithic Preference Optimization without Reference Model (ORPO); and implementing adaptive batch- and step-size algorithms to reduce costs and accelerate training processes.

[Arxiv](https://arxiv.org/abs/2408.05606)