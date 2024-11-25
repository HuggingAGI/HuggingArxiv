# 利用文本到图像扩散模型进行无监督模态适应以实现语义分割

发布时间：2024年10月28日

`其他` `计算机视觉` `语义分割`

> Unsupervised Modality Adaptation with Text-to-Image Diffusion Models for Semantic Segmentation

# 摘要

> 尽管成果斐然，但用于语义分割的无监督域适应方法主要着眼于图像域之间的适应，而未充分利用深度、红外和事件等其他丰富的视觉模态。这一局限阻碍了其性能发挥，也限制了其在现实世界多模态场景中的应用。为化解此难题，我们针对语义分割任务提出了具有文本到图像扩散模型的模态适应（MADM），借助在大量图像 - 文本对上预训练的文本到图像扩散模型来增强模型的跨模态能力。具体来说，MADM 包含两个关键的互补组件以应对主要挑战。其一，鉴于模态差异较大，用一种模态数据为另一种模态生成伪标签会致使准确性显著降低。对此，MADM 设计了基于扩散的伪标签生成方式，添加潜在噪声以稳定伪标签并提升标签准确性。其二，为克服扩散模型中潜在低分辨率特征的限制，MADM 引入了标签调色板和潜在回归，通过调色板将独热编码标签转为 RGB 形式，并在潜在空间中进行回归，从而保障预训练的解码器进行上采样以获取细粒度特征。大量实验结果表明，MADM 在包括图像到深度、红外和事件模态等各类模态任务中均达成了最先进的适应性能。我们在 https://github.com/XiaRho/MADM 开源了代码和模型。

> Despite their success, unsupervised domain adaptation methods for semantic segmentation primarily focus on adaptation between image domains and do not utilize other abundant visual modalities like depth, infrared and event. This limitation hinders their performance and restricts their application in real-world multimodal scenarios. To address this issue, we propose Modality Adaptation with text-to-image Diffusion Models (MADM) for semantic segmentation task which utilizes text-to-image diffusion models pre-trained on extensive image-text pairs to enhance the model's cross-modality capabilities. Specifically, MADM comprises two key complementary components to tackle major challenges. First, due to the large modality gap, using one modal data to generate pseudo labels for another modality suffers from a significant drop in accuracy. To address this, MADM designs diffusion-based pseudo-label generation which adds latent noise to stabilize pseudo-labels and enhance label accuracy. Second, to overcome the limitations of latent low-resolution features in diffusion models, MADM introduces the label palette and latent regression which converts one-hot encoded labels into the RGB form by palette and regresses them in the latent space, thus ensuring the pre-trained decoder for up-sampling to obtain fine-grained features. Extensive experimental results demonstrate that MADM achieves state-of-the-art adaptation performance across various modality tasks, including images to depth, infrared, and event modalities. We open-source our code and models at https://github.com/XiaRho/MADM.

[Arxiv](https://arxiv.org/abs/2410.21708)