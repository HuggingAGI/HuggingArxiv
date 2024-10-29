# MvDrag3D：通过多视图生成-重建先验进行基于拖动的创意 3D 编辑

发布时间：2024年10月21日

`其他` `3D 编辑` `内容创作`

> MvDrag3D: Drag-based Creative 3D Editing via Multi-view Generation-Reconstruction Priors

# 摘要

> 摘要：基于拖动的编辑在 2D 内容创作中因图像生成模型的能力而变得流行。然而，将此技术扩展到 3D 仍然是一个挑战。现有的 3D 基于拖动的编辑方法，无论是采用显式的空间变换还是依赖于有限容量的 3D 生成模型中的隐式潜在优化，在处理显著的拓扑变化或在不同对象类别中生成新纹理方面都存在不足。为了克服这些限制，我们引入了 MVDrag3D，这是一个用于更灵活和创造性的基于拖动的 3D 编辑的新框架，它利用了多视图生成和重建先验。我们方法的核心是使用多视图扩散模型作为强大的生成先验，在多个渲染视图上执行一致的拖动编辑，然后是一个重建模型，重建编辑对象的 3D 高斯分布。虽然初始的 3D 高斯分布可能在不同视图之间存在未对齐的情况，但我们通过视图特定的变形网络来解决这个问题，调整高斯分布的位置以使其良好对齐。此外，我们提出了一个多视图得分函数，从多个视图中提取生成先验，以进一步提高视图一致性和视觉质量。大量实验表明，MVDrag3D 为基于拖动的 3D 编辑提供了精确、生成性和灵活的解决方案，支持在各种对象类别和 3D 表示中实现更多样化的编辑效果。

> 
Abstract:Drag-based editing has become popular in 2D content creation, driven by the capabilities of image generative models. However, extending this technique to 3D remains a challenge. Existing 3D drag-based editing methods, whether employing explicit spatial transformations or relying on implicit latent optimization within limited-capacity 3D generative models, fall short in handling significant topology changes or generating new textures across diverse object categories. To overcome these limitations, we introduce MVDrag3D, a novel framework for more flexible and creative drag-based 3D editing that leverages multi-view generation and reconstruction priors. At the core of our approach is the usage of a multi-view diffusion model as a strong generative prior to perform consistent drag editing over multiple rendered views, which is followed by a reconstruction model that reconstructs 3D Gaussians of the edited object. While the initial 3D Gaussians may suffer from misalignment between different views, we address this via view-specific deformation networks that adjust the position of Gaussians to be well aligned. In addition, we propose a multi-view score function that distills generative priors from multiple views to further enhance the view consistency and visual quality. Extensive experiments demonstrate that MVDrag3D provides a precise, generative, and flexible solution for 3D drag-based editing, supporting more versatile editing effects across various object categories and 3D representations.
    

[Arxiv](https://arxiv.org/pdf/2410.16272)