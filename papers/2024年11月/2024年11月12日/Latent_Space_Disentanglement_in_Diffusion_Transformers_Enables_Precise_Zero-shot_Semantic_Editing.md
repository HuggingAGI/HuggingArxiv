# 在扩散变压器中的潜在空间解缠能够实现精确的零样本语义编辑

发布时间：2024年11月12日

`其他` `图像生成` `图像编辑`

> Latent Space Disentanglement in Diffusion Transformers Enables Precise Zero-shot Semantic Editing

# 摘要

> 扩散 Transformer（DiTs）最近在文本引导的图像生成方面取得了显著的成功。在图像编辑中，DiTs 将文本和图像输入投影到一个联合潜在空间，从中解码并合成新图像。然而，多模态信息如何共同形成这个联合空间以及它们如何引导合成图像的语义在很大程度上仍未被探索。在本文中，我们研究了 DiT 模型的潜在空间，并揭示了两个关键特性：首先，DiT 的潜在空间本质上是语义解耦的，不同的语义属性可以通过特定的编辑方向进行控制。其次，一致的语义编辑需要利用整个联合潜在空间，因为单独的编码图像或文本都不包含足够的语义信息。我们表明，这些编辑方向可以直接从文本提示中获得，无需额外的训练或掩码注释即可实现精确的语义控制。基于这些见解，我们提出了一个简单而有效的用于零样本细粒度图像编辑的编码 - 识别 - 操作（EIM）框架。具体来说，我们首先对给定的源图像和描述图像的文本提示进行编码，以获得联合潜在嵌入。然后，使用我们提出的 Hessian 分数蒸馏采样（HSDS）方法，我们确定控制特定目标属性同时保留其他图像特征的编辑方向。这些方向由文本提示引导，并用于操作潜在嵌入。此外，我们提出了一种新的指标来量化扩散模型潜在空间的解耦程度。在我们新整理的基准数据集上的大量实验结果和分析证明了 DiT 的解耦特性和 EIM 框架的有效性。

> Diffusion Transformers (DiTs) have recently achieved remarkable success in text-guided image generation. In image editing, DiTs project text and image inputs to a joint latent space, from which they decode and synthesize new images. However, it remains largely unexplored how multimodal information collectively forms this joint space and how they guide the semantics of the synthesized images. In this paper, we investigate the latent space of DiT models and uncover two key properties: First, DiT's latent space is inherently semantically disentangled, where different semantic attributes can be controlled by specific editing directions. Second, consistent semantic editing requires utilizing the entire joint latent space, as neither encoded image nor text alone contains enough semantic information. We show that these editing directions can be obtained directly from text prompts, enabling precise semantic control without additional training or mask annotations. Based on these insights, we propose a simple yet effective Encode-Identify-Manipulate (EIM) framework for zero-shot fine-grained image editing. Specifically, we first encode both the given source image and the text prompt that describes the image, to obtain the joint latent embedding. Then, using our proposed Hessian Score Distillation Sampling (HSDS) method, we identify editing directions that control specific target attributes while preserving other image features. These directions are guided by text prompts and used to manipulate the latent embeddings. Moreover, we propose a new metric to quantify the disentanglement degree of the latent space of diffusion models. Extensive experiment results on our new curated benchmark dataset and analysis demonstrate DiT's disentanglement properties and effectiveness of the EIM framework.

[Arxiv](https://arxiv.org/abs/2411.08196)