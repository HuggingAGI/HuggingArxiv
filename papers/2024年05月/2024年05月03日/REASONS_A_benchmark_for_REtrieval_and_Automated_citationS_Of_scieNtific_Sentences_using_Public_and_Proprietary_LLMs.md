# REASONS：一个基准测试，旨在利用公共及私有的大型语言模型（LLMs）检索并自动引用科学文献中的句子。

发布时间：2024年05月03日

`分类：RAG

这篇论文探讨了大型语言模型（LLMs）在自动化引用生成任务中的应用，特别是研究了高级检索增强生成（RAG）在处理间接查询时的性能。论文中提到了对公共和专有的 LLMs 进行了分析，并比较了不同模型在减少幻觉率（HR）和通过率（PP）方面的表现。此外，还提到了通过对抗性样本的测试来评估 LLMs 在理解上下文方面的挑战。这些内容都与 RAG 技术的应用和性能评估相关，因此将这篇论文归类为 RAG。` `情报分析` `网络安全`

> REASONS: A benchmark for REtrieval and Automated citationS Of scieNtific Sentences using Public and Proprietary LLMs

# 摘要

> 自动生成文档或报告中句子的引用对于情报分析、网络安全、新闻机构和教育工作者极为重要。本研究探讨了大型语言模型（LLMs）是否能够根据两种查询形式生成参考文献：(a) 直接查询，要求模型提供特定研究文章的作者名；(b) 间接查询，要求模型根据来自不同文章的句子提供被引用文章的标题。为了评估 LLMs 在此任务上的表现，我们创建了一个名为 REASONS 的大型数据集，涵盖了 arXiv 上科学研究成果最丰富的 12 个领域的摘要，覆盖约 20,000 篇研究文章。我们对公共和专有的 LLMs 进行了分析，得出以下结论：(a) 被称为具有人类特质的先进模型 GPT-4 和 GPT-3.5，尽管在减少幻觉率（HR）方面表现出色，但在 Perplexity.ai（7B）的测试中意外出现了更多错误；(b) 添加相关元数据有效降低了通过率（PP）并最小化了 HR；(c) 使用 Mistral 的高级检索增强生成（RAG）在处理间接查询时展现出了稳定且强大的引用生成能力，其性能与 GPT-3.5 和 GPT-4 相当。所有领域和模型的平均 HR 下降了 41.93%，而 PP 在大多数情况下降至 0%。就生成质量而言，平均 F1 分数和 BLEU 分数分别为 68.09% 和 57.51%；(d) 通过对抗性样本的测试显示，包括高级 RAG Mistral 在内的 LLMs 在理解上下文方面存在挑战，但在 Mistral 和 GPT-4-Preview 中这一问题的影响较小。我们的研究为 RAG 在自动化引用生成任务的可靠性提供了重要的洞见。

> Automatic citation generation for sentences in a document or report is paramount for intelligence analysts, cybersecurity, news agencies, and education personnel. In this research, we investigate whether large language models (LLMs) are capable of generating references based on two forms of sentence queries: (a) Direct Queries, LLMs are asked to provide author names of the given research article, and (b) Indirect Queries, LLMs are asked to provide the title of a mentioned article when given a sentence from a different article. To demonstrate where LLM stands in this task, we introduce a large dataset called REASONS comprising abstracts of the 12 most popular domains of scientific research on arXiv. From around 20K research articles, we make the following deductions on public and proprietary LLMs: (a) State-of-the-art, often called anthropomorphic GPT-4 and GPT-3.5, suffers from high pass percentage (PP) to minimize the hallucination rate (HR). When tested with Perplexity.ai (7B), they unexpectedly made more errors; (b) Augmenting relevant metadata lowered the PP and gave the lowest HR; (c) Advance retrieval-augmented generation (RAG) using Mistral demonstrates consistent and robust citation support on indirect queries and matched performance to GPT-3.5 and GPT-4. The HR across all domains and models decreased by an average of 41.93% and the PP was reduced to 0% in most cases. In terms of generation quality, the average F1 Score and BLEU were 68.09% and 57.51%, respectively; (d) Testing with adversarial samples showed that LLMs, including the Advance RAG Mistral, struggle to understand context, but the extent of this issue was small in Mistral and GPT-4-Preview. Our study con tributes valuable insights into the reliability of RAG for automated citation generation tasks.

[Arxiv](https://arxiv.org/abs/2405.02228)