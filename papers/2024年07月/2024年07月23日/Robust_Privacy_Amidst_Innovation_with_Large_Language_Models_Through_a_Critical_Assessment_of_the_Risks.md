# 在大型语言模型的创新浪潮中，我们需通过批判性评估风险，确保隐私的坚固防线。

发布时间：2024年07月23日

`LLM应用` `生物医学研究`

> Robust Privacy Amidst Innovation with Large Language Models Through a Critical Assessment of the Risks

# 摘要

> 本研究通过整合 EHR 和 NLP 与 LLM，旨在提升医疗数据管理和患者护理。研究利用先进模型，创建符合 HIPAA 标准的合成患者笔记，供生物医学研究使用。通过去标识化和再标识化的 MIMIC III 数据集，结合 GPT-3.5、GPT-4 和 Mistral 7B，生成合成笔记。采用模板和关键词提取，确保笔记上下文相关，并通过一次性生成进行对比。隐私评估关注 PHI 出现，而文本效用则通过 ICD-9 编码任务检验。文本质量通过 ROUGE 和余弦相似度评估，确保与源笔记语义相似。分析显示，关键词方法风险低且性能佳。一次性生成中 PHI 暴露和共现最高，尤其在地理位置和日期类别。标准化一次性方法分类准确性最高。隐私分析强调数据效用与隐私保护的平衡，影响未来数据使用和共享。再标识化数据始终优于去标识化。研究证明关键词方法在生成保护隐私的合成临床笔记方面有效，保留数据可用性，可能革新临床数据共享。再标识化数据的优势表明，应采用虚拟 PHI 混淆隐私攻击的方法，提升效用和隐私。

> This study examines integrating EHRs and NLP with large language models (LLMs) to improve healthcare data management and patient care. It focuses on using advanced models to create secure, HIPAA-compliant synthetic patient notes for biomedical research. The study used de-identified and re-identified MIMIC III datasets with GPT-3.5, GPT-4, and Mistral 7B to generate synthetic notes. Text generation employed templates and keyword extraction for contextually relevant notes, with one-shot generation for comparison. Privacy assessment checked PHI occurrence, while text utility was tested using an ICD-9 coding task. Text quality was evaluated with ROUGE and cosine similarity metrics to measure semantic similarity with source notes. Analysis of PHI occurrence and text utility via the ICD-9 coding task showed that the keyword-based method had low risk and good performance. One-shot generation showed the highest PHI exposure and PHI co-occurrence, especially in geographic location and date categories. The Normalized One-shot method achieved the highest classification accuracy. Privacy analysis revealed a critical balance between data utility and privacy protection, influencing future data use and sharing. Re-identified data consistently outperformed de-identified data. This study demonstrates the effectiveness of keyword-based methods in generating privacy-protecting synthetic clinical notes that retain data usability, potentially transforming clinical data-sharing practices. The superior performance of re-identified over de-identified data suggests a shift towards methods that enhance utility and privacy by using dummy PHIs to perplex privacy attacks.

[Arxiv](https://arxiv.org/abs/2407.16166)