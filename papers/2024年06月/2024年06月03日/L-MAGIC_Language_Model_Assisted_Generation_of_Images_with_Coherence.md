# L-MAGIC：借助语言模型，生成连贯图像的魔法

发布时间：2024年06月03日

`LLM应用

理由：这篇论文介绍了一种名为L-MAGIC的创新方法，该方法利用大型语言模型（LLM）在生成360度全景视图时提供精准指导。这种方法展示了LLM在实际应用中的能力，特别是在图像处理和场景生成领域。论文中提到的L-MAGIC方法不需要对预训练模型进行微调，即可实现零-shot性能，并通过技术如超分辨率和多视图融合来提升输出质量。这些特性表明，该论文主要关注的是LLM在特定应用场景中的实际应用和效果，因此归类为LLM应用。` `计算机视觉` `虚拟现实`

> L-MAGIC: Language Model Assisted Generation of Images with Coherence

# 摘要

> 在生成AI技术飞速发展的今天，从单张图片生成全景场景仍是一大挑战。现有技术多依赖于扩散模型进行迭代或多视角修复，但常因缺乏全局场景布局先验而导致输出质量不佳，如出现重复物体（例如，卧室中多个床），或需耗时的人工文本输入来指导每个视图。为此，我们推出了L-MAGIC，一种创新方法，它借助大型语言模型在生成360度全景视图时提供精准指导。L-MAGIC无需对预训练模型进行微调，即可实现零-shot性能，并通过超分辨率和多视图融合技术进一步提升输出质量。实验证明，L-MAGIC生成的全景场景在场景布局和透视图渲染方面表现卓越，人类评估中偏好率高达70%以上。此外，结合条件扩散模型，L-MAGIC能灵活接受多种输入，如文本、深度图、草图等，并利用深度估计技术实现3D点云生成和动态场景的流畅探索。项目代码已公开于https://github.com/IntelLabs/MMPano，演示视频可在此链接https://youtu.be/XDMNEzH4-Ec?list=PLG9Zyvu7iBa0-a7ccNLO8LjcVRAoMn57s观看。

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