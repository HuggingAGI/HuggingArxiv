# 融合语言模型：实现跨分词器的零-shot 适配器发现，优化提示效果

发布时间：2024年08月08日

`LLM应用` `计算机视觉`

> FUSE-ing Language Models: Zero-Shot Adapter Discovery for Prompt Optimization Across Tokenizers

# 摘要

> 随着大型语言模型的普及，多种分词器和嵌入空间的出现使得知识转移变得复杂。为此，我们推出了FUSE（灵活的语义嵌入统一），一种经济高效的方法，旨在构建一个适配器层，实现不同模型间甚至跨分词器的嵌入空间转换。我们创新性地采用三阶张量来表示模型嵌入空间，有效对齐了因分词器差异而分散的语义嵌入，并据此推导出模型间嵌入空间梯度的近似值。通过在视觉-语言和因果语言模型上实施多目标优化，应用于图像描述和情感驱动的图像描述任务，我们验证了FUSE方法的实际效果。

> The widespread use of large language models has resulted in a multitude of tokenizers and embedding spaces, making knowledge transfer in prompt discovery tasks difficult. In this work, we propose FUSE (Flexible Unification of Semantic Embeddings), an inexpensive approach to approximating an adapter layer that maps from one model's textual embedding space to another, even across different tokenizers. We introduce a third-order tensor-based representation of a model's embedding space that aligns semantic embeddings that have been split apart by different tokenizers, and use this representation to derive an approximation of the gradient of one model's outputs with respect to another model's embedding space. We show the efficacy of our approach via multi-objective optimization over vision-language and causal language models for image captioning and sentiment-based image captioning.

[Arxiv](https://arxiv.org/abs/2408.04816)