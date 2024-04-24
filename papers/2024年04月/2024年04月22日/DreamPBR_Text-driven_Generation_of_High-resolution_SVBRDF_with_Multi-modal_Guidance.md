# DreamPBR：一种文本驱动的高分辨率SVBRDF生成技术，辅以多模态引导功能。

发布时间：2024年04月22日

`分类：LLM应用

这篇论文讨论了一种基于扩散的生成框架DreamPBR，它能够根据文本和多模态控制生成具有空间变化外观属性的材料。这个框架利用了大规模视觉-语言模型的能力，这些模型基于数十亿文本-图像对进行训练。因此，这篇论文可以归类为LLM应用，因为它展示了如何将大型语言模型（LLM）应用于材料生成任务，以提高生成的可控性和多样性。` `材料科学` `计算机图形学`

> DreamPBR: Text-driven Generation of High-resolution SVBRDF with Multi-modal Guidance

# 摘要

> 以往材料生成方法因依赖现实世界数据和训练数据集规模有限，难以产生多样化结果。为解决这一问题，我们推出了DreamPBR，一种创新的基于扩散的生成框架，能够根据文本和多模态控制生成具有空间变化外观属性的材料，极大提升了材料生成的可控性和多样性。这一成就归功于结合了最新大规模视觉-语言模型的能力，这些模型基于数十亿文本-图像对进行训练，并利用了数百个PBR材料样本中提取的材料先验。我们采用了一种新型材料潜在扩散模型（LDM）来映射反照率图与潜在空间的关系，并通过渲染感知的PBR解码器将潜在表示解码为完整的SVBRDF参数图。本方法还支持通过循环填充卷积实现可平铺生成。此外，我们还引入了多模态引导模块，包括像素对齐、风格图像和3D形状引导，以增强材料LDM的控制能力。DreamPBR在材料创作上的应用证明了其效果，无论是在可控生成还是编辑应用上，都展现了其多功能性和易用性。

> Prior material creation methods had limitations in producing diverse results mainly because reconstruction-based methods relied on real-world measurements and generation-based methods were trained on relatively small material datasets. To address these challenges, we propose DreamPBR, a novel diffusion-based generative framework designed to create spatially-varying appearance properties guided by text and multi-modal controls, providing high controllability and diversity in material generation. Key to achieving diverse and high-quality PBR material generation lies in integrating the capabilities of recent large-scale vision-language models trained on billions of text-image pairs, along with material priors derived from hundreds of PBR material samples. We utilize a novel material Latent Diffusion Model (LDM) to establish the mapping between albedo maps and the corresponding latent space. The latent representation is then decoded into full SVBRDF parameter maps using a rendering-aware PBR decoder. Our method supports tileable generation through convolution with circular padding. Furthermore, we introduce a multi-modal guidance module, which includes pixel-aligned guidance, style image guidance, and 3D shape guidance, to enhance the control capabilities of the material LDM. We demonstrate the effectiveness of DreamPBR in material creation, showcasing its versatility and user-friendliness on a wide range of controllable generation and editing applications.

[Arxiv](https://arxiv.org/abs/2404.14676)