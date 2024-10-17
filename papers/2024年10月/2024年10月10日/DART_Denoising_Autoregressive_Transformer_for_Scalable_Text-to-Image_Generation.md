# DART：一种去噪自回归变换器，专为可扩展的文本到图像生成而设计。

发布时间：2024年10月10日

`其他` `视觉生成` `图像处理`

> DART: Denoising Autoregressive Transformer for Scalable Text-to-Image Generation

# 摘要

> 扩散模型在视觉生成领域占据主导地位，但马尔可夫性质限制了其充分利用生成轨迹的能力，导致训练和推理效率低下。为此，我们提出DART，一种基于Transformer的非马尔可夫框架模型，统一了自回归和扩散过程。DART通过迭代去噪图像块，不依赖图像量化，实现更灵活高效的图像建模。此外，DART能无缝整合文本和图像数据进行训练，在类别条件和文本到图像生成任务上表现出色，为传统扩散模型提供了可扩展、高效的替代方案。DART的统一框架为高质量图像合成设定了新标准。

> 
Abstract:Diffusion models have become the dominant approach for visual generation. They are trained by denoising a Markovian process that gradually adds noise to the input. We argue that the Markovian property limits the models ability to fully utilize the generation trajectory, leading to inefficiencies during training and inference. In this paper, we propose DART, a transformer-based model that unifies autoregressive (AR) and diffusion within a non-Markovian framework. DART iteratively denoises image patches spatially and spectrally using an AR model with the same architecture as standard language models. DART does not rely on image quantization, enabling more effective image modeling while maintaining flexibility. Furthermore, DART seamlessly trains with both text and image data in a unified model. Our approach demonstrates competitive performance on class-conditioned and text-to-image generation tasks, offering a scalable, efficient alternative to traditional diffusion models. Through this unified framework, DART sets a new benchmark for scalable, high-quality image synthesis.
    

[Arxiv](https://arxiv.org/pdf/2410.08159)