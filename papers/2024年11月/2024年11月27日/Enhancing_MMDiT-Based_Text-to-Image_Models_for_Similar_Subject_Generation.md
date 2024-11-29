# 提升基于 MMDiT 的文本到图像模型来生成相似主题

发布时间：2024年11月27日

`其他` `图像生成` `多模态`

> Enhancing MMDiT-Based Text-to-Image Models for Similar Subject Generation

# 摘要

> 作为文本转图像模型的前沿技术，最新的多模态扩散变压器（MMDiT）极大地缓解了以往模型存在的诸多生成问题。然而，我们发现当输入的文本提示包含多个语义或外观相近的主题时，它仍会出现主题被忽略或混淆的情况。我们在 MMDiT 架构中找出了导致这一问题的三种可能的歧义：块间歧义、文本编码器歧义以及语义歧义。为解决这些问题，我们提议在早期去噪步骤中通过测试时优化来即时修复模糊的潜在表示。具体而言，我们设计了三个损失函数：块对齐损失、文本编码器对齐损失和重叠损失，每个函数均旨在减轻这些歧义。尽管有了显著改进，但我们观察到在生成多个相似主题时语义歧义仍存在，因为重叠损失提供的引导不够清晰。所以，我们进一步提出了重叠在线检测和回到起点采样策略来缓解该问题。在新构建的具有挑战性的相似主题数据集上的实验结果验证了我们方法的有效性，展现出比现有方法更出色的生成质量和更高的成功率。我们的代码将在 https://github.com/wtybest/EnMMDiT 上提供。

> Representing the cutting-edge technique of text-to-image models, the latest Multimodal Diffusion Transformer (MMDiT) largely mitigates many generation issues existing in previous models. However, we discover that it still suffers from subject neglect or mixing when the input text prompt contains multiple subjects of similar semantics or appearance. We identify three possible ambiguities within the MMDiT architecture that cause this problem: Inter-block Ambiguity, Text Encoder Ambiguity, and Semantic Ambiguity. To address these issues, we propose to repair the ambiguous latent on-the-fly by test-time optimization at early denoising steps. In detail, we design three loss functions: Block Alignment Loss, Text Encoder Alignment Loss, and Overlap Loss, each tailored to mitigate these ambiguities. Despite significant improvements, we observe that semantic ambiguity persists when generating multiple similar subjects, as the guidance provided by overlap loss is not explicit enough. Therefore, we further propose Overlap Online Detection and Back-to-Start Sampling Strategy to alleviate the problem. Experimental results on a newly constructed challenging dataset of similar subjects validate the effectiveness of our approach, showing superior generation quality and much higher success rates over existing methods. Our code will be available at https://github.com/wtybest/EnMMDiT.

[Arxiv](https://arxiv.org/abs/2411.18301)