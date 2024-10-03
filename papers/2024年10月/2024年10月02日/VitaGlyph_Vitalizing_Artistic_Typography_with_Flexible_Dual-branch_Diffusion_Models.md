# VitaGlyph：以灵活的双分支扩散模型赋予艺术字体生命力

发布时间：2024年10月02日

`LLM应用`

> VitaGlyph: Vitalizing Artistic Typography with Flexible Dual-branch Diffusion Models

# 摘要

> 艺术字体通过强大的文本到图像扩散模型，直接设计字符的几何和纹理，但难以兼顾创意与可读性。本文提出 VitaGlyph，一种双分支、无需训练的方法，能在保持可读性的同时，灵活设计艺术字体并控制几何变化。VitaGlyph 将字符视为由主体和背景组成的场景，在不同几何变换下渲染，主体表达字符核心概念，背景丰富细节。通过三阶段框架实现：(i) 利用大型语言模型设计主体和背景描述；(ii) 分解字符图像为主体和背景区域；(iii) 优化主体结构，分别渲染主体和背景纹理。实验显示，VitaGlyph 不仅提升艺术性和可读性，还能描绘多种定制概念，促进更具创意的艺术字体生成。代码将在 https://github.com/Carlofkl/VitaGlyph 公开。

> Artistic typography is a technique to visualize the meaning of input character in an imaginable and readable manner. With powerful text-to-image diffusion models, existing methods directly design the overall geometry and texture of input character, making it challenging to ensure both creativity and legibility. In this paper, we introduce a dual-branch and training-free method, namely VitaGlyph, enabling flexible artistic typography along with controllable geometry change to maintain the readability. The key insight of VitaGlyph is to treat input character as a scene composed of Subject and Surrounding, followed by rendering them under varying degrees of geometry transformation. The subject flexibly expresses the essential concept of input character, while the surrounding enriches relevant background without altering the shape. Specifically, we implement VitaGlyph through a three-phase framework: (i) Knowledge Acquisition leverages large language models to design text descriptions of subject and surrounding. (ii) Regional decomposition detects the part that most matches the subject description and divides input glyph image into subject and surrounding regions. (iii) Typography Stylization firstly refines the structure of subject region via Semantic Typography, and then separately renders the textures of Subject and Surrounding regions through Controllable Compositional Generation. Experimental results demonstrate that VitaGlyph not only achieves better artistry and readability, but also manages to depict multiple customize concepts, facilitating more creative and pleasing artistic typography generation. Our code will be made publicly at https://github.com/Carlofkl/VitaGlyph.

[Arxiv](https://arxiv.org/abs/2410.01738)