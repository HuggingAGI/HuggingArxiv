# 探究多模态长文本摘要：以金融报告分析为例

发布时间：2024年04月09日

`LLM应用` `文本摘要`

> Characterizing Multimodal Long-form Summarization: A Case Study on Financial Reports

# 摘要

> 随着大型语言模型不断增强自然语言处理长文本的能力，深入分析其性能和行为变得至关重要。以摘要生成为例，它因其普遍性和争议性（如一些研究者宣称摘要生成已死）而备受关注。本文以财务报告摘要为研究案例，探讨了其长篇幅和大量使用数字与表格的特点。我们构建了一个计算框架，用以刻画多模态长文本摘要，并考察了Claude 2.0/2.1、GPT-4/3.5和Command的表现。结果显示，GPT-3.5和Command在这项摘要任务上表现欠佳。对于Claude 2和GPT-4，我们深入分析了摘要的质量，并发现了LLM中存在的位置偏好。有趣的是，当输入文本顺序被打乱后，Claude的位置偏好消失了，这表明它能够辨识关键信息。此外，我们还全面研究了LLM生成摘要中数字数据的使用情况，并提出了数字误读的分类。尽管我们尝试通过提示工程提升GPT-4处理数字的能力，但效果有限。总的来说，我们的研究显示，相较于GPT-4，Claude 2在处理长篇幅多模态输入方面展现出更强大的能力。

> As large language models (LLMs) expand the power of natural language processing to handle long inputs, rigorous and systematic analyses are necessary to understand their abilities and behavior. A salient application is summarization, due to its ubiquity and controversy (e.g., researchers have declared the death of summarization). In this paper, we use financial report summarization as a case study because financial reports not only are long but also use numbers and tables extensively. We propose a computational framework for characterizing multimodal long-form summarization and investigate the behavior of Claude 2.0/2.1, GPT-4/3.5, and Command. We find that GPT-3.5 and Command fail to perform this summarization task meaningfully. For Claude 2 and GPT-4, we analyze the extractiveness of the summary and identify a position bias in LLMs. This position bias disappears after shuffling the input for Claude, which suggests that Claude has the ability to recognize important information. We also conduct a comprehensive investigation on the use of numeric data in LLM-generated summaries and offer a taxonomy of numeric hallucination. We employ prompt engineering to improve GPT-4's use of numbers with limited success. Overall, our analyses highlight the strong capability of Claude 2 in handling long multimodal inputs compared to GPT-4.

![探究多模态长文本摘要：以金融报告分析为例](../../../paper_images/2404.06162/x1.png)

![探究多模态长文本摘要：以金融报告分析为例](../../../paper_images/2404.06162/x2.png)

![探究多模态长文本摘要：以金融报告分析为例](../../../paper_images/2404.06162/x3.png)

![探究多模态长文本摘要：以金融报告分析为例](../../../paper_images/2404.06162/x4.png)

[Arxiv](https://arxiv.org/abs/2404.06162)