# 探索视觉-语言模型中的跨模态后向兼容表示学习

发布时间：2024年05月23日

`RAG

理由：这篇论文主要关注的是跨模态检索系统中的后向兼容性问题，特别是如何确保新旧模型嵌入的一致性。通过引入跨模态后向兼容训练（XBT），论文提出了一种新的方法来解决这一问题，即通过设计一个投影模块来实现新模型嵌入与旧模型嵌入的兼容。这种方法特别适用于视觉语言预训练模型（如CLIP）在跨模态检索中的应用。因此，这篇论文更符合RAG分类，因为它涉及的是检索增强生成（Retrieval-Augmented Generation）领域的技术，即如何增强检索系统的兼容性和效率。` `跨模态检索` `视觉语言预训练`

> Towards Cross-modal Backward-compatible Representation Learning for Vision-Language Models

# 摘要

> 现代检索系统升级时，常因新旧模型嵌入不兼容而陷入困境，需进行昂贵的回填操作，即重新计算大量数据嵌入。视觉领域已提出后向兼容训练（BT）以确保新旧模型嵌入一致。本文首次将BT概念扩展至跨模态检索，探索跨模态BT（XBT）。我们旨在实现视觉语言预训练模型（如CLIP）在跨模态检索中的后向兼容。为此，我们设计了一个高效的投影模块，将新模型嵌入映射至旧模型，该模块仅用文本数据预训练，大幅减少所需图像-文本对，且预训练后无需旧模型参与。我们还采用了参数高效的训练策略，保持新模型原有知识，避免任何改动。实验证明，XBT在跨模态检索数据集上表现出色，为未来VLP模型升级提供了无回填的可能。

> Modern retrieval systems often struggle with upgrading to new and more powerful models due to the incompatibility of embeddings between the old and new models. This necessitates a costly process known as backfilling, which involves re-computing the embeddings for a large number of data samples. In vision, Backward-compatible Training (BT) has been proposed to ensure that the new model aligns with the old model's embeddings. This paper extends the concept of vision-only BT to the field of cross-modal retrieval, marking the first attempt to address Cross-modal BT (XBT). Our goal is to achieve backward-compatibility between Vision-Language Pretraining (VLP) models, such as CLIP, for the cross-modal retrieval task. To address XBT challenges, we propose an efficient solution: a projection module that maps the new model's embeddings to those of the old model. This module, pretrained solely with text data, significantly reduces the number of image-text pairs required for XBT learning, and, once it is pretrained, it avoids using the old model during training. Furthermore, we utilize parameter-efficient training strategies that improve efficiency and preserve the off-the-shelf new model's knowledge by avoiding any modifications. Experimental results on cross-modal retrieval datasets demonstrate the effectiveness of XBT and its potential to enable backfill-free upgrades when a new VLP model emerges.

[Arxiv](https://arxiv.org/abs/2405.14715)