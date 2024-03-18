# [3DTopia是一款创新的大型文本转三维生成模型，巧妙融合了混合扩散先验技术，实现从文本信息高效构建高质量三维模型。]

发布时间：2024年03月04日

`Agent`

> 3DTopia: Large Text-to-3D Generation Model with Hybrid Diffusion Priors

> 我们创新提出了名为3DTopia的两阶段文本转3D生成系统，借助混合扩散先验技术，在短短5分钟内就能高效产出高品质通用3D素材。首阶段运用从3D数据中直接习得的3D扩散先验进行采样，通过基于文本引导的三平面潜在扩散模型迅速构建出粗略3D样本，满足快速原型设计需求。次阶段则运用2D扩散先验对首阶段产出的粗略3D模型纹理进行精细打磨，同时在潜在空间和像素空间上进行优化，确保高质量纹理的生成。为支持此系统的训练，我们巧妙结合视觉语言模型与大型语言模型的优势，对开源的最大3D数据集Objaverse进行了深度清理与注解。我们从定性与定量两个维度展示了实验结果，验证了所提系统的卓越性能。目前，相关代码与模型已开放在https://github.com/3DTopia/3DTopia供您查阅和使用。

> We present a two-stage text-to-3D generation system, namely 3DTopia, which generates high-quality general 3D assets within 5 minutes using hybrid diffusion priors. The first stage samples from a 3D diffusion prior directly learned from 3D data. Specifically, it is powered by a text-conditioned tri-plane latent diffusion model, which quickly generates coarse 3D samples for fast prototyping. The second stage utilizes 2D diffusion priors to further refine the texture of coarse 3D models from the first stage. The refinement consists of both latent and pixel space optimization for high-quality texture generation. To facilitate the training of the proposed system, we clean and caption the largest open-source 3D dataset, Objaverse, by combining the power of vision language models and large language models. Experiment results are reported qualitatively and quantitatively to show the performance of the proposed system. Our codes and models are available at https://github.com/3DTopia/3DTopia

[Arxiv](https://arxiv.org/abs/2403.02234)