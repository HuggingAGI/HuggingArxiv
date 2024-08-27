# 以艺术家之手，借助扩散模型，通过构图、绘制与润饰，创造出错综复杂的场景。

发布时间：2024年08月25日

`LLM应用` `图像处理` `计算机视觉`

> Draw Like an Artist: Complex Scene Generation with Diffusion Model via Composition, Painting, and Retouching

# 摘要

> 近期，文本到图像扩散模型在图像质量上展现了卓越能力，但复杂场景生成仍待深入探索，其定义也尚不明确。本文中，我们明确了复杂场景的定义，并引入了复杂分解标准（CDC）。受艺术家创作启发，我们提出了无需训练的复杂扩散框架（CxD），分为构图、绘画和修饰三阶段。借助大型语言模型的思维链能力，我们根据CDC分解复杂提示，管理构图布局，并采用注意力调制方法，引导简单提示至特定区域，完成复杂场景绘画。最后，通过修饰模型增强细节，实现修饰阶段。实验证明，我们的方法在生成高质量、语义一致且视觉多样的复杂场景图像方面，超越了现有最佳方法，即便面对复杂提示也能表现出色。

> Recent advances in text-to-image diffusion models have demonstrated impressive capabilities in image quality. However, complex scene generation remains relatively unexplored, and even the definition of `complex scene' itself remains unclear. In this paper, we address this gap by providing a precise definition of complex scenes and introducing a set of Complex Decomposition Criteria (CDC) based on this definition. Inspired by the artists painting process, we propose a training-free diffusion framework called Complex Diffusion (CxD), which divides the process into three stages: composition, painting, and retouching. Our method leverages the powerful chain-of-thought capabilities of large language models (LLMs) to decompose complex prompts based on CDC and to manage composition and layout. We then develop an attention modulation method that guides simple prompts to specific regions to complete the complex scene painting. Finally, we inject the detailed output of the LLM into a retouching model to enhance the image details, thus implementing the retouching stage. Extensive experiments demonstrate that our method outperforms previous SOTA approaches, significantly improving the generation of high-quality, semantically consistent, and visually diverse images for complex scenes, even with intricate prompts.

[Arxiv](https://arxiv.org/abs/2408.13858)