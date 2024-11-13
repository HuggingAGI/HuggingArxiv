# LapGSR：用于引导热超分辨率的拉普拉斯重构网络

发布时间：2024年11月12日

`其他` `机器人技术` `图像超分辨率`

> LapGSR: Laplacian Reconstructive Network for Guided Thermal Super-Resolution

# 摘要

> 在过去的几年里，多模态数据的融合已被广泛研究用于各种应用，如机器人技术、手势识别和自主导航。确实，高质量的视觉传感器很昂贵，而消费级传感器产生低分辨率图像。研究人员已经开发出将RGB彩色图像与非视觉数据（如热数据）相结合的方法，以克服这一限制来提高分辨率。将多种模态融合以生成视觉上吸引人的高分辨率图像通常需要具有数百万参数的密集模型和沉重的计算负荷，这通常归因于模型的复杂架构。

我们提出LapGSR，这是一种多模态、轻量级的生成模型，结合了拉普拉斯图像金字塔用于引导热超分辨率。这种方法在RGB彩色图像上使用拉普拉斯金字塔来提取重要的边缘信息，然后与组合的像素和对抗损失一起用于绕过模型较高层中的繁重特征图计算。LapGSR在保留图像的空间和结构细节的同时，也高效且紧凑。这导致该模型的参数比其他SOTA模型少得多，同时在两个跨域数据集，即ULB17-VT和VGTSR数据集上展示出出色的结果。

> In the last few years, the fusion of multi-modal data has been widely studied for various applications such as robotics, gesture recognition, and autonomous navigation. Indeed, high-quality visual sensors are expensive, and consumer-grade sensors produce low-resolution images. Researchers have developed methods to combine RGB color images with non-visual data, such as thermal, to overcome this limitation to improve resolution. Fusing multiple modalities to produce visually appealing, high-resolution images often requires dense models with millions of parameters and a heavy computational load, which is commonly attributed to the intricate architecture of the model.
  We propose LapGSR, a multimodal, lightweight, generative model incorporating Laplacian image pyramids for guided thermal super-resolution. This approach uses a Laplacian Pyramid on RGB color images to extract vital edge information, which is then used to bypass heavy feature map computation in the higher layers of the model in tandem with a combined pixel and adversarial loss. LapGSR preserves the spatial and structural details of the image while also being efficient and compact. This results in a model with significantly fewer parameters than other SOTA models while demonstrating excellent results on two cross-domain datasets viz. ULB17-VT and VGTSR datasets.

[Arxiv](https://arxiv.org/abs/2411.07750)