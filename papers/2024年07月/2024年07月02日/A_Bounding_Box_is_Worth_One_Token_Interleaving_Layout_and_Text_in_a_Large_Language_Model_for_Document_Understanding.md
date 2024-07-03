# 每个边界框等同于一个令牌，通过在大规模语言模型中交错布局与文本，我们实现了对文档的深入理解。

发布时间：2024年07月02日

`LLM应用` `文档处理` `视觉问答`

> A Bounding Box is Worth One Token: Interleaving Layout and Text in a Large Language Model for Document Understanding

# 摘要

> 近期研究显示，结合OCR文本和空间布局的LLMs在文档理解任务中表现出色。然而，现有方法在整合这两者时存在不足，如产生冗长文本或未能充分发挥LLMs的自回归优势。为此，我们提出了LayTextLLM，它通过将每个边界框映射为一个嵌入并与文本交错，巧妙规避了长序列问题，同时强化了自回归特性。LayTextLLM不仅优化了布局与文本的交互，还在KIE和VQA任务中展现了显著的性能提升。基准测试表明，与现有最先进模型相比，LayTextLLM在KIE任务上提升了27.0%，在VQA任务上提升了24.1%，同时在基于OCR的LLMs的KIE任务上也有15.5%的进步。

> Recently, many studies have demonstrated that exclusively incorporating OCR-derived text and spatial layouts with large language models (LLMs) can be highly effective for document understanding tasks. However, existing methods that integrate spatial layouts with text have limitations, such as producing overly long text sequences or failing to fully leverage the autoregressive traits of LLMs. In this work, we introduce Interleaving Layout and Text in a Large Language Model (LayTextLLM)} for document understanding. In particular, LayTextLLM projects each bounding box to a single embedding and interleaves it with text, efficiently avoiding long sequence issues while leveraging autoregressive traits of LLMs. LayTextLLM not only streamlines the interaction of layout and textual data but also shows enhanced performance in Key Information Extraction (KIE) and Visual Question Answering (VQA). Comprehensive benchmark evaluations reveal significant improvements, with a 27.0% increase on KIE tasks and 24.1% on VQA tasks compared to previous state-of-the-art document understanding MLLMs, as well as a 15.5% improvement over other SOTA OCR-based LLMs on KIE tasks.

[Arxiv](https://arxiv.org/abs/2407.01976)