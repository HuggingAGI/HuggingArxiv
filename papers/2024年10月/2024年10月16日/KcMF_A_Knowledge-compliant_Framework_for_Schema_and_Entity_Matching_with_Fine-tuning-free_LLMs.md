# KcMF：一个无需微调的大型语言模型框架，专为模式和实体匹配设计，确保知识合规性。

发布时间：2024年10月16日

`LLM应用` `数据管理` `数据集成`

> KcMF: A Knowledge-compliant Framework for Schema and Entity Matching with Fine-tuning-free LLMs

# 摘要

> 模式与实体匹配任务在数据集成和管理中至关重要。尽管大型语言模型 (LLM) 在此类任务中表现出色，但仍存在对任务指令的误解和混淆。为此，我们提出了知识合规匹配框架 (KcMF)，一种无需特定领域微调的 LLM 方法。KcMF 通过伪代码分解任务，用自然语言指导 LLM 推理，减少混淆。我们还设计了数据集即知识 (DaK) 和示例即知识 (EaK) 机制，以构建领域知识集。此外，通过结果集成策略，我们整合多源知识，优化输出格式。实验表明，KcMF 在模式与实体匹配任务中，平均 F1 分数比非 LLM 的 SOTA 方法高出 22.9%，并能与微调后的 LLM 相媲美。更重要的是，KcMF 在不同 LLM 间展现出良好的泛化能力。

> Schema and entity matching tasks are crucial for data integration and management. While large language models (LLMs) have shown promising results in these tasks, they suffer from hallucinations and confusion about task instructions. In this paper, we present the Knowledge-Compliant Matching Framework (KcMF), an LLM-based approach that addresses these issues without the need for domain-specific fine-tuning. KcMF employs a pseudo-code-based task decomposition strategy to adopt task-specific natural language statements that guide LLM reasoning and reduce confusion. We also propose two mechanisms, Dataset as Knowledge (DaK) and Example as Knowledge (EaK), to build domain knowledge sets when unstructured domain knowledge is lacking. Additionally, we introduce a result-ensembling strategy to leverage multiple knowledge sources and suppress poorly formatted outputs. Comprehensive evaluations on schema and entity matching tasks demonstrate that KcMF outperforms previous non-LLM state-of-the-art (SOTA) methods by an average F1 score of 22.9% and competes effectively with SOTA fine-tuned LLMs. Moreover, KcMF generalizes well across different LLMs.

[Arxiv](https://arxiv.org/abs/2410.12480)