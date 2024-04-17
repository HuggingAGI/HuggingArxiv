# LegalPro-BERT：借助 BERT 大型语言模型的微调技术，实现对法律条文的精准分类。

发布时间：2024年04月15日

`LLM应用` `合同管理`

> LegalPro-BERT: Classification of Legal Provisions by fine-tuning BERT Large Language Model

# 摘要

> 合同作为组织中常见的法律文件，其审查过程对于规避商业风险至关重要，且需反复进行。合同分析涉及识别和分类合同中的关键条款，这一任务既费时又具挑战性，通常需要专业律师或法律助理的协助。由于法律专业术语的运用和标记数据的匮乏，利用AI及自然语言处理技术对合同条款进行分类变得复杂。通用模型在此领域并不适用，因为它们可能无法识别合同中的专业词汇。为应对这一挑战，我们建议采用经过法律术语校准的预训练大型语言模型。我们开发了LegalPro-BERT，这是一种BERT模型，经过精细调整后，能有效执行法律条款分类任务。实验结果显示，LegalPro-BERT在性能上超越了本研究中对比的先前基准模型。

> A contract is a type of legal document commonly used in organizations. Contract review is an integral and repetitive process to avoid business risk and liability. Contract analysis requires the identification and classification of key provisions and paragraphs within an agreement. Identification and validation of contract clauses can be a time-consuming and challenging task demanding the services of trained and expensive lawyers, paralegals or other legal assistants. Classification of legal provisions in contracts using artificial intelligence and natural language processing is complex due to the requirement of domain-specialized legal language for model training and the scarcity of sufficient labeled data in the legal domain. Using general-purpose models is not effective in this context due to the use of specialized legal vocabulary in contracts which may not be recognized by a general model. To address this problem, we propose the use of a pre-trained large language model which is subsequently calibrated on legal taxonomy. We propose LegalPro-BERT, a BERT transformer architecture model that we fine- tune to efficiently handle classification task for legal provisions. We conducted experiments to measure and compare metrics with current benchmark results. We found that LegalPro-BERT outperforms the previous benchmark used for comparison in this research.

[Arxiv](https://arxiv.org/abs/2404.10097)