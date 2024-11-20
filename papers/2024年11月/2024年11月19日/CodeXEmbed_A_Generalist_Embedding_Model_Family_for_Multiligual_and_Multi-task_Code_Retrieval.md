# CodeXEmbed：适用于多语言和多任务代码检索的通用嵌入模型族

发布时间：2024年11月19日

`RAG`

> CodeXEmbed: A Generalist Embedding Model Family for Multiligual and Multi-task Code Retrieval

# 摘要

> 尽管文本检索在众多 NLP 任务中成果斐然，但代码检索在很大程度上仍属未充分开拓的领域。多数文本检索系统专为自然语言查询打造，常常忽视了检索代码的特定难题。这一差距致使现有模型难以有效捕捉不同领域中编程语言和任务的多样性，凸显出在代码检索方面开展更具针对性研究的必要性。为此，我们推出了 CodeXEmbed，这是一组参数规模从 4 亿到 70 亿的大规模代码嵌入模型。我们创新的训练流程统一了多种编程语言，并将各类与代码相关的任务纳入一个通用的检索框架，增强了模型的泛化能力和检索性能。我们的 70 亿参数模型在代码检索领域树立了新的最优水平（SOTA），在 CoIR 基准测试中比此前的领先模型 Voyage-Code 超出 20%以上。除在代码检索中表现卓越外，我们的模型在广泛应用的 BeIR 文本检索基准测试中也展现出颇具竞争力的性能，在不同领域均具备通用性。实验结果表明，提升检索性能能显著增强与代码相关任务的端到端检索增强生成（RAG）性能。

> Despite the success of text retrieval in many NLP tasks, code retrieval remains a largely underexplored area. Most text retrieval systems are tailored for natural language queries, often neglecting the specific challenges of retrieving code. This gap leaves existing models unable to effectively capture the diversity of programming languages and tasks across different domains, highlighting the need for more focused research in code retrieval. To address this, we introduce CodeXEmbed, a family of large-scale code embedding models ranging from 400M to 7B parameters. Our novel training pipeline unifies multiple programming languages and transforms various code-related tasks into a common retrieval framework, enhancing model generalizability and retrieval performance. Our 7B model sets a new state-of-the-art (SOTA) in code retrieval, outperforming the previous leading model, Voyage-Code, by over 20% on CoIR benchmark. In addition to excelling in code retrieval, our models demonstrate competitive performance on the widely adopted BeIR text retrieval benchmark, offering versatility across domains. Experimental results demonstrate that improving retrieval performance significantly enhances end-to-end Retrieval-Augmented Generation (RAG) performance for code-related tasks.

[Arxiv](https://arxiv.org/abs/2411.12644)