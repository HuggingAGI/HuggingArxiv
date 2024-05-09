# 探究视觉变压器结合运动补丁在三维人体运动与语言模型中的应用，以深入理解其对运动表达的影响。

发布时间：2024年05月07日

`Agent

这篇论文主要探讨了如何通过迁移学习将图像领域的知识应用到运动数据分析中，以解决运动数据稀缺的问题。它提出了“运动补丁”的概念，并利用视觉变换器（ViT）作为运动编码器。这种方法可以被视为一种智能体（Agent），因为它在处理和分析运动数据时展现出了自主学习和适应的能力。虽然这种方法可能涉及到大型语言模型（LLM）的应用，但论文的重点在于跨模态学习和数据处理的创新方法，而不是LLM的理论或特定应用。因此，将其归类为Agent更为合适。` `运动分析` `跨模态学习`

> Exploring Vision Transformers for 3D Human Motion-Language Models with Motion Patches

# 摘要

> 为了在3D人体运动与语言间构建跨模态空间，我们需要大量且高质量的运动数据。然而，与图像数据的丰富相比，运动数据的稀缺限制了现有模型的性能。为此，我们提出了“运动补丁”这一新概念，并采用视觉变换器（ViT）通过迁移学习作为运动编码器，旨在将图像领域的知识迁移至运动领域。这些运动补丁基于身体部位对骨骼关节进行分割和排序，对不同骨骼结构具有鲁棒性，并可视为ViT中的彩色图像补丁。实验证明，使用ViT预训练权重进行迁移学习能显著提升运动分析性能，为解决运动数据不足的问题开辟了新途径。我们的研究显示，结合ViT的运动补丁在文本到运动检索等多个领域达到了业界领先水平，有效克服了数据缺乏带来的挑战。

> To build a cross-modal latent space between 3D human motion and language, acquiring large-scale and high-quality human motion data is crucial. However, unlike the abundance of image data, the scarcity of motion data has limited the performance of existing motion-language models. To counter this, we introduce "motion patches", a new representation of motion sequences, and propose using Vision Transformers (ViT) as motion encoders via transfer learning, aiming to extract useful knowledge from the image domain and apply it to the motion domain. These motion patches, created by dividing and sorting skeleton joints based on body parts in motion sequences, are robust to varying skeleton structures, and can be regarded as color image patches in ViT. We find that transfer learning with pre-trained weights of ViT obtained through training with 2D image data can boost the performance of motion analysis, presenting a promising direction for addressing the issue of limited motion data. Our extensive experiments show that the proposed motion patches, used jointly with ViT, achieve state-of-the-art performance in the benchmarks of text-to-motion retrieval, and other novel challenging tasks, such as cross-skeleton recognition, zero-shot motion classification, and human interaction recognition, which are currently impeded by the lack of data.

[Arxiv](https://arxiv.org/abs/2405.04771)