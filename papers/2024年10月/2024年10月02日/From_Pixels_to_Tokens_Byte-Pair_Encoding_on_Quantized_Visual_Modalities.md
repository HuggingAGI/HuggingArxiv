# 从像素到标记：量化视觉模态中的字节对编码

发布时间：2024年10月02日

`LLM应用` `人工智能` `计算机视觉`

> From Pixels to Tokens: Byte-Pair Encoding on Quantized Visual Modalities

# 摘要

> 多模态大型语言模型在整合视觉和文本信息方面取得了显著进展，但它们往往难以有效地对齐这些模态。我们引入了一种新颖的图像标记器，通过将字节对编码（BPE）原理应用于视觉数据来弥合这一差距。与依赖于单独视觉编码器的传统方法不同，我们的方法直接将结构先验信息融入图像标记中，类似于仅使用文本的大型语言模型中成功的标记化策略。这种创新方法使Transformer模型能够更有效地跨模态学习和推理。通过理论分析和广泛的实验，我们证明我们的BPE图像标记器显著增强了MLLMs的多模态理解能力，即使在有限的训练数据下也是如此。我们的方法不仅在各种基准测试中提高了性能，还展示了良好的可扩展性，可能为更高效和强大的多模态基础模型铺平道路。

> Multimodal Large Language Models have made significant strides in integrating visual and textual information, yet they often struggle with effectively aligning these modalities. We introduce a novel image tokenizer that bridges this gap by applying the principle of Byte-Pair Encoding (BPE) to visual data. Unlike conventional approaches that rely on separate visual encoders, our method directly incorporates structural prior information into image tokens, mirroring the successful tokenization strategies used in text-only Large Language Models. This innovative approach enables Transformer models to more effectively learn and reason across modalities. Through theoretical analysis and extensive experiments, we demonstrate that our BPE Image Tokenizer significantly enhances MLLMs' multimodal understanding capabilities, even with limited training data. Our method not only improves performance across various benchmarks but also shows promising scalability, potentially paving the way for more efficient and capable multimodal foundation models.

[Arxiv](https://arxiv.org/abs/2410.02155)