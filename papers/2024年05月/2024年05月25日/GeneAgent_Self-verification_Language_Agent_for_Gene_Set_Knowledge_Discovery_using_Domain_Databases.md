# GeneAgent：利用专业数据库，自主验证基因集知识的语言智能助手

发布时间：2024年05月25日

`Agent

解析：这篇论文介绍了一个名为 GeneAgent 的创新语言代理，它具备自我验证功能，能够自主访问生物数据库，整合专业知识，提升准确性，减少错误。这个代理在基因集知识发现领域展现出了优越的性能，特别是在减少幻觉和提高分析可靠性方面。因此，这篇论文更符合Agent分类，因为它描述了一个具体的语言代理及其在特定领域的应用。` `生物技术` `基因组学`

> GeneAgent: Self-verification Language Agent for Gene Set Knowledge Discovery using Domain Databases

# 摘要

> 在推进人类功能基因组学的过程中，基因集知识发现扮演着关键角色。近期研究显示，大型语言模型（LLMs）在这一领域展现出潜力，但仍受限于幻觉等常见问题。为此，我们开发了GeneAgent，这一创新语言代理具备自我验证功能，能自主访问生物数据库，整合专业知识，提升准确性，减少错误。在1,106个基因集的测试中，GeneAgent显著优于GPT-4。专家评审进一步证实，其自我验证机制有效降低了幻觉，增强了分析的可靠性。我们还将GeneAgent应用于七个来自鼠黑色素瘤细胞系的新基因集，结果表明，GeneAgent不仅揭示了基因功能的新视角，还加速了知识发现的进程。

> Gene set knowledge discovery is essential for advancing human functional genomics. Recent studies have shown promising performance by harnessing the power of Large Language Models (LLMs) on this task. Nonetheless, their results are subject to several limitations common in LLMs such as hallucinations. In response, we present GeneAgent, a first-of-its-kind language agent featuring self-verification capability. It autonomously interacts with various biological databases and leverages relevant domain knowledge to improve accuracy and reduce hallucination occurrences. Benchmarking on 1,106 gene sets from different sources, GeneAgent consistently outperforms standard GPT-4 by a significant margin. Moreover, a detailed manual review confirms the effectiveness of the self-verification module in minimizing hallucinations and generating more reliable analytical narratives. To demonstrate its practical utility, we apply GeneAgent to seven novel gene sets derived from mouse B2905 melanoma cell lines, with expert evaluations showing that GeneAgent offers novel insights into gene functions and subsequently expedites knowledge discovery.

[Arxiv](https://arxiv.org/abs/2405.16205)