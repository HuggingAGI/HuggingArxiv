# SAM-I2I：激发“分割一切”模型在医学图像翻译方面的潜能

发布时间：2024年11月12日

`其他` `医学图像`

> SAM-I2I: Unleash the Power of Segment Anything Model for Medical Image Translation

# 摘要

> 医学图像转换在临床领域中对于降低冗余且昂贵的多模态成像需求极为关键。然而，当下基于卷积神经网络（CNNs）和 Transformer 的方法常常难以捕捉到细粒度语义特征，致使图像质量不尽人意。为解决这一难题，我们推出了 SAM-I2I，这是一个基于分割一切模型 2（SAM2）的全新图像到图像转换框架。SAM-I2I 借助预训练的图像编码器从源图像提取多尺度语义特征，并通过基于掩码单元注意力模块的解码器来合成目标模态图像。我们在多对比度 MRI 数据集上开展的实验表明，SAM-I2I 超越了最前沿的方法，实现了更高效、更精准的医学图像转换。

> Medical image translation is crucial for reducing the need for redundant and expensive multi-modal imaging in clinical field. However, current approaches based on Convolutional Neural Networks (CNNs) and Transformers often fail to capture fine-grain semantic features, resulting in suboptimal image quality. To address this challenge, we propose SAM-I2I, a novel image-to-image translation framework based on the Segment Anything Model 2 (SAM2). SAM-I2I utilizes a pre-trained image encoder to extract multiscale semantic features from the source image and a decoder, based on the mask unit attention module, to synthesize target modality images. Our experiments on multi-contrast MRI datasets demonstrate that SAM-I2I outperforms state-of-the-art methods, offering more efficient and accurate medical image translation.

[Arxiv](https://arxiv.org/abs/2411.12755)