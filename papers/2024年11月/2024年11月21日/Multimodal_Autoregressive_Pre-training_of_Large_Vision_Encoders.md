# 大型视觉编码器的多模态自回归预训练

发布时间：2024年11月21日

`其他` `多模态`

> Multimodal Autoregressive Pre-training of Large Vision Encoders

# 摘要

> 我们带来了一种用于大规模视觉编码器预训练的全新方法。以视觉模型自回归预训练的最新成果为基础，将此框架拓展到多模态领域，也就是图像和文本。在本文里，我们推出了 AIMV2，这是一组通用视觉编码器，具有预训练流程简便、可扩展性佳以及在众多下游任务中表现出众等特性。这通过为视觉编码器搭配一个能自回归生成原始图像块和文本标记的多模态解码器得以实现。我们的编码器不但在多模态评估里表现卓越，在诸如定位、基础和分类等视觉基准测试中也成绩斐然。特别值得一提的是，我们的 AIMV2-3B 编码器在冻结主干的情况下，于 ImageNet-1k 上达到了 89.5％的准确率。此外，AIMV2 在各种不同设置下的多模态图像理解中，始终胜过最先进的对比模型（比如 CLIP、SigLIP）。

> We introduce a novel method for pre-training of large-scale vision encoders. Building on recent advancements in autoregressive pre-training of vision models, we extend this framework to a multimodal setting, i.e., images and text. In this paper, we present AIMV2, a family of generalist vision encoders characterized by a straightforward pre-training process, scalability, and remarkable performance across a range of downstream tasks. This is achieved by pairing the vision encoder with a multimodal decoder that autoregressively generates raw image patches and text tokens. Our encoders excel not only in multimodal evaluations but also in vision benchmarks such as localization, grounding, and classification. Notably, our AIMV2-3B encoder achieves 89.5% accuracy on ImageNet-1k with a frozen trunk. Furthermore, AIMV2 consistently outperforms state-of-the-art contrastive models (e.g., CLIP, SigLIP) in multimodal image understanding across diverse settings.

[Arxiv](https://arxiv.org/abs/2411.14402)