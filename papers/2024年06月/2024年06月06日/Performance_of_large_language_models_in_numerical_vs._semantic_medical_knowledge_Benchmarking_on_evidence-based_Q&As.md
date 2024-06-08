# 大型语言模型在数值与语义医学知识领域的性能对比：基于证据的问答基准测试研究

发布时间：2024年06月06日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在临床问题解决中的应用，特别是在处理语义和数值医学知识以支持循证决策方面的表现。通过创建一个包含大量医学知识的多选题数据集，并使用顶尖的LLMs进行测试，研究者评估了这些模型在不同类型问题上的表现，并与人类表现进行了比较。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在特定领域（医学）的实际应用和性能评估。` `临床决策支持`

> Performance of large language models in numerical vs. semantic medical knowledge: Benchmarking on evidence-based Q&As

# 摘要

> 临床问题解决依赖于处理语义和数值医学知识以支持循证决策。尽管大型语言模型（LLMs）在语言驱动的临床实践中表现出色，但它们在生成基于非语言证据的临床答案方面存在固有限制。我们评估了LLMs在数值（关联发现）和语义（区分实体）问题上的表现，并比较了它们与人类的表现。利用包含50,000多篇同行评审文章数据的医学知识图谱，我们创建了“EBMQA”，一个包含105,000个多选QAs的数据集，这些QAs被标记并分类为数值或语义问题。我们使用Chat-GPT4和Claude3-Opus这两个顶尖LLMs测试了超过24,500个QAs。结果显示，LLMs在语义问题上的表现优于数值问题，其中Claude3在数值问题上超越了GPT4。尽管如此，LLMs在不同医学方面仍显示出差距，且整体表现不及人类。因此，对LLMs提供的医学建议应持审慎态度。

> Clinical problem-solving requires processing of semantic medical knowledge such as illness scripts and numerical medical knowledge of diagnostic tests for evidence-based decision-making. As large language models (LLMs) show promising results in many aspects of language-based clinical practice, their ability to generate non-language evidence-based answers to clinical questions is inherently limited by tokenization. Therefore, we evaluated LLMs' performance on two question types: numeric (correlating findings) and semantic (differentiating entities) while examining differences within and between LLMs in medical aspects and comparing their performance to humans. To generate straightforward multi-choice questions and answers (QAs) based on evidence-based medicine (EBM), we used a comprehensive medical knowledge graph (encompassed data from more than 50,00 peer-reviewed articles) and created the "EBMQA". EBMQA contains 105,000 QAs labeled with medical and non-medical topics and classified into numerical or semantic questions. We benchmarked this dataset using more than 24,500 QAs on two state-of-the-art LLMs: Chat-GPT4 and Claude3-Opus. We evaluated the LLMs accuracy on semantic and numerical question types and according to sub-labeled topics. For validation, six medical experts were tested on 100 numerical EBMQA questions. We found that both LLMs excelled more in semantic than numerical QAs, with Claude3 surpassing GPT4 in numerical QAs. However, both LLMs showed inter and intra gaps in different medical aspects and remained inferior to humans. Thus, their medical advice should be addressed carefully.

[Arxiv](https://arxiv.org/abs/2406.03855)