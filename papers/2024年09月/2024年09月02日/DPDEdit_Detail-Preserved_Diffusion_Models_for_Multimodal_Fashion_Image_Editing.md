# DPDEdit：一种专为多模态时尚图像编辑设计的细节保留扩散模型

发布时间：2024年09月02日

`LLM应用` `图像编辑`

> DPDEdit: Detail-Preserved Diffusion Models for Multimodal Fashion Image Editing

# 摘要

> 时尚图像编辑是设计师展现创意的关键工具，但现有技术在准确识别编辑区域和保留服装纹理细节方面仍有不足。为此，我们推出了基于潜在扩散模型的新架构DPDEdit，它通过融合文本、区域掩码、人体姿态及服装纹理图像，优化图像生成。我们利用Grounded-SAM精准定位编辑区域，并创新纹理注入与细化机制，确保细节完美转移。实验证明，DPDEdit在图像质量和多模态输入一致性上超越了现有技术。

> Fashion image editing is a crucial tool for designers to convey their creative ideas by visualizing design concepts interactively. Current fashion image editing techniques, though advanced with multimodal prompts and powerful diffusion models, often struggle to accurately identify editing regions and preserve the desired garment texture detail. To address these challenges, we introduce a new multimodal fashion image editing architecture based on latent diffusion models, called Detail-Preserved Diffusion Models (DPDEdit). DPDEdit guides the fashion image generation of diffusion models by integrating text prompts, region masks, human pose images, and garment texture images. To precisely locate the editing region, we first introduce Grounded-SAM to predict the editing region based on the user's textual description, and then combine it with other conditions to perform local editing. To transfer the detail of the given garment texture into the target fashion image, we propose a texture injection and refinement mechanism. Specifically, this mechanism employs a decoupled cross-attention layer to integrate textual descriptions and texture images, and incorporates an auxiliary U-Net to preserve the high-frequency details of generated garment texture. Additionally, we extend the VITON-HD dataset using a multimodal large language model to generate paired samples with texture images and textual descriptions. Extensive experiments show that our DPDEdit outperforms state-of-the-art methods in terms of image fidelity and coherence with the given multimodal inputs.

[Arxiv](https://arxiv.org/abs/2409.01086)