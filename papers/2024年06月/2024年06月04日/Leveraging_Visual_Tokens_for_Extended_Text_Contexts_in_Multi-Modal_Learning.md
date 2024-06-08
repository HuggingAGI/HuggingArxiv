# 借助视觉令牌，拓展多模态学习中的文本上下文

发布时间：2024年06月04日

`LLM应用

这篇论文介绍了一种名为“可视化上下文文本处理（VisInContext）”的创新方法，该方法旨在高效扩展多模态大型语言模型（MLLMs）的上下文文本长度。这种方法通过使用视觉标记处理长文本，显著降低了GPU内存和浮点运算的需求，从而使得训练和推理过程更加高效。论文中提到的应用场景包括文档问答和顺序文档检索等，这些都是LLM技术的实际应用。因此，这篇论文应归类为LLM应用。` `文档处理` `多模态学习`

> Leveraging Visual Tokens for Extended Text Contexts in Multi-Modal Learning

# 摘要

> 在多模态模型中，训练具有更长上下文长度的模型面临巨大挑战，主要是因为高昂的GPU内存和计算成本。本研究并未展示最尖端的模型，而是提出了一种创新方法——可视化上下文文本处理（VisInContext），旨在高效扩展多模态大型语言模型（MLLMs）的上下文文本长度。通过使用视觉标记处理长文本，VisInContext在训练和推理中大幅降低了GPU内存和浮点运算的需求。例如，我们的方法成功将预训练上下文文本长度从256扩展至2048个标记，而对一个拥有56亿参数的MOE模型，其浮点运算量几乎不变。实验证明，采用VisInContext训练的模型在上下文少样本评估的下游任务中表现卓越。此外，VisInContext与现有技术相辅相成，显著提升了文档理解能力，预示着在文档问答和顺序文档检索等任务中的广阔应用前景。

> Training models with longer in-context lengths is a significant challenge for multimodal model due to substantial GPU memory and computational costs. This exploratory study does not present state-of-the-art models; rather, it introduces an innovative method designed to increase in-context text length in multi-modality large language models (MLLMs) efficiently. We present Visualized In-Context Text Processing (VisInContext), which processes long in-context text using visual tokens. This technique significantly reduces GPU memory usage and floating point operations (FLOPs) for both training and inferenceing stage. For instance, our method expands the pre-training in-context text length from 256 to 2048 tokens with nearly same FLOPs for a 56 billion parameter MOE model. Experimental results demonstrate that model trained with VisInContext delivers superior performance on common downstream benchmarks for in-context few-shot evaluation. Additionally, VisInContext is complementary to existing methods for increasing in-context text length and enhances document understanding capabilities, showing great potential in document QA tasks and sequential document retrieval.

[Arxiv](https://arxiv.org/abs/2406.02547)