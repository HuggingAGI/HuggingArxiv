# 借助结构化知识库，大型语言模型在元数据管理方面的表现得到提升。

发布时间：2024年04月08日

`LLM应用` `生物信息学` `数据管理`

> Use of a Structured Knowledge Base Enhances Metadata Curation by Large Language Models

# 摘要

> 元数据对于保障数据集的易检索、易获取、易交互和可复用至关重要。本研究探讨了大型语言模型（特别是GPT-4）在提升对元数据标准遵循度方面的潜力。我们针对NCBI BioSample库中的200条肺癌相关人类样本数据记录进行实验，评估GPT-4对提升元数据标准遵循度的建议编辑能力。通过同行评审，我们发现字段名称与值的匹配准确率从79%微升至80%（p<0.01）。随后，我们向GPT-4输入了CEDAR模板的文字描述作为领域信息，发现遵循度显著提升至97%（p<0.01）。这一发现揭示了尽管在无人辅助的情况下，LLMs可能无法完全纠正现有元数据以达到标准要求，但结合结构化知识库后，它们在自动化元数据管理方面展现出巨大潜力。

> Metadata play a crucial role in ensuring the findability, accessibility, interoperability, and reusability of datasets. This paper investigates the potential of large language models (LLMs), specifically GPT-4, to improve adherence to metadata standards. We conducted experiments on 200 random data records describing human samples relating to lung cancer from the NCBI BioSample repository, evaluating GPT-4's ability to suggest edits for adherence to metadata standards. We computed the adherence accuracy of field name-field value pairs through a peer review process, and we observed a marginal average improvement in adherence to the standard data dictionary from 79% to 80% (p<0.01). We then prompted GPT-4 with domain information in the form of the textual descriptions of CEDAR templates and recorded a significant improvement to 97% from 79% (p<0.01). These results indicate that, while LLMs may not be able to correct legacy metadata to ensure satisfactory adherence to standards when unaided, they do show promise for use in automated metadata curation when integrated with a structured knowledge base.

[Arxiv](https://arxiv.org/abs/2404.05893)