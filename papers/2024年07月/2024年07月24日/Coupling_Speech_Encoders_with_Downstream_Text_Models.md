# 融合语音编码器与文本模型下游应用

发布时间：2024年07月24日

`LLM应用` `语音识别` `翻译技术`

> Coupling Speech Encoders with Downstream Text Models

# 摘要

> 我们创新性地提出了一种模块化方法，用于构建级联语音翻译模型，确保其性能不低于最佳级联基线，同时保持顶尖的语音识别和文本翻译能力。核心创新在于引入“导出器”层，通过 L2 损失训练，精准匹配 ASR 与 MT 的嵌入。这些输出嵌入直接替代最佳令牌嵌入输入 MT 模型，不仅性能不减，还允许梯度从 MT 回流至 ASR。在无法增量训练 MT 模型的情况下，这种匹配嵌入的级联架构显著提升了翻译质量。然而，一旦 MT 模型得以增量训练，这种优势便不复存在。此方法对于结合 ASR 与固定文本模型的应用，如大型语言模型，具有广阔前景。

> We present a modular approach to building cascade speech translation (AST) models that guarantees that the resulting model performs no worse than the 1-best cascade baseline while preserving state-of-the-art speech recognition (ASR) and text translation (MT) performance for a given task. Our novel contribution is the use of an ``exporter'' layer that is trained under L2-loss to ensure a strong match between ASR embeddings and the MT token embeddings for the 1-best sequence. The ``exporter'' output embeddings are fed directly to the MT model in lieu of 1-best token embeddings, thus guaranteeing that the resulting model performs no worse than the 1-best cascade baseline, while allowing back-propagation gradient to flow from the MT model into the ASR components. The matched-embeddings cascade architecture provide a significant improvement over its 1-best counterpart in scenarios where incremental training of the MT model is not an option and yet we seek to improve quality by leveraging (speech, transcription, translated transcription) data provided with the AST task. The gain disappears when the MT model is incrementally trained on the parallel text data available with the AST task. The approach holds promise for other scenarios that seek to couple ASR encoders and immutable text models, such at large language models (LLM).

![融合语音编码器与文本模型下游应用](../../../paper_images/2407.17605/x1.png)

![融合语音编码器与文本模型下游应用](../../../paper_images/2407.17605/x2.png)

[Arxiv](https://arxiv.org/abs/2407.17605)