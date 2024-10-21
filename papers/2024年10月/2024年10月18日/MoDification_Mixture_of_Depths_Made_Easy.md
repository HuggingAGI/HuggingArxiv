# MoDification：深度混合轻松实现

发布时间：2024年10月18日

`LLM应用` `人工智能` `云计算`

> MoDification: Mixture of Depths Made Easy

# 摘要

> 长上下文效率在 LLM 服务中备受关注，混合深度 (MoD) 被视为降低延迟和内存的理想方案。然而，我们发现 MoD 难以在不经过大量标记的昂贵训练的情况下转换现有 LLM。为此，我们提出将 MoD 中的 top-k 操作符提升为阈值-p 操作符，并对架构和数据进行改进，形成名为 MoDification 的方法。通过从 3B 到 70B 模型规模的实验，MoDification 在效率和有效性之间取得了极佳平衡，尤其在长上下文应用中，延迟加速达 ~1.2 倍，内存减少达 ~1.8 倍。

> Long-context efficiency has recently become a trending topic in serving large language models (LLMs). And mixture of depths (MoD) is proposed as a perfect fit to bring down both latency and memory. In this paper, however, we discover that MoD can barely transform existing LLMs without costly training over an extensive number of tokens. To enable the transformations from any LLMs to MoD ones, we showcase top-k operator in MoD should be promoted to threshold-p operator, and refinement to architecture and data should also be crafted along. All these designs form our method termed MoDification. Through a comprehensive set of experiments covering model scales from 3B to 70B, we exhibit MoDification strikes an excellent balance between efficiency and effectiveness. MoDification can achieve up to ~1.2x speedup in latency and ~1.8x reduction in memory compared to original LLMs especially in long-context applications.

[Arxiv](https://arxiv.org/abs/2410.14268)