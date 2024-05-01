# 探索奥克西唐方言拼写变异的建模研究

发布时间：2024年04月30日

`分类：LLM应用

这篇论文主要研究了多语言模型在处理低资源语言（特别是奥克西唐方言）时的表现，以及如何通过微调模型来提高对这些方言的理解和表征。论文还探讨了模型在不同方言之间的性能差异，以及如何减少对拼写归一化的依赖。这些研究内容都与大型语言模型（LLM）的应用相关，因此将其归类为LLM应用。` `语言学研究`

> Modeling Orthographic Variation in Occitan's Dialects

# 摘要

> 文本数据的有效归一化尤其对于缺乏统一书写系统的低资源语言来说是一个重大挑战。本研究中，我们针对几种奥克西唐方言的数据对一个多语言模型进行了微调，并通过一系列实验来评估模型对这些方言的理解和表征。为了评估，我们创建了一个包含四种奥克西唐方言的对照词汇库。模型嵌入的内在评估显示，方言间的表面相似性有助于加强模型的表征能力。此外，当模型进一步针对词性标注和通用依存句法分析进行微调时，即便仅使用单一方言的词性数据进行训练，其性能也能稳定应对方言差异。研究结果表明，大型多语言模型能够在预处理阶段减少对拼写归一化的依赖。

> Effectively normalizing textual data poses a considerable challenge, especially for low-resource languages lacking standardized writing systems. In this study, we fine-tuned a multilingual model with data from several Occitan dialects and conducted a series of experiments to assess the model's representations of these dialects. For evaluation purposes, we compiled a parallel lexicon encompassing four Occitan dialects. Intrinsic evaluations of the model's embeddings revealed that surface similarity between the dialects strengthened representations. When the model was further fine-tuned for part-of-speech tagging and Universal Dependency parsing, its performance was robust to dialectical variation, even when trained solely on part-of-speech data from a single dialect. Our findings suggest that large multilingual models minimize the need for spelling normalization during pre-processing.

[Arxiv](https://arxiv.org/abs/2404.19315)