# 逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整

发布时间：2024年06月06日

`LLM应用

理由：这篇论文主要讨论了直接偏好优化（DPO）技术在大型语言模型（LLMs）与文本到图像扩散模型对齐中的应用，特别是提出了步骤感知偏好优化（SPO）技术，这是一种针对每个去噪步骤定制偏好标签的后训练技术。这种技术旨在优化每个步骤的去噪能力，并通过步骤感知偏好模型和步骤级重采样器实现精准的步骤级监督。因此，这项工作属于LLM在特定应用场景（即文本到图像扩散模型对齐）中的应用，而不是理论研究或Agent相关的工作。` `图像生成` `人工智能`

> Step-aware Preference Optimization: Aligning Preference with Denoising Performance at Each Step

# 摘要

> 近期，直接偏好优化（DPO）技术已成功应用于将大型语言模型（LLMs）与文本到图像扩散模型对齐，以符合人类偏好。不同于传统DPO方法假设所有扩散步骤的偏好顺序与最终图像一致，我们提出，这种假设忽视了各步骤特有的去噪效果，应为每个步骤定制偏好标签。为此，我们开发了步骤感知偏好优化（SPO），一种创新的后训练技术，它独立评估并优化每个步骤的去噪能力，通过步骤感知偏好模型和步骤级重采样器实现精准的步骤级监督。在每个去噪阶段，我们从一组图像中选取，确定胜负对，并随机挑选一张图像作为下一阶段的起点。这一过程确保了胜负比较不受前一阶段影响。我们训练了一个专用的步骤感知偏好模型，用于评估噪声和干净图像在各阶段的偏好。实验结果显示，SPO在处理复杂、详细提示的图像生成及提升美学质量方面，显著超越了最新的Diffusion-DPO，且训练速度提升了20倍以上。详情及模型访问：https://rockeycoss.github.io/spo.github.io/

> Recently, Direct Preference Optimization (DPO) has extended its success from aligning large language models (LLMs) to aligning text-to-image diffusion models with human preferences. Unlike most existing DPO methods that assume all diffusion steps share a consistent preference order with the final generated images, we argue that this assumption neglects step-specific denoising performance and that preference labels should be tailored to each step's contribution. To address this limitation, we propose Step-aware Preference Optimization (SPO), a novel post-training approach that independently evaluates and adjusts the denoising performance at each step, using a step-aware preference model and a step-wise resampler to ensure accurate step-aware supervision. Specifically, at each denoising step, we sample a pool of images, find a suitable win-lose pair, and, most importantly, randomly select a single image from the pool to initialize the next denoising step. This step-wise resampler process ensures the next win-lose image pair comes from the same image, making the win-lose comparison independent of the previous step. To assess the preferences at each step, we train a separate step-aware preference model that can be applied to both noisy and clean images. Our experiments with Stable Diffusion v1.5 and SDXL demonstrate that SPO significantly outperforms the latest Diffusion-DPO in aligning generated images with complex, detailed prompts and enhancing aesthetics, while also achieving more than 20x times faster in training efficiency. Code and model: https://rockeycoss.github.io/spo.github.io/

![逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整](../../../paper_images/2406.04314/grid_512.png)

![逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整](../../../paper_images/2406.04314/intro_vis.jpg)

![逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整](../../../paper_images/2406.04314/x1.png)

![逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整](../../../paper_images/2406.04314/x2.png)

![逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整](../../../paper_images/2406.04314/x3.png)

![逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整](../../../paper_images/2406.04314/x4.png)

![逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整](../../../paper_images/2406.04314/qualitative_compare.jpg)

![逐步偏好优化：确保每一步的去噪效果与用户偏好同步调整](../../../paper_images/2406.04314/glyphbyt5_sdxl_comp.jpg)

[Arxiv](https://arxiv.org/abs/2406.04314)