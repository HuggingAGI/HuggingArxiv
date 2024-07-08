# 元提示优化检索增强生成技术

发布时间：2024年07月04日

`RAG` `问答系统` `人工智能`

> Meta-prompting Optimized Retrieval-augmented Generation

# 摘要

> 检索增强生成通过利用外部检索内容提升大型语言模型在下游任务中的表现。然而，检索内容过多或分散可能导致负面效果。为此，我们提出一种通过元提示优化精炼检索内容的方法，以提升生成质量。在StrategyQA数据集的多跳问答任务中，该方法表现优于传统检索增强系统30%以上。

> Retrieval-augmented generation resorts to content retrieved from external sources in order to leverage the performance of large language models in downstream tasks. The excessive volume of retrieved content, the possible dispersion of its parts, or their out of focus range may happen nevertheless to eventually have a detrimental rather than an incremental effect. To mitigate this issue and improve retrieval-augmented generation, we propose a method to refine the retrieved content before it is included in the prompt by resorting to meta-prompting optimization. Put to empirical test with the demanding multi-hop question answering task from the StrategyQA dataset, the evaluation results indicate that this method outperforms a similar retrieval-augmented system but without this method by over 30%.

[Arxiv](https://arxiv.org/abs/2407.03955)