# L-MAGIC：借助语言模型，生成连贯图像的魔法

发布时间：2024年06月03日

`LLM应用

理由：这篇论文介绍了一种名为L-MAGIC的新方法，该方法利用大型语言模型（LLM）来指导生成连贯的360度全景视图。这种方法特别强调了LLM在实际应用中的效能，即在无需模型微调的情况下，保持零-shot性能，并通过超分辨率和多视角融合技术提升输出质量。此外，论文还提到了L-MAGIC的多种输入兼容性和其生成的全景场景在布局和渲染质量上的优越性。这些特点表明，该论文主要关注的是LLM在特定应用场景（全景场景生成）中的实际应用和效果，因此属于LLM应用分类。` `计算机视觉` `虚拟现实`

> L-MAGIC: Language Model Assisted Generation of Images with Coherence

# 摘要

> 在生成AI技术飞速发展的今天，从单张图片生成全景场景仍是一大挑战。现有技术多依赖于扩散模型进行迭代或多视角修复，但常因缺乏全局场景布局先验而产生重复物体，或需耗时的人工文本输入。为此，我们创新性地提出了L-MAGIC方法，它巧妙结合大型语言模型，指导生成连贯的360度全景视图，且无需模型微调，保持零-shot性能。通过超分辨率和多视角融合技术，输出质量显著提升。实验证明，L-MAGIC生成的全景场景在布局和渲染质量上超越同类技术，人类评估中偏好率高达70%以上。此外，L-MAGIC兼容多种输入，如文本、深度图、草图等，并能通过深度估计生成3D点云，探索动态场景，实现流畅的相机运动。代码及演示视频已公开，详情请访问GitHub和YouTube链接。

> In the current era of generative AI breakthroughs, generating panoramic scenes from a single input image remains a key challenge. Most existing methods use diffusion-based iterative or simultaneous multi-view inpainting. However, the lack of global scene layout priors leads to subpar outputs with duplicated objects (e.g., multiple beds in a bedroom) or requires time-consuming human text inputs for each view. We propose L-MAGIC, a novel method leveraging large language models for guidance while diffusing multiple coherent views of 360 degree panoramic scenes. L-MAGIC harnesses pre-trained diffusion and language models without fine-tuning, ensuring zero-shot performance. The output quality is further enhanced by super-resolution and multi-view fusion techniques. Extensive experiments demonstrate that the resulting panoramic scenes feature better scene layouts and perspective view rendering quality compared to related works, with >70% preference in human evaluations. Combined with conditional diffusion models, L-MAGIC can accept various input modalities, including but not limited to text, depth maps, sketches, and colored scripts. Applying depth estimation further enables 3D point cloud generation and dynamic scene exploration with fluid camera motion. Code is available at https://github.com/IntelLabs/MMPano. The video presentation is available at https://youtu.be/XDMNEzH4-Ec?list=PLG9Zyvu7iBa0-a7ccNLO8LjcVRAoMn57s.

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x1.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x2.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x3.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x4.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x5.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x6.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x7.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x8.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x9.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x10.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x11.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x12.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x13.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x14.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x15.png)

![L-MAGIC：借助语言模型，生成连贯图像的魔法](../../../paper_images/2406.01843/x17.png)

[Arxiv](https://arxiv.org/abs/2406.01843)