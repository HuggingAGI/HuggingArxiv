# Chat2SVG：借助大型语言模型和图像扩散模型实现矢量图形生成

发布时间：2024年11月25日

`LLM应用` `数字设计` `图形生成`

> Chat2SVG: Vector Graphics Generation with Large Language Models and Image Diffusion Models

# 摘要

> 可缩放矢量图形（SVG）已然成为数字设计中矢量图形的实际标准，具备分辨率独立和对单个元素的精准把控等特性。虽说有这些优势，可创作高质量的 SVG 内容依旧困难重重，毕竟这需要专业编辑软件方面的技术专长，还得投入大量时间去塑造复杂形状。近来的文本转 SVG 生成方法意在让矢量图形的创作更便捷，然而它们在形状的规整性、泛化能力以及表现力上仍存在局限。为应对这些挑战，我们推出了 Chat2SVG，这是一个融合了大型语言模型（LLMs）和图像扩散模型优势的混合框架，用于文本转 SVG 的生成。我们的方法先是利用 LLM 从基本几何原语生成富有语义的 SVG 模板。在图像扩散模型的引导下，一个双阶段优化流程在潜在空间中优化路径，并调整点坐标以增强几何复杂度。大量实验表明，Chat2SVG 在视觉保真度、路径规整性和语义对齐方面都胜过现有方法。另外，我们的系统通过自然语言指令实现直观编辑，让所有用户都能进行专业的矢量图形创作。

> Scalable Vector Graphics (SVG) has become the de facto standard for vector graphics in digital design, offering resolution independence and precise control over individual elements. Despite their advantages, creating high-quality SVG content remains challenging, as it demands technical expertise with professional editing software and a considerable time investment to craft complex shapes. Recent text-to-SVG generation methods aim to make vector graphics creation more accessible, but they still encounter limitations in shape regularity, generalization ability, and expressiveness. To address these challenges, we introduce Chat2SVG, a hybrid framework that combines the strengths of Large Language Models (LLMs) and image diffusion models for text-to-SVG generation. Our approach first uses an LLM to generate semantically meaningful SVG templates from basic geometric primitives. Guided by image diffusion models, a dual-stage optimization pipeline refines paths in latent space and adjusts point coordinates to enhance geometric complexity. Extensive experiments show that Chat2SVG outperforms existing methods in visual fidelity, path regularity, and semantic alignment. Additionally, our system enables intuitive editing through natural language instructions, making professional vector graphics creation accessible to all users.

[Arxiv](https://arxiv.org/abs/2411.16602)