# [TEncDM项目旨在深入理解扩散模型在语言模型编码空间中的独特性质，研究其内在机制及影响效果。](https://arxiv.org/abs/2402.19097)

发布时间：2024年02月29日

`LLM应用`

> TEncDM: Understanding the Properties of Diffusion Model in the Space of Language Model Encodings

> 鉴于扩散模型在多个领域的广泛应用成效，诸多研究尝试将这一原理迁移至文本数据处理，然而至今尚无方法能企及大型语言模型的表现水准。本文深入剖析了文本扩散模型的核心组件，并创新性地引入了“文本编码扩散模型”（TEncDM）。与众不同的是，我们选择在语言模型编码空间而非通用的词嵌入空间中训练模型。此外，我们提议采用基于Transformer的解码器，巧妙利用上下文信息以实现文本重建。进一步的研究揭示了自条件化的价值，它可增强模型输出的力度，进而允许在推理阶段减少去噪步数。最终，在QQP与XSum两个下游文本生成任务上的实验证明，TEncDM相较于现存非自回归模型具有显著优势。

> Drawing inspiration from the success of diffusion models in various domains, numerous research papers proposed methods for adapting them to text data. Despite these efforts, none of them has managed to achieve the quality of the large language models. In this paper, we conduct a comprehensive analysis of key components of the text diffusion models and introduce a novel approach named Text Encoding Diffusion Model (TEncDM). Instead of the commonly used token embedding space, we train our model in the space of the language model encodings. Additionally, we propose to use a Transformer-based decoder that utilizes contextual information for text reconstruction. We also analyse self-conditioning and find that it increases the magnitude of the model outputs, allowing the reduction of the number of denoising steps at the inference stage. Evaluation of TEncDM on two downstream text generation tasks, QQP and XSum, demonstrates its superiority over existing non-autoregressive models.

[Arxiv](https://arxiv.org/abs/2402.19097)