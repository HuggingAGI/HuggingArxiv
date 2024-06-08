# 借助视觉令牌，拓展多模态学习中的文本上下文

发布时间：2024年06月04日

`LLM应用

理由：这篇论文介绍了一种名为“可视化上下文文本处理（VisInContext）”的方法，该方法旨在扩展多模态大型语言模型（MLLMs）的上下文文本长度，同时降低GPU内存和计算成本。这种方法的创新性和实用性使其直接应用于LLM的实际问题解决中，特别是在提高模型处理长文本能力方面。因此，它属于LLM应用类别。` `文档处理` `多模态学习`

> Leveraging Visual Tokens for Extended Text Contexts in Multi-Modal Learning

# 摘要

> 在多模态模型中，训练具有更长上下文长度的模型面临着GPU内存和计算成本的巨大挑战。本研究并未追求最先进的技术，而是创新性地提出了一种方法——可视化上下文文本处理（VisInContext），旨在高效扩展多模态大型语言模型（MLLMs）的上下文文本长度。通过使用视觉标记处理长文本，VisInContext显著降低了GPU内存和浮点运算的需求。例如，该方法将预训练上下文长度从256个标记扩展至2048个，而对56亿参数的MOE模型的计算负担几乎不变。实验证明，采用VisInContext训练的模型在少样本评估的下游任务中表现卓越。此外，VisInContext不仅与现有技术相辅相成，还提升了文档理解能力，预示着在文档问答和顺序文档检索等任务中的广阔应用前景。

> Training models with longer in-context lengths is a significant challenge for multimodal model due to substantial GPU memory and computational costs. This exploratory study does not present state-of-the-art models; rather, it introduces an innovative method designed to increase in-context text length in multi-modality large language models (MLLMs) efficiently. We present Visualized In-Context Text Processing (VisInContext), which processes long in-context text using visual tokens. This technique significantly reduces GPU memory usage and floating point operations (FLOPs) for both training and inferenceing stage. For instance, our method expands the pre-training in-context text length from 256 to 2048 tokens with nearly same FLOPs for a 56 billion parameter MOE model. Experimental results demonstrate that model trained with VisInContext delivers superior performance on common downstream benchmarks for in-context few-shot evaluation. Additionally, VisInContext is complementary to existing methods for increasing in-context text length and enhances document understanding capabilities, showing great potential in document QA tasks and sequential document retrieval.

[Arxiv](https://arxiv.org/abs/2406.02547)