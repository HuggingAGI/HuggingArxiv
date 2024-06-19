# Satyrn：分析赋能的生成平台

发布时间：2024年06月17日

`RAG

这篇论文主要介绍了一种名为分析增强生成（AAG）的新方法，该方法通过分析结构化数据来生成事实集，以指导大型语言模型（LLMs）在检索增强生成（RAG）中的文档生成。这种方法利用了神经符号平台Satyrn，并展示了在生成准确、流畅、连贯报告方面的有效性。因此，这篇论文的内容与RAG技术紧密相关，属于RAG分类。` `数据分析`

> Satyrn: A Platform for Analytics Augmented Generation

# 摘要

> 大型语言模型（LLMs）能生成文档，检索增强生成（RAG）有效提升准确性且不损流畅。但文本并非信息之源。我们提出新法，分析结构化数据以生成事实集，指导生成如RAG中检索文档。此分析增强生成（AAG）法，运用标准分析技术，生成事实转文本，供LLM使用。我们推出神经符号平台Satyrn，利用AAG，基于大数据库产出准确、流畅、连贯报告。实验显示，Satyrn报告准确率达86%，流畅连贯，即便用小模型如Mistral-7B，亦胜GPT-4 Code Interpreter的57%准确率。

> Large language models (LLMs) are capable of producing documents, and retrieval augmented generation (RAG) has shown itself to be a powerful method for improving accuracy without sacrificing fluency. However, not all information can be retrieved from text. We propose an approach that uses the analysis of structured data to generate fact sets that are used to guide generation in much the same way that retrieved documents are used in RAG. This analytics augmented generation (AAG) approach supports the ability to utilize standard analytic techniques to generate facts that are then converted to text and passed to an LLM. We present a neurosymbolic platform, Satyrn that leverages AAG to produce accurate, fluent, and coherent reports grounded in large scale databases. In our experiments, we find that Satyrn generates reports in which over 86% accurate claims while maintaining high levels of fluency and coherence, even when using smaller language models such as Mistral-7B, as compared to GPT-4 Code Interpreter in which just 57% of claims are accurate.

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x1.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x2.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x3.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x4.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x5.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x6.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x7.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x8.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x9.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x10.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x11.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x12.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x13.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x14.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x15.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x16.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x17.png)

![Satyrn：分析赋能的生成平台](../../../paper_images/2406.12069/x18.png)

[Arxiv](https://arxiv.org/abs/2406.12069)