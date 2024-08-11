# Transformer 模型，作为通用上下文学习者，展现了其广泛适应性。

发布时间：2024年08月02日

`LLM理论` `人工智能`

> Transformers are Universal In-context Learners

# 摘要

> 摘要：Transformer 架构通过定义“上下文映射”，能基于一组给定令牌预测新令牌。本研究聚焦于其处理海量上下文令牌的能力。我们通过令牌的概率分布来条件化映射，以数学统一地探讨其表达力。平滑性对应于上下文间 Wasserstein 距离的连续性。我们证实，深度 Transformer 能以任意精度，均匀地在紧凑令牌域上逼近连续上下文映射。关键在于，固定精度下，单个 Transformer 可处理任意数量令牌，且在固定嵌入维度和头数下运行，多头注意力层间的 MLP 层使用也受控。

> 
Abstract:Transformers are deep architectures that define "in-context mappings" which enable predicting new tokens based on a given set of tokens (such as a prompt in NLP applications or a set of patches for vision transformers). This work studies in particular the ability of these architectures to handle an arbitrarily large number of context tokens. To mathematically and uniformly address the expressivity of these architectures, we consider the case that the mappings are conditioned on a context represented by a probability distribution of tokens (discrete for a finite number of tokens). The related notion of smoothness corresponds to continuity in terms of the Wasserstein distance between these contexts. We demonstrate that deep transformers are universal and can approximate continuous in-context mappings to arbitrary precision, uniformly over compact token domains. A key aspect of our results, compared to existing findings, is that for a fixed precision, a single transformer can operate on an arbitrary (even infinite) number of tokens. Additionally, it operates with a fixed embedding dimension of tokens (this dimension does not increase with precision) and a fixed number of heads (proportional to the dimension). The use of MLP layers between multi-head attention layers is also explicitly controlled.
    

[Arxiv](https://arxiv.org/pdf/2408.01367)