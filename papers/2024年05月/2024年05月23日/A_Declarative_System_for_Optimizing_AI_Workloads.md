# 声明式系统：优化AI工作负载的利器

发布时间：2024年05月23日

`Agent

这篇论文介绍了一个名为Palimpzest的系统，该系统能够处理AI驱动的分析查询，并通过声明性语言定义查询。它利用成本优化框架来探索AI模型、提示技术和相关基础模型优化的搜索空间，以实现查询的最佳权衡。这个系统可以被视为一个智能Agent，因为它能够自主地处理和优化复杂的AI查询任务，而不需要程序员进行大量的手动决策。此外，论文中提到的系统在多个任务上的评估结果显示了其在性能和成本效益方面的优势，进一步支持了其作为Agent的分类。`

> A Declarative System for Optimizing AI Workloads

# 摘要

> 现代AI模型实现了长久以来的梦想：几乎可以处理任何类型数据的分析查询。过去，从公司文档中提取事实、从科学论文中提取数据或从图像和视频库中提取见解都是困难且昂贵的。如今的模型能够以高精度完成这些任务。然而，想要通过AI回答实质性查询的程序员必须协调大量模型、提示和数据操作。即使是单一查询，程序员也必须做出大量决策，如模型的选择、正确的推理方法、最具成本效益的推理硬件、理想的提示设计等。随着查询的变化，以及技术环境的快速演变，最佳决策集也会发生变化。本文介绍了Palimpzest系统，该系统允许任何人通过在声明性语言中定义查询来处理AI驱动的分析查询。该系统利用其成本优化框架——探索AI模型、提示技术和相关基础模型优化的搜索空间——以最佳权衡运行时间、财务成本和输出数据质量来实现查询。我们描述了AI驱动的分析任务的工作负载、Palimpzest使用的优化方法以及原型系统本身。我们在法律发现、房地产搜索和医疗模式匹配等任务上评估了Palimpzest。我们展示了，即使是我们简单的原型也提供了一系列吸引人的计划，其中一个比基线方法快3.3倍，便宜2.9倍，并且提供更好的数据质量。通过启用并行处理，Palimpzest可以相对于单线程GPT-4基线实现高达90.3倍的加速和9.1倍的成本降低，同时获得基线83.5%的F1分数，而用户无需额外工作。

> Modern AI models provide the key to a long-standing dream: processing analytical queries about almost any kind of data. Until recently, it was difficult and expensive to extract facts from company documents, data from scientific papers, or insights from image and video corpora. Today's models can accomplish these tasks with high accuracy. However, a programmer who wants to answer a substantive AI-powered query must orchestrate large numbers of models, prompts, and data operations. For even a single query, the programmer has to make a vast number of decisions such as the choice of model, the right inference method, the most cost-effective inference hardware, the ideal prompt design, and so on. The optimal set of decisions can change as the query changes and as the rapidly-evolving technical landscape shifts. In this paper we present Palimpzest, a system that enables anyone to process AI-powered analytical queries simply by defining them in a declarative language. The system uses its cost optimization framework -- which explores the search space of AI models, prompting techniques, and related foundation model optimizations -- to implement the query with the best trade-offs between runtime, financial cost, and output data quality. We describe the workload of AI-powered analytics tasks, the optimization methods that Palimpzest uses, and the prototype system itself. We evaluate Palimpzest on tasks in Legal Discovery, Real Estate Search, and Medical Schema Matching. We show that even our simple prototype offers a range of appealing plans, including one that is 3.3x faster, 2.9x cheaper, and offers better data quality than the baseline method. With parallelism enabled, Palimpzest can produce plans with up to a 90.3x speedup at 9.1x lower cost relative to a single-threaded GPT-4 baseline, while obtaining an F1-score within 83.5% of the baseline. These require no additional work by the user.

[Arxiv](https://arxiv.org/abs/2405.14696)