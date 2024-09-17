# 红外与可见光图像融合的分层人类感知

发布时间：2024年09月13日

`LLM应用` `图像处理` `视觉感知`

> Infrared and Visible Image Fusion with Hierarchical Human Perception

# 摘要

> 图像融合技术将多源图像合而为一，保留了各源域的互补信息。然而，现有方法多以像素强度、纹理等为标准，忽略了人类感知的提升。为此，我们提出了分层感知融合（HPFusion），借助大型视觉-语言模型，结合人类分层语义先验，确保融合图像既保留互补信息，又符合人类视觉习惯。我们设计了一系列问题，模拟人类观看图像时的关注点，并通过模型生成答案，将答案文本编码入融合网络。优化过程中，我们还力求使融合图像的语义分布更贴近源图像，深入挖掘人类感知域内的互补信息。实验证明，HPFusion在信息保留和视觉增强方面均表现出色。

> Image fusion combines images from multiple domains into one image, containing complementary information from source domains. Existing methods take pixel intensity, texture and high-level vision task information as the standards to determine preservation of information, lacking enhancement for human perception. We introduce an image fusion method, Hierarchical Perception Fusion (HPFusion), which leverages Large Vision-Language Model to incorporate hierarchical human semantic priors, preserving complementary information that satisfies human visual system. We propose multiple questions that humans focus on when viewing an image pair, and answers are generated via the Large Vision-Language Model according to images. The texts of answers are encoded into the fusion network, and the optimization also aims to guide the human semantic distribution of the fused image more similarly to source images, exploring complementary information within the human perception domain. Extensive experiments demonstrate our HPFusoin can achieve high-quality fusion results both for information preservation and human visual enhancement.

[Arxiv](https://arxiv.org/abs/2409.09291)