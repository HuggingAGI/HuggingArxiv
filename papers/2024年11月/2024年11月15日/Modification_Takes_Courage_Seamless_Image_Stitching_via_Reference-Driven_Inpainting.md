# 修改需要勇气：借助参考驱动的修复达成无缝图像拼接

发布时间：2024年11月15日

`LLM应用` `图像拼接` `计算机视觉`

> Modification Takes Courage: Seamless Image Stitching via Reference-Driven Inpainting

# 摘要

> 当前的图像拼接方法在诸如色调不均、视差较大等具有挑战性的场景中，常常会出现明显的拼接缝。为解决此问题，我们提出了参考驱动的修复拼接器（RDIStitcher），它将图像融合与矩形化重新构建为基于参考的修复模型，其修改融合区域更大、修改强度更强，超越了以往的方法。另外，我们引入了一种自监督模型训练方式，通过对文本到图像（T2I）扩散模型进行微调，实现 RDIStitcher 时无需有标记的数据。鉴于评估拼接图像质量存在困难，我们提出了基于多模态大语言模型（MLLMs）的指标，为评估拼接图像质量提供了新视角。与最先进（SOTA）的方法相比，大量实验表明，我们的方法极大地增强了拼接图像的内容连贯性和无缝过渡。尤其在零样本实验中，我们的方法展现出了强大的泛化能力。代码：https://github.com/yayoyo66/RDIStitcher

> Current image stitching methods often produce noticeable seams in challenging scenarios such as uneven hue and large parallax. To tackle this problem, we propose the Reference-Driven Inpainting Stitcher (RDIStitcher), which reformulates the image fusion and rectangling as a reference-based inpainting model, incorporating a larger modification fusion area and stronger modification intensity than previous methods. Furthermore, we introduce a self-supervised model training method, which enables the implementation of RDIStitcher without requiring labeled data by fine-tuning a Text-to-Image (T2I) diffusion model. Recognizing difficulties in assessing the quality of stitched images, we present the Multimodal Large Language Models (MLLMs)-based metrics, offering a new perspective on evaluating stitched image quality. Compared to the state-of-the-art (SOTA) method, extensive experiments demonstrate that our method significantly enhances content coherence and seamless transitions in the stitched images. Especially in the zero-shot experiments, our method exhibits strong generalization capabilities. Code: https://github.com/yayoyo66/RDIStitcher

[Arxiv](https://arxiv.org/abs/2411.10309)