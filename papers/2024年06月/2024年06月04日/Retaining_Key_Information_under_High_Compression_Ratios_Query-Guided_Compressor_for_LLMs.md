# 在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。

发布时间：2024年06月04日

`RAG

理由：这篇论文主要关注的是大型语言模型（LLM）中的上下文压缩技术，特别是通过开发查询引导压缩器（QGC）来优化压缩过程，以保留关键信息。这种方法与检索增强生成（RAG）模型中的技术相似，后者也依赖于优化信息检索和生成过程以提高性能。因此，这篇论文更适合归类于RAG，因为它专注于通过改进压缩技术来增强LLM的性能，这与RAG的核心目标相符。` `问答系统`

> Retaining Key Information under High Compression Ratios: Query-Guided Compressor for LLMs

# 摘要

> 随着大型语言模型的流行，人们开始关注其上下文压缩技术。然而，以往的方法在压缩比提高时性能大幅下降，有时甚至退化到闭卷水平，这主要是因为压缩过程中丢失了关键信息。我们的初步研究证实了这一点，强调了在高压缩比下保留关键信息的重要性。为此，我们开发了查询引导压缩器（QGC），它通过查询来优化压缩过程，确保关键信息得以保留。我们还采用了动态压缩策略。在问答任务上，包括NaturalQuestions、TriviaQA和HotpotQA数据集，QGC的实验结果显示，即使在极高的压缩比下，它也能保持优异性能，同时显著降低了推理成本和提高了吞吐量。

> The growing popularity of Large Language Models has sparked interest in context compression for Large Language Models (LLMs). However, the performance of previous methods degrades dramatically as compression ratios increase, sometimes even falling to the closed-book level. This decline can be attributed to the loss of key information during the compression process. Our preliminary study supports this hypothesis, emphasizing the significance of retaining key information to maintain model performance under high compression ratios. As a result, we introduce Query-Guided Compressor (QGC), which leverages queries to guide the context compression process, effectively preserving key information within the compressed context. Additionally, we employ a dynamic compression strategy. We validate the effectiveness of our proposed QGC on the Question Answering task, including NaturalQuestions, TriviaQA, and HotpotQA datasets. Experimental results show that QGC can consistently perform well even at high compression ratios, which also offers significant benefits in terms of inference cost and throughput.

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。](../../../paper_images/2406.02376/x1.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。](../../../paper_images/2406.02376/x2.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。](../../../paper_images/2406.02376/x3.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。](../../../paper_images/2406.02376/x4.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。](../../../paper_images/2406.02376/x5.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。](../../../paper_images/2406.02376/x6.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。](../../../paper_images/2406.02376/x7.png)

![在极高压缩比下，如何确保关键信息不丢失？针对LLMs的查询引导压缩器，正是解决这一难题的关键。](../../../paper_images/2406.02376/x8.png)

[Arxiv](https://arxiv.org/abs/2406.02376)