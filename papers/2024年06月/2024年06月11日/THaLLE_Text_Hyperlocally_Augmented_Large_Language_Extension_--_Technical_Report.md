# THaLLE：文本局部增强的大型语言扩展技术报告

发布时间：2024年06月11日

`LLM应用

这篇论文介绍了针对金融分析领域的特定应用，即文本超本地增强大型语言扩展（THaLLE）的金融分析师扩展。该研究专注于开发和微调一系列具有80亿参数的大型语言模型（LLMs），以在模拟的特许金融分析师（CFA）考试中表现出色。此外，研究还引入了Flare CFA数据集，用于评估LLMs在金融顾问角色中的能力。这表明研究的重点是LLMs在特定领域的应用，而不是理论探讨或Agent的设计与实现，也不是关于检索增强生成（RAG）的研究。因此，最合适的分类是LLM应用。`

> THaLLE: Text Hyperlocally Augmented Large Language Extension -- Technical Report

# 摘要

> 大型语言模型（LLMs）的最新发展为技术领域带来了新机遇，但超大型模型的实用性因高计算成本而受限，其效益与人类能力相比并不显著。尽管小型实用的LLMs在金融分析领域展现出潜力，但它们在特许金融分析师（CFA）考试中的表现仅接近及格，尚未完全成熟。本研究介绍了我们文本超本地增强大型语言扩展（THaLLE）的金融分析师扩展，这一系列80亿参数的LLMs在模拟CFA考试中持续领先于同规模模型。我们详细记录了微调技术，以促进未来研究，并引入了Flare CFA数据集，用于评估LLMs作为金融顾问的能力。

> Recent advancements in Large Language Models (LLMs) have revealed new capabilities and opportunities across the technological landscape. However, the practicality of very large LLMs is challenged by their high compute cost, which does not justify the benefits given their limited capability compared to humans. While smaller, more practical LLMs have shown potential in financial analysis, though they are not yet fully proficient, as evidenced by their near-passing performance on the Chartered Financial Analyst (CFA) exam. In this work, we present Financial Analyst Extension to our Text Hyperlocally Augmented Large Language Extension (THaLLE), a series of 8B LLMs consistently achieving highest performance on mock CFA exams against models of comparable size. We thoroughly document the fine-tuning techniques used to facilitate future research. Additionally, we introduce the use of Flare CFA, a publicly available dataset for evaluating LLMs as a financial advisor.

[Arxiv](https://arxiv.org/abs/2406.07505)