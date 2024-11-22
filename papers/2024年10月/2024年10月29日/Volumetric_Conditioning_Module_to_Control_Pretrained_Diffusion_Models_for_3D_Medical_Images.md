# 用于掌控 3D 医学图像预训练扩散模型的体积调节模块

发布时间：2024年10月29日

`其他` `医学成像` `图像合成`

> Volumetric Conditioning Module to Control Pretrained Diffusion Models for 3D Medical Images

# 摘要

> 在预训练的扩散模型上采用附加模块的空间控制方法，因能于自然图像中达成条件生成而备受瞩目。这些方法在借助大型模型能力的同时，以新条件引领生成流程。在 3D 医学成像领域，鉴于高计算成本和数据稀缺，从头训练扩散模型颇具挑战，所以它们作为训练策略可能颇具益处。然而，带有附加模块的空间控制方法在 3D 医学图像中的潜在应用尚未被探索。本文中，我们为 3D 医学图像推出了一种量身定制的空间控制方法，即具备新型轻量级模块——体积调节模块（VCM）。我们的 VCM 运用非对称 U-Net 架构，能有效地从 3D 条件的各个层面编码复杂信息，为图像合成给予详尽指引。为考查空间控制方法的适用性以及 VCM 对 3D 医学数据的有效性，我们在单模态和多模态条件场景下开展实验，涵盖了从仅 10 个样本的极小数据集到 500 个样本的大型数据集等各种规模。实验结果显示，VCM 在条件生成方面成效显著，且在所需训练数据和计算资源更少方面表现高效。我们还通过医学图像的轴向超分辨率进一步探究了我们空间控制方法的潜在应用。我们的代码可在 url{https://github.com/Ahn-Ssu/VCM} 获取。

> Spatial control methods using additional modules on pretrained diffusion models have gained attention for enabling conditional generation in natural images. These methods guide the generation process with new conditions while leveraging the capabilities of large models. They could be beneficial as training strategies in the context of 3D medical imaging, where training a diffusion model from scratch is challenging due to high computational costs and data scarcity. However, the potential application of spatial control methods with additional modules to 3D medical images has not yet been explored. In this paper, we present a tailored spatial control method for 3D medical images with a novel lightweight module, Volumetric Conditioning Module (VCM). Our VCM employs an asymmetric U-Net architecture to effectively encode complex information from various levels of 3D conditions, providing detailed guidance in image synthesis. To examine the applicability of spatial control methods and the effectiveness of VCM for 3D medical data, we conduct experiments under single- and multimodal conditions scenarios across a wide range of dataset sizes, from extremely small datasets with 10 samples to large datasets with 500 samples. The experimental results show that the VCM is effective for conditional generation and efficient in terms of requiring less training data and computational resources. We further investigate the potential applications for our spatial control method through axial super-resolution for medical images. Our code is available at url{https://github.com/Ahn-Ssu/VCM}

[Arxiv](https://arxiv.org/abs/2410.21826)