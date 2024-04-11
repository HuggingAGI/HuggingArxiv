# 适配 LLaMA 解码器至视觉变换网络

发布时间：2024年04月10日

`LLM应用` `计算机视觉` `机器学习`

> Adapting LLaMA Decoder to Vision Transformer

# 摘要

> 本研究尝试将专为大型语言模型（LLMs）设计的解码器型变换器，如LLaMA，迁移应用到计算机视觉领域。我们逐步调整标准ViT的结构，使其适配LLaMA的架构，却发现直接应用休闲掩码至自注意力会引发注意力崩溃，导致训练失败。为此，我们提出将类别标记置于图像标记之后，采用后序列类别标记技术，以解决这一问题，让休闲自注意力能高效捕获整张图像信息。同时，我们设计了一种软掩码策略，在训练初期逐步引入休闲掩码至自注意力，以优化模型行为。这一定制模型，即图像LLaMA（iLLaMA），在架构上与LLaMA相似，支持直接监督学习。其休闲自注意力不仅提升了计算效率，还通过提高注意力图等级学习到了复杂表示。iLLaMA在性能上与仅编码器模型相媲美，仅用5.7M参数便达到了75.1%的ImageNet top-1准确率。进一步扩展模型至310M参数并在ImageNet-21K上进行预训练，准确率提升至86.0%。大量实验验证了iLLaMA的可靠性：包括校准性、形状纹理偏好、量化兼容性、ADE20K分割能力以及CIFAR的迁移学习能力。我们期望本研究能为LLMs浪潮中的视觉模型设计带来新视角。预训练模型和代码已开放获取。

> This work examines whether decoder-only Transformers such as LLaMA, which were originally designed for large language models (LLMs), can be adapted to the computer vision field. We first "LLaMAfy" a standard ViT step-by-step to align with LLaMA's architecture, and find that directly applying a casual mask to the self-attention brings an attention collapse issue, resulting in the failure to the network training. We suggest to reposition the class token behind the image tokens with a post-sequence class token technique to overcome this challenge, enabling causal self-attention to efficiently capture the entire image's information. Additionally, we develop a soft mask strategy that gradually introduces a casual mask to the self-attention at the onset of training to facilitate the optimization behavior. The tailored model, dubbed as image LLaMA (iLLaMA), is akin to LLaMA in architecture and enables direct supervised learning. Its causal self-attention boosts computational efficiency and learns complex representation by elevating attention map ranks. iLLaMA rivals the performance with its encoder-only counterparts, achieving 75.1% ImageNet top-1 accuracy with only 5.7M parameters. Scaling the model to ~310M and pre-training on ImageNet-21K further enhances the accuracy to 86.0%. Extensive experiments demonstrate iLLaMA's reliable properties: calibration, shape-texture bias, quantization compatibility, ADE20K segmentation and CIFAR transfer learning. We hope our study can kindle fresh views to visual model design in the wave of LLMs. Pre-trained models and codes are available here.

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x1.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x2.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x3.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x4.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x5.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x6.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x7.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x8.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x9.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x10.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x11.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x12.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x13.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x14.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x15.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x16.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x17.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x18.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x19.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x20.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x21.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x22.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x23.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x24.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x25.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x26.png)

![适配 LLaMA 解码器至视觉变换网络](../../../paper_images/2404.06773/x27.png)

[Arxiv](https://arxiv.org/abs/2404.06773)