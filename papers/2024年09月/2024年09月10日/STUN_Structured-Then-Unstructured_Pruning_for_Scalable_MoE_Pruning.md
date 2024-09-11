# STUN：一种先结构化后非结构化的剪枝方法，专为可扩展的 MoE 剪枝设计。

发布时间：2024年09月10日

`LLM理论` `人工智能` `云计算`

> STUN: Structured-Then-Unstructured Pruning for Scalable MoE Pruning

# 摘要

> MoEs 通过稀疏激活专家来降低 LLMs 的推理成本，但大量专家仍使其服务成本高昂。本文通过修剪 MoEs 来解决这一问题。非结构化修剪在给定比例下性能最高，因其解空间更广。然而，我们发现结构化修剪（专家修剪）能先于非结构化修剪，提升性能。现有专家修剪方法复杂度高，无法扩展。我们提出 $O(1)$ 复杂度的可扩展方案，利用专家间行为相似性，实现高效修剪。对于 480B 大小的 MoE，仅需一个 H100 和两小时，在 40% 稀疏度下几乎无性能损失，甚至在 GSM8K 等生成任务中超越最先进方法。代码将公开。

> Mixture-of-experts (MoEs) have been adopted for reducing inference costs by sparsely activating experts in Large language models (LLMs). Despite this reduction, the massive number of experts in MoEs still makes them expensive to serve. In this paper, we study how to address this, by pruning MoEs. Among pruning methodologies, unstructured pruning has been known to achieve the highest performance for a given pruning ratio, compared to structured pruning, since the latter imposes constraints on the sparsification structure. This is intuitive, as the solution space of unstructured pruning subsumes that of structured pruning. However, our counterintuitive finding reveals that expert pruning, a form of structured pruning, can actually precede unstructured pruning to outperform unstructured-only pruning. As existing expert pruning, requiring $O(\frac{k^n}{\sqrt{n}})$ forward passes for $n$ experts, cannot scale for recent MoEs, we propose a scalable alternative with $O(1)$ complexity, yet outperforming the more expensive methods. The key idea is leveraging a latent structure between experts, based on behavior similarity, such that the greedy decision of whether to prune closely captures the joint pruning effect. Ours is highly effective -- for Snowflake Arctic, a 480B-sized MoE with 128 experts, our method needs only one H100 and two hours to achieve nearly no loss in performance with 40% sparsity, even in generative tasks such as GSM8K, where state-of-the-art unstructured pruning fails to. The code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2409.06211)