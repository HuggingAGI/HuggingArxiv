# KARGEN：借助大型语言模型，实现知识增强的自动化放射报告生成

发布时间：2024年09月09日

`LLM应用` `放射学`

> KARGEN: Knowledge-enhanced Automated Radiology Report Generation Using Large Language Models

# 摘要

> 本研究利用大型语言模型 (LLM) 在叙事生成、逻辑推理和常识知识整合方面的强大能力，探索了如何通过 LLM 增强自动化放射学报告生成 (R2Gen)。尽管 LLM 知识丰富，但如何高效提取与 R2Gen 相关的知识仍是一大挑战。为此，我们提出了 KARGEN，一个基于 LLM 的知识增强报告生成框架。该框架通过整合知识图谱，解锁 LLM 中与胸部疾病相关的知识，从而提升报告的临床价值。我们利用知识图谱提炼疾病特征，并将其与图像特征融合，生成更精准、质量更高的报告。实验结果表明，KARGEN 在 MIMIC-CXR 和 IU-Xray 数据集上表现出色。

> Harnessing the robust capabilities of Large Language Models (LLMs) for narrative generation, logical reasoning, and common-sense knowledge integration, this study delves into utilizing LLMs to enhance automated radiology report generation (R2Gen). Despite the wealth of knowledge within LLMs, efficiently triggering relevant knowledge within these large models for specific tasks like R2Gen poses a critical research challenge. This paper presents KARGEN, a Knowledge-enhanced Automated radiology Report GENeration framework based on LLMs. Utilizing a frozen LLM to generate reports, the framework integrates a knowledge graph to unlock chest disease-related knowledge within the LLM to enhance the clinical utility of generated reports. This is achieved by leveraging the knowledge graph to distill disease-related features in a designed way. Since a radiology report encompasses both normal and disease-related findings, the extracted graph-enhanced disease-related features are integrated with regional image features, attending to both aspects. We explore two fusion methods to automatically prioritize and select the most relevant features. The fused features are employed by LLM to generate reports that are more sensitive to diseases and of improved quality. Our approach demonstrates promising results on the MIMIC-CXR and IU-Xray datasets.

[Arxiv](https://arxiv.org/abs/2409.05370)