# 利用大型语言模型对文本进行丰富和改写，可以有效提升嵌入技术的表现。

发布时间：2024年04月18日

`LLM应用` `文本嵌入`

> Enhancing Embedding Performance through Large Language Model-based Text Enrichment and Rewriting

# 摘要

> 嵌入模型在自然语言处理的多个任务中发挥着关键作用，但它们可能因词汇限制、上下文缺失和语法错误等因素而受限。本研究提出了一种创新的改进方法，即在嵌入之前，通过大型语言模型（LLMs）来丰富和改写输入文本，以提升嵌入效果。利用ChatGPT 3.5为文本增添额外上下文、纠正错误并整合元数据，旨在提高嵌入模型的效用和精确度。该方法在三个不同的数据集上进行了测试：Banking77Classification、TwitterSemEval 2015和Amazon Counter-factual Classification。在TwitterSemEval 2015数据集上，该方法相较于基线模型实现了显著的性能提升，在Massive Text Embedding Benchmark（MTEB）排行榜上得分高达85.34，刷新了此前81.52的记录。然而，其他两个数据集的提升效果并不显著，这强调了考虑领域特定特性的必要性。研究结果表明，基于LLM的文本增强在提升嵌入性能方面取得了积极进展，尤其是在特定领域。因此，可以规避嵌入过程中的许多限制。

> Embedding models are crucial for various natural language processing tasks but can be limited by factors such as limited vocabulary, lack of context, and grammatical errors. This paper proposes a novel approach to improve embedding performance by leveraging large language models (LLMs) to enrich and rewrite input text before the embedding process. By utilizing ChatGPT 3.5 to provide additional context, correct inaccuracies, and incorporate metadata, the proposed method aims to enhance the utility and accuracy of embedding models. The effectiveness of this approach is evaluated on three datasets: Banking77Classification, TwitterSemEval 2015, and Amazon Counter-factual Classification. Results demonstrate significant improvements over the baseline model on the TwitterSemEval 2015 dataset, with the best-performing prompt achieving a score of 85.34 compared to the previous best of 81.52 on the Massive Text Embedding Benchmark (MTEB) Leaderboard. However, performance on the other two datasets was less impressive, highlighting the importance of considering domain-specific characteristics. The findings suggest that LLM-based text enrichment has shown promising results to improve embedding performance, particularly in certain domains. Hence, numerous limitations in the process of embedding can be avoided.

[Arxiv](https://arxiv.org/abs/2404.12283)