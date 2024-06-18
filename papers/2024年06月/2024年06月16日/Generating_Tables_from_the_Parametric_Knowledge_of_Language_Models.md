# 利用语言模型的参数知识生成表格

发布时间：2024年06月16日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在生成事实准确的结构化表格方面的应用，特别是在金融和医疗等关键领域。它通过实验评估了不同LLMs的表格生成能力，并创建了一个新的基准WikiTabGen来评估这些模型的性能。论文的重点在于应用层面，即如何利用LLMs来生成高质量的结构化数据，而不是探讨LLMs的理论基础或Agent的设计与实现。因此，它更适合归类为LLM应用。`

> Generating Tables from the Parametric Knowledge of Language Models

# 摘要

> 我们研究如何利用大型语言模型（LLMs）的参数知识生成事实准确的结构化表格，这在金融和医疗等关键领域尤为重要。我们测试了GPT-3.5、GPT-4、Llama2-13B和Llama2-70B这四种顶尖LLMs的表格生成能力，并采用了全表、逐行和逐单元格三种提示策略。为了准确评估，我们创建了WikiTabGen这一新基准，包含100个精心挑选的维基百科表格，并确保其内容的事实正确性，同时附有手动编写的自然语言描述。研究结果显示，尽管GPT-4的准确率最高，达到19.6%，但表格生成仍充满挑战。我们的深入分析揭示了表格属性如大小、流行度和数值内容对生成效果的影响。这项研究不仅揭示了LLM在表格生成方面的独特挑战，还为后续研究提供了一个全面的评估框架。所有相关代码、提示和数据已公开发布：https://github.com/analysis-bots/WikiTabGen

> We explore generating factual and accurate tables from the parametric knowledge of large language models (LLMs). While LLMs have demonstrated impressive capabilities in recreating knowledge bases and generating free-form text, we focus on generating structured tabular data, which is crucial in domains like finance and healthcare. We examine the table generation abilities of four state-of-the-art LLMs: GPT-3.5, GPT-4, Llama2-13B, and Llama2-70B, using three prompting methods for table generation: (a) full-table, (b) row-by-row; (c) cell-by-cell. For evaluation, we introduce a novel benchmark, WikiTabGen which contains 100 curated Wikipedia tables. Tables are further processed to ensure their factual correctness and manually annotated with short natural language descriptions. Our findings reveal that table generation remains a challenge, with GPT-4 reaching the highest accuracy at 19.6%. Our detailed analysis sheds light on how various table properties, such as size, table popularity, and numerical content, influence generation performance. This work highlights the unique challenges in LLM-based table generation and provides a solid evaluation framework for future research. Our code, prompts and data are all publicly available: https://github.com/analysis-bots/WikiTabGen

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x1.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x2.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x3.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x4.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x5.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x6.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x7.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/cost.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x8.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x9.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x10.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x11.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x12.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x13.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x14.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x15.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x16.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x17.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x18.png)

![利用语言模型的参数知识生成表格](../../../paper_images/2406.10922/x19.png)

[Arxiv](https://arxiv.org/abs/2406.10922)