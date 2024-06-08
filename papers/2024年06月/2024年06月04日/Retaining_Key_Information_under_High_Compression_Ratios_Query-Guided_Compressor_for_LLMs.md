# 在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。

发布时间：2024年06月04日

`RAG

理由：该论文主要关注的是大型语言模型（LLM）中的上下文压缩技术，特别是通过开发查询引导压缩器（QGC）来优化这一过程，以确保在压缩过程中保留关键信息。这种技术是针对LLM的特定应用，即在问答任务中提高性能和效率。因此，它属于RAG分类，即与检索增强生成（Retrieval-Augmented Generation）相关的技术，这类技术通常涉及通过查询优化信息检索和生成过程。` `问答系统`

> Retaining Key Information under High Compression Ratios: Query-Guided Compressor for LLMs

# 摘要

> 随着大型语言模型的普及，人们对其上下文压缩技术产生了浓厚兴趣。然而，以往的方法在压缩比提高时性能大幅下滑，有时甚至跌至闭卷水平，这主要是因为压缩过程中丢失了关键信息。我们的初步研究证实了这一点，强调了在高压缩比下保留关键信息对维持模型性能的重要性。为此，我们开发了查询引导压缩器（QGC），它通过查询来优化上下文压缩，确保关键信息在压缩后依然保留。我们还采用了动态压缩策略。在问答任务上，包括NaturalQuestions、TriviaQA和HotpotQA数据集，QGC的实验结果显示，即使在极高的压缩比下，它也能保持优异性能，同时大幅降低了推理成本和提高了吞吐量。

> The growing popularity of Large Language Models has sparked interest in context compression for Large Language Models (LLMs). However, the performance of previous methods degrades dramatically as compression ratios increase, sometimes even falling to the closed-book level. This decline can be attributed to the loss of key information during the compression process. Our preliminary study supports this hypothesis, emphasizing the significance of retaining key information to maintain model performance under high compression ratios. As a result, we introduce Query-Guided Compressor (QGC), which leverages queries to guide the context compression process, effectively preserving key information within the compressed context. Additionally, we employ a dynamic compression strategy. We validate the effectiveness of our proposed QGC on the Question Answering task, including NaturalQuestions, TriviaQA, and HotpotQA datasets. Experimental results show that QGC can consistently perform well even at high compression ratios, which also offers significant benefits in terms of inference cost and throughput.

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。](../../../paper_images/2406.02376/x1.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。](../../../paper_images/2406.02376/x2.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。](../../../paper_images/2406.02376/x3.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。](../../../paper_images/2406.02376/x4.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。](../../../paper_images/2406.02376/x5.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。](../../../paper_images/2406.02376/x6.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。](../../../paper_images/2406.02376/x7.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs，我们提出了一种查询引导的压缩器，旨在优化信息保留。](../../../paper_images/2406.02376/x8.png)

[Arxiv](https://arxiv.org/abs/2406.02376)