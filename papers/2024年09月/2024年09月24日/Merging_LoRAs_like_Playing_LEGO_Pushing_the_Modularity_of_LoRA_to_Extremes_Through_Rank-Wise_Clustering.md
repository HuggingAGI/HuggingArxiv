# 合并 LoRA 如同玩乐高积木，通过秩聚类将 LoRA 的模块化发挥到极致。

发布时间：2024年09月24日

`LLM理论` `人工智能` `软件工程`

> Merging LoRAs like Playing LEGO: Pushing the Modularity of LoRA to Extremes Through Rank-Wise Clustering

# 摘要

> LoRA 因其模块化设计和广泛的平台支持，成为微调 LLM 的热门技术。然而，现有方法在组合 LoRA 时，常因未能充分利用其模块化特性，导致性能下降。本文探讨了在更细粒度上拆解和重组 LoRA 的可行性，如同组装乐高积木。我们提出最小语义单元 (MSU) 概念，使 LoRA 参数能灵活组合。基于此，我们设计了 LoRA-LEGO 框架，通过秩参数聚类和双重加权策略，优化合并 LoRA 的性能。实验证明，该方法在 LoRA 合并中表现优异。

> Low-Rank Adaptation (LoRA) has emerged as a popular technique for fine-tuning large language models (LLMs) to various domains due to its modular design and widespread availability on platforms like Huggingface. This modularity has sparked interest in combining multiple LoRAs to enhance LLM capabilities. However, existing methods for LoRA composition primarily focus on task-specific adaptations that require additional training, and current model merging techniques often fail to fully leverage LoRA's modular nature, leading to parameter interference and performance degradation. In this paper, we investigate the feasibility of disassembling and reassembling multiple LoRAs at a finer granularity, analogous to assembling LEGO blocks. We introduce the concept of Minimal Semantic Units (MSUs), where the parameters corresponding to each rank in LoRA function as independent units. These MSUs demonstrate permutation invariance and concatenation-summation equivalence properties, enabling flexible combinations to create new LoRAs. Building on these insights, we propose the LoRA-LEGO framework. This framework conducts rank-wise parameter clustering by grouping MSUs from different LoRAs into $k$ clusters. The centroid of each cluster serves as a representative MSU, enabling the assembly of a merged LoRA with an adjusted rank of $k$. Additionally, we apply a dual reweighting strategy to optimize the scale of the merged LoRA. Experiments across various benchmarks demonstrate that our method outperforms existing approaches in LoRA merging.

[Arxiv](https://arxiv.org/abs/2409.16167)