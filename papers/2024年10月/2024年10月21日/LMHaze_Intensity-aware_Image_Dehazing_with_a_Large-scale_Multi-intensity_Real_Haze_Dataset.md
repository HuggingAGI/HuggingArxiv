# LMHaze：基于大规模多强度真实雾霾数据集的强度感知图像去雾技术

发布时间：2024年10月21日

`其他` `计算机视觉` `图像处理`

> LMHaze: Intensity-aware Image Dehazing with a Large-scale Multi-intensity Real Haze Dataset

# 摘要

> 近年来，图像去雾技术备受瞩目。然而，基于学习的方法通常依赖于配对的模糊与清晰图像进行训练，这在真实世界中难以实现，限制了现有方法的发展。尽管一些研究通过合成数据集或小规模真实数据集部分缓解了这一问题，但现有数据集的雾浓度分布偏差和场景同质性仍限制了方法的泛化能力。为此，我们推出了LMHaze，一个大规模、高质量的真实世界数据集，包含超过5K对高分辨率图像，比现有最大数据集大25倍以上。此外，我们提出了一种基于Mamba（MoE-Mamba）的专家混合模型，能根据雾浓度动态调整参数，以应对不同雾浓度的图像。我们还进行了一项基于大型多模态模型（LMM）的基准研究，模拟人类感知来评估去雾效果。实验证明，LMHaze数据集显著提升了真实场景中的去雾性能，我们的方法也优于当前最先进的技术。

> Image dehazing has drawn a significant attention in recent years. Learning-based methods usually require paired hazy and corresponding ground truth (haze-free) images for training. However, it is difficult to collect real-world image pairs, which prevents developments of existing methods. Although several works partially alleviate this issue by using synthetic datasets or small-scale real datasets. The haze intensity distribution bias and scene homogeneity in existing datasets limit the generalization ability of these methods, particularly when encountering images with previously unseen haze intensities. In this work, we present LMHaze, a large-scale, high-quality real-world dataset. LMHaze comprises paired hazy and haze-free images captured in diverse indoor and outdoor environments, spanning multiple scenarios and haze intensities. It contains over 5K high-resolution image pairs, surpassing the size of the biggest existing real-world dehazing dataset by over 25 times. Meanwhile, to better handle images with different haze intensities, we propose a mixture-of-experts model based on Mamba (MoE-Mamba) for dehazing, which dynamically adjusts the model parameters according to the haze intensity. Moreover, with our proposed dataset, we conduct a new large multimodal model (LMM)-based benchmark study to simulate human perception for evaluating dehazed images. Experiments demonstrate that LMHaze dataset improves the dehazing performance in real scenarios and our dehazing method provides better results compared to state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2410.16095)