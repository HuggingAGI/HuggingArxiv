# 《3D人体化身建模综述：从重建到生成》

发布时间：2024年06月06日

`Agent

理由：这篇论文主要关注的是3D建模技术，特别是3D人体建模，这在计算机视觉和图形学中是一个重要的应用领域。虽然论文中提到了大型语言模型（如CLIP）和扩散模型，但这些技术是作为工具被用来辅助3D人体化身的生成，而不是作为研究的主要焦点。因此，这篇论文更符合Agent分类，因为它探讨的是如何使用这些技术来创建和改进3D模型，而不是深入研究LLM的理论或应用。`

> A Survey on 3D Human Avatar Modeling -- From Reconstruction to Generation

# 摘要

> 3D建模一直是计算机视觉和图形学的核心领域。近年来，神经表示和生成模型的突破推动了3D建模的飞速发展，尤其是3D人体建模，这一技术在游戏和动画等众多应用中占据核心地位，吸引了广泛关注。过去几年，大量关于3D人体化身创建的研究涌现，构建了一个丰富的知识库。面对如此庞大的文献，个人难以全面追踪。本综述旨在从重建和生成两个视角，全面概述这些新兴的3D人体化身建模技术。我们首先回顾了包括像素对齐隐函数、神经辐射场和3D高斯溅射在内的3D人体重建方法。接着，我们总结了利用大型语言模型如CLIP、扩散模型及多种3D表示的3D人体生成方法，这些方法展现了顶尖性能。最后，我们反思现有方法，并探讨3D人体化身建模的挑战与未来研究方向。

> 3D modeling has long been an important area in computer vision and computer graphics. Recently, thanks to the breakthroughs in neural representations and generative models, we witnessed a rapid development of 3D modeling. 3D human modeling, lying at the core of many real-world applications, such as gaming and animation, has attracted significant attention. Over the past few years, a large body of work on creating 3D human avatars has been introduced, forming a new and abundant knowledge base for 3D human modeling. The scale of the literature makes it difficult for individuals to keep track of all the works. This survey aims to provide a comprehensive overview of these emerging techniques for 3D human avatar modeling, from both reconstruction and generation perspectives. Firstly, we review representative methods for 3D human reconstruction, including methods based on pixel-aligned implicit function, neural radiance field, and 3D Gaussian Splatting, etc. We then summarize representative methods for 3D human generation, especially those using large language models like CLIP, diffusion models, and various 3D representations, which demonstrate state-of-the-art performance. Finally, we discuss our reflection on existing methods and open challenges for 3D human avatar modeling, shedding light on future research.

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x1.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x2.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x3.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x4.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x5.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x6.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x7.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x8.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x9.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x10.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/personnerf.jpg)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x11.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x12.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x13.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/tri-plane.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x14.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x15.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x16.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x17.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x18.png)

![《3D人体化身建模综述：从重建到生成》](../../../paper_images/2406.04253/x19.png)

[Arxiv](https://arxiv.org/abs/2406.04253)