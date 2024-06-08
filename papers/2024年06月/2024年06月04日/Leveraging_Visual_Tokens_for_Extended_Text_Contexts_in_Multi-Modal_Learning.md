# 借助视觉令牌，拓展多模态学习中的文本上下文

发布时间：2024年06月04日

`LLM理论

理由：这篇论文探讨了多模态大型语言模型中上下文长度的扩展问题，并提出了一种新的方法（VisInContext）来解决这一问题。这种方法涉及到模型的内部结构和训练过程的优化，属于对大型语言模型理论层面的研究。虽然这种方法可能具有实际应用的潜力，但其核心贡献在于理论创新和模型性能的提升，因此更适合归类为LLM理论。` `机器学习` `文档处理`

> Leveraging Visual Tokens for Extended Text Contexts in Multi-Modal Learning

# 摘要

> 在多模态大型语言模型中，训练具有更长上下文长度的模型面临着GPU内存和计算成本的巨大挑战。本研究并未追求最先进的技术，而是创新性地提出了可视化上下文文本处理（VisInContext），一种通过视觉标记高效扩展上下文文本长度的方法。这种方法在训练和推理过程中大幅降低了GPU内存和浮点运算的需求。例如，我们成功将一个56亿参数MOE模型的预训练上下文长度从256扩展至2048个标记，而FLOPs几乎保持不变。实验证明，采用VisInContext训练的模型在少样本评估的下游任务中表现卓越。此外，VisInContext不仅与现有技术相辅相成，还显著提升了文档理解能力，预示着在文档问答和顺序文档检索等任务中的广阔应用前景。

> Training models with longer in-context lengths is a significant challenge for multimodal model due to substantial GPU memory and computational costs. This exploratory study does not present state-of-the-art models; rather, it introduces an innovative method designed to increase in-context text length in multi-modality large language models (MLLMs) efficiently. We present Visualized In-Context Text Processing (VisInContext), which processes long in-context text using visual tokens. This technique significantly reduces GPU memory usage and floating point operations (FLOPs) for both training and inferenceing stage. For instance, our method expands the pre-training in-context text length from 256 to 2048 tokens with nearly same FLOPs for a 56 billion parameter MOE model. Experimental results demonstrate that model trained with VisInContext delivers superior performance on common downstream benchmarks for in-context few-shot evaluation. Additionally, VisInContext is complementary to existing methods for increasing in-context text length and enhances document understanding capabilities, showing great potential in document QA tasks and sequential document retrieval.

[Arxiv](https://arxiv.org/abs/2406.02547)