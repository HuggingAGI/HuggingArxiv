# GlyphDraw2：结合扩散模型与大型语言模型，自动创作复杂字形海报。

发布时间：2024年07月02日

`LLM应用`

> GlyphDraw2: Automatic Generation of Complex Glyph Posters with Diffusion Models and Large Language Models

# 摘要

> 海报在营销和广告中至关重要，通过提升视觉传达和品牌曝光，对工业设计贡献巨大。随着可控文本到图像技术的进步，合成图像中的文本渲染成为研究焦点。尽管文本渲染精度提升，端到端海报生成仍待深入探索。这一挑战要求在文本准确性和布局自动化间找到平衡，以产出高分辨率、多宽高比的海报。为此，我们设计了基于对齐学习的三重交叉注意力机制，旨在精细背景中精准渲染海报文本。同时，我们推出了超1024像素的高分辨率数据集，并采用SDXL架构。实验证明，我们的方法能生成背景丰富、细节精致的海报。相关代码将在GitHub上公开。

> Posters play a crucial role in marketing and advertising, contributing significantly to industrial design by enhancing visual communication and brand visibility. With recent advances in controllable text-to-image diffusion models, more concise research is now focusing on rendering text within synthetic images. Despite improvements in text rendering accuracy, the field of end-to-end poster generation remains underexplored. This complex task involves striking a balance between text rendering accuracy and automated layout to produce high-resolution images with variable aspect ratios. To tackle this challenge, we propose an end-to-end text rendering framework employing a triple cross-attention mechanism rooted in align learning, designed to create precise poster text within detailed contextual backgrounds. Additionally, we introduce a high-resolution dataset that exceeds 1024 pixels in image resolution. Our approach leverages the SDXL architecture. Extensive experiments validate the ability of our method to generate poster images featuring intricate and contextually rich backgrounds. Codes will be available at https://github.com/OPPO-Mente-Lab/GlyphDraw2.

[Arxiv](https://arxiv.org/abs/2407.02252)