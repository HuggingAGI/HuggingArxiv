# LoRA - 用于长文档理解的大型多模态模型的情境化适配

发布时间：2024年11月01日

`LLM应用` `多模态` `文档处理`

> LoRA-Contextualizing Adaptation of Large Multimodal Models for Long Document Understanding

# 摘要

> 大型多模态模型（LMMs）近来在富含文本的图像理解领域进步显著，然而在应对复杂、多页且视觉内容丰富的文档时，仍力有不逮。采用文档解析器进行检索增强生成的传统手段，在性能和效率上存在局限，直接将所有页面呈现给 LMMs 会导致效率低下，对于长篇文档尤甚。在本研究中，我们推出了一个新颖的框架，名为大型多模态模型的 LoRA 情境化适配（LoCAL），它拓展了任意 LMM 的能力，使其能够支持对长文档的理解。我们证实 LMMs 能够有效地充当多模态检索器，依据这些页面获取相关页面以回答用户的问题。LoCAL 由两个特定的 LMM 适配器实现：一个用于证据页面检索，另一个用于回答问题。实证结果在公共基准测试中展现出了前沿水平的性能，彰显了 LoCAL 的有效性。

> Large multimodal models (LMMs) have recently shown great progress in text-rich image understanding, yet they still struggle with complex, multi-page, visually-rich documents. Traditional methods using document parsers for retrieval-augmented generation suffer from performance and efficiency limitations, while directly presenting all pages to LMMs leads to inefficiencies, especially with lengthy documents. In this work, we present a novel framework named LoRA-Contextualizing Adaptation of Large multimodal models (LoCAL), which broadens the capabilities of any LMM to support long-document understanding. We demonstrate that LMMs can effectively serve as multimodal retrievers, fetching relevant pages to answer user questions based on these pages. LoCAL is implemented with two specific LMM adapters: one for evidence page retrieval and another for question answering. Empirical results show state-of-the-art performance on public benchmarks, demonstrating the effectiveness of LoCAL.

[Arxiv](https://arxiv.org/abs/2411.01106)