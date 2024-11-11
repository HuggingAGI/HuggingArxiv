# 通过分层表示学习实现鲁棒的不完整多模态情感分析

发布时间：2024年11月04日

`其他` `情感分析` `多模态`

> Toward Robust Incomplete Multimodal Sentiment Analysis via Hierarchical Representation Learning

# 摘要

> 多模态情感分析（MSA）是一个重要的研究领域，旨在通过多种模态来理解和识别人类情感。多模态融合提供的互补信息与仅使用单一模态相比，促进了更好的情感分析。然而，在现实世界的应用中，许多不可避免的因素可能导致不确定模态缺失的情况，从而阻碍多模态建模的有效性并降低模型的性能。为此，我们为不确定缺失模态下的 MSA 任务提出了一个分层表示学习框架（HRLF）。具体来说，我们提出了一个细粒度的表示分解模块，通过跨模态翻译和情感语义重建将模态分解为与情感相关和模态特定的表示，充分提取有价值的情感信息。此外，引入了分层互信息最大化机制，以逐步最大化多尺度表示之间的互信息，从而对齐和重建表示中的高级语义。最终，我们提出了一个分层对抗学习机制，进一步对齐和适应与情感相关表示的潜在分布，以产生强大的联合多模态表示。在三个数据集上的综合实验表明，HRLF 在不确定模态缺失的情况下显著提高了 MSA 性能。

> Multimodal Sentiment Analysis (MSA) is an important research area that aims to understand and recognize human sentiment through multiple modalities. The complementary information provided by multimodal fusion promotes better sentiment analysis compared to utilizing only a single modality. Nevertheless, in real-world applications, many unavoidable factors may lead to situations of uncertain modality missing, thus hindering the effectiveness of multimodal modeling and degrading the model's performance. To this end, we propose a Hierarchical Representation Learning Framework (HRLF) for the MSA task under uncertain missing modalities. Specifically, we propose a fine-grained representation factorization module that sufficiently extracts valuable sentiment information by factorizing modality into sentiment-relevant and modality-specific representations through crossmodal translation and sentiment semantic reconstruction. Moreover, a hierarchical mutual information maximization mechanism is introduced to incrementally maximize the mutual information between multi-scale representations to align and reconstruct the high-level semantics in the representations. Ultimately, we propose a hierarchical adversarial learning mechanism that further aligns and adapts the latent distribution of sentiment-relevant representations to produce robust joint multimodal representations. Comprehensive experiments on three datasets demonstrate that HRLF significantly improves MSA performance under uncertain modality missing cases.

[Arxiv](https://arxiv.org/abs/2411.02793)