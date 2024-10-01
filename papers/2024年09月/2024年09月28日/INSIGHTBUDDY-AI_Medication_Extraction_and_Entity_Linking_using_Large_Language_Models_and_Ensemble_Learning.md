# INSIGHTBUDDY-AI：借助大型语言模型与集成学习，实现药物提取与实体链接的智能助手

发布时间：2024年09月28日

`LLM应用`

> INSIGHTBUDDY-AI: Medication Extraction and Entity Linking using Large Language Models and Ensemble Learning

# 摘要

> 在医疗NLP研究中，药物提取与挖掘因其医院环境中的实际应用（如映射至SNOMED-CT、BNF等标准知识库）而显得尤为重要。我们深入探讨了最先进的LLM在药物及其属性（如剂量、途径、强度及不良反应）文本挖掘任务中的表现。同时，我们通过\textsc{Stack-Ensemble}和\textsc{Voting-Ensemble}等集成学习方法，显著提升了单个LLM的性能，使其在一般与特定领域均超越了BERT、RoBERTa等微调模型。最终，我们开发了实体链接功能，将提取的医学术语精准映射至SNOMED-CT、BNF代码，并进一步关联至dm+d与ICD。所有工具与应用已公开于\url{https://github.com/HECTA-UoM/ensemble-NER}。

> Medication Extraction and Mining play an important role in healthcare NLP research due to its practical applications in hospital settings, such as their mapping into standard clinical knowledge bases (SNOMED-CT, BNF, etc.). In this work, we investigate state-of-the-art LLMs in text mining tasks on medications and their related attributes such as dosage, route, strength, and adverse effects. In addition, we explore different ensemble learning methods (\textsc{Stack-Ensemble} and \textsc{Voting-Ensemble}) to augment the model performances from individual LLMs. Our ensemble learning result demonstrated better performances than individually fine-tuned base models BERT, RoBERTa, RoBERTa-L, BioBERT, BioClinicalBERT, BioMedRoBERTa, ClinicalBERT, and PubMedBERT across general and specific domains. Finally, we build up an entity linking function to map extracted medical terminologies into the SNOMED-CT codes and the British National Formulary (BNF) codes, which are further mapped to the Dictionary of Medicines and Devices (dm+d), and ICD. Our model's toolkit and desktop applications are publicly available at \url{https://github.com/HECTA-UoM/ensemble-NER}.

[Arxiv](https://arxiv.org/abs/2409.19467)