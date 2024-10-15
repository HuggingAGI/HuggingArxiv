# Text4Seg：重塑图像分割为文本生成

发布时间：2024年10月13日

`LLM应用` `计算机视觉`

> Text4Seg: Reimagining Image Segmentation as Text Generation

# 摘要

> 多模态大型语言模型 (MLLM) 在视觉-语言任务中表现出色，但如何有效整合图像分割仍是一大难题。本文提出 Text4Seg，一种将图像分割转化为文本生成的新方法，无需额外解码器，大幅简化分割流程。核心创新在于语义描述符，一种将图像块映射到文本标签的新型表示，便于无缝融入 MLLM 的自回归训练。实验证明，使用 $16\times16$ 语义描述符即可实现优异的分割效果。为提升效率，引入行式游程编码 (R-RLE)，压缩冗余文本，减少描述符长度 74%，推理速度提升三倍，性能不受影响。在引用表达分割等任务中，Text4Seg 通过微调不同 MLLM 骨干网络，已在多个数据集上达到最先进水平。本方法为 MLLM 框架内的视觉任务提供了高效、可扩展的解决方案。

> Multimodal Large Language Models (MLLMs) have shown exceptional capabilities in vision-language tasks; however, effectively integrating image segmentation into these models remains a significant challenge. In this paper, we introduce Text4Seg, a novel text-as-mask paradigm that casts image segmentation as a text generation problem, eliminating the need for additional decoders and significantly simplifying the segmentation process. Our key innovation is semantic descriptors, a new textual representation of segmentation masks where each image patch is mapped to its corresponding text label. This unified representation allows seamless integration into the auto-regressive training pipeline of MLLMs for easier optimization. We demonstrate that representing an image with $16\times16$ semantic descriptors yields competitive segmentation performance. To enhance efficiency, we introduce the Row-wise Run-Length Encoding (R-RLE), which compresses redundant text sequences, reducing the length of semantic descriptors by 74% and accelerating inference by $3\times$, without compromising performance. Extensive experiments across various vision tasks, such as referring expression segmentation and comprehension, show that Text4Seg achieves state-of-the-art performance on multiple datasets by fine-tuning different MLLM backbones. Our approach provides an efficient, scalable solution for vision-centric tasks within the MLLM framework.

[Arxiv](https://arxiv.org/abs/2410.09855)