# 在利用GPT模型评估相关性时，精准捕捉提示中的关键术语至关重要。本研究聚焦于如何有效地识别这些关键术语，以提升模型在相关性评估中的准确性和效率。

发布时间：2024年05月11日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在信息检索领域中的相关性评估任务，特别是在提示设计对模型效能的影响方面。研究关注了提示中特定词汇对LLMs评估相关性的积极或消极影响，并通过实验对比了不同提示设计在少样本和零样本场景下的表现。这表明了LLMs在实际应用中的一个具体场景，即如何通过优化提示设计来提高信息检索的相关性评估性能。因此，这篇论文属于LLM应用分类。` `信息检索`

> Identifying Key Terms in Prompts for Relevance Evaluation with GPT Models

# 摘要

> 在信息检索领域，查询与段落的相关性评估是核心任务。近期，借助GPT-4等大型语言模型，相关性判断任务取得了显著进展。然而，这些模型的效能深受提示设计的影响。本研究旨在揭示提示中哪些特定词汇对LLMs的相关性评估产生积极或消极影响。我们采用了两类提示：一类沿用前人研究，另一类由LLMs自动生成。通过对比这些提示在少样本和零样本场景下的表现，我们探究了提示中词汇的具体影响。研究发现两点关键：首先，使用“answer”一词的提示在相关性评估上更为有效，这表明直接针对查询的回答策略能提升性能。其次，相关性范围的适度平衡至关重要。“relevant”一词可能使范围过宽，导致评估不够精准，而找到相关性的最佳平衡点是确保评估准确性的关键。少样本示例的引入有助于更精确地界定这一平衡，为“relevant”提供更明确的语境，从而细化相关性标准。综上所述，本研究强调了在LLMs进行相关性评估时，精心挑选提示词汇的重要性。

> Relevance evaluation of a query and a passage is essential in Information Retrieval (IR). Recently, numerous studies have been conducted on tasks related to relevance judgment using Large Language Models (LLMs) such as GPT-4, demonstrating significant improvements. However, the efficacy of LLMs is considerably influenced by the design of the prompt. The purpose of this paper is to identify which specific terms in prompts positively or negatively impact relevance evaluation with LLMs. We employed two types of prompts: those used in previous research and generated automatically by LLMs. By comparing the performance of these prompts in both few-shot and zero-shot settings, we analyze the influence of specific terms in the prompts. We have observed two main findings from our study. First, we discovered that prompts using the term answerlead to more effective relevance evaluations than those using relevant. This indicates that a more direct approach, focusing on answering the query, tends to enhance performance. Second, we noted the importance of appropriately balancing the scope of relevance. While the term relevant can extend the scope too broadly, resulting in less precise evaluations, an optimal balance in defining relevance is crucial for accurate assessments. The inclusion of few-shot examples helps in more precisely defining this balance. By providing clearer contexts for the term relevance, few-shot examples contribute to refine relevance criteria. In conclusion, our study highlights the significance of carefully selecting terms in prompts for relevance evaluation with LLMs.

[Arxiv](https://arxiv.org/abs/2405.06931)