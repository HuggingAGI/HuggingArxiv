# 优化 CLIP 模型，实现图像检索的同时保持联合嵌入的精准对齐

发布时间：2024年09月03日

`LLM应用` `多媒体` `搜索引擎`

> Optimizing CLIP Models for Image Retrieval with Maintained Joint-Embedding Alignment

# 摘要

> CLIP 技术在多媒体检索领域具有革命性，通过同时训练两个神经网络为文本和图像生成联合嵌入。然而，直接应用时，模型在区分视觉差异大但标题相似的图像时表现不佳，影响了基于图像的相似搜索。本文针对这一挑战，提出优化方案，确保 CLIP 在多种图像相似搜索场景中表现出色，同时不削弱其在文本检索任务中的效能。我们设计了两种创新方法：一是顺序微调，先优化图像编码器，再调整文本编码器；二是引入伪标题，直接在嵌入空间内对齐。实验证明，这些方法提升了 CLIP 在图像检索、分类等任务中的性能，同时简化了大规模多模态搜索系统的架构。

> Contrastive Language and Image Pairing (CLIP), a transformative method in multimedia retrieval, typically trains two neural networks concurrently to generate joint embeddings for text and image pairs. However, when applied directly, these models often struggle to differentiate between visually distinct images that have similar captions, resulting in suboptimal performance for image-based similarity searches. This paper addresses the challenge of optimizing CLIP models for various image-based similarity search scenarios, while maintaining their effectiveness in text-based search tasks such as text-to-image retrieval and zero-shot classification. We propose and evaluate two novel methods aimed at refining the retrieval capabilities of CLIP without compromising the alignment between text and image embeddings. The first method involves a sequential fine-tuning process: initially optimizing the image encoder for more precise image retrieval and subsequently realigning the text encoder to these optimized image embeddings. The second approach integrates pseudo-captions during the retrieval-optimization phase to foster direct alignment within the embedding space. Through comprehensive experiments, we demonstrate that these methods enhance CLIP's performance on various benchmarks, including image retrieval, k-NN classification, and zero-shot text-based classification, while maintaining robustness in text-to-image retrieval. Our optimized models permit maintaining a single embedding per image, significantly simplifying the infrastructure needed for large-scale multi-modal similarity search systems.

[Arxiv](https://arxiv.org/abs/2409.01936)