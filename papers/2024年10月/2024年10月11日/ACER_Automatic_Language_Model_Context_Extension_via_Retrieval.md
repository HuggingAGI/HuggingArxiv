# ACER：利用检索技术自动扩展语言模型的上下文

发布时间：2024年10月11日

`RAG` `人工智能`

> ACER: Automatic Language Model Context Extension via Retrieval

# 摘要

> 长上下文建模是语言AI处理复杂信息的核心能力。实践中，这种能力通常通过预训练语言模型的上下文扩展阶段实现，旨在打造通用长上下文能力。然而，我们初步实验发现，现有开源通用长上下文模型在实际任务中表现欠佳。这意味着完全有效的长上下文建模需要特定任务数据，但成本高昂。本文受人类处理大量信息方式的启发：通过有损**检索**阶段筛选文档，读者仅深入阅读精选内容。我们构建了**自动**数据合成管道，模拟这一过程，并使用短上下文LM生成数据，进一步调整以获得特定任务的长上下文能力。类似预训练从不完美数据中学习，我们假设并证明，短上下文模型可通过合成数据引导，不仅超越通用长上下文模型，还在实际任务中如长上下文检索增强生成中，超越了用于合成训练数据的检索和阅读管道。

> Long-context modeling is one of the critical capabilities of language AI for digesting and reasoning over complex information pieces. In practice, long-context capabilities are typically built into a pre-trained language model~(LM) through a carefully designed context extension stage, with the goal of producing generalist long-context capabilities. In our preliminary experiments, however, we discovered that the current open-weight generalist long-context models are still lacking in practical long-context processing tasks. While this means perfectly effective long-context modeling demands task-specific data, the cost can be prohibitive. In this paper, we draw inspiration from how humans process a large body of information: a lossy \textbf{retrieval} stage ranks a large set of documents while the reader ends up reading deeply only the top candidates. We build an \textbf{automatic} data synthesis pipeline that mimics this process using short-context LMs. The short-context LMs are further tuned using these self-generated data to obtain task-specific long-context capabilities. Similar to how pre-training learns from imperfect data, we hypothesize and further demonstrate that the short-context model can bootstrap over the synthetic data, outperforming not only long-context generalist models but also the retrieval and read pipeline used to synthesize the training data in real-world tasks such as long-context retrieval augmented generation.

[Arxiv](https://arxiv.org/abs/2410.09141)