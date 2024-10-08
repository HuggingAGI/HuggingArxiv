# 通过知识图谱社区检索提升医疗预测中的推理能力

发布时间：2024年10月06日

`LLM应用` `临床决策支持`

> Reasoning-Enhanced Healthcare Predictions with Knowledge Graph Community Retrieval

# 摘要

> 大型语言模型 (LLM) 在临床决策支持中展现出巨大潜力，但仍面临幻觉和缺乏细粒度医学知识的问题，限制了其在高风险医疗应用中的表现，如临床诊断。传统的检索增强生成 (RAG) 方法虽尝试解决这些问题，但常检索到无关信息，影响预测准确性。为此，我们推出了 KARE 框架，结合知识图谱 (KG) 社区级检索与 LLM 推理，提升医疗预测能力。KARE 通过整合生物医学数据库、临床文献及 LLM 生成见解，构建多源 KG，并运用层次图社区检测与总结，实现精准上下文相关信息检索。主要创新包括：(1) 密集医学知识结构化，确保信息准确检索；(2) 动态知识检索机制，丰富患者多方面医学见解；(3) 推理增强预测框架，利用丰富上下文生成准确可解释的临床预测。实验显示，KARE 在 MIMIC-III 和 MIMIC-IV 的死亡率与再入院预测中，分别优于领先模型 10.8-15.0% 和 12.6-12.7%。此外，KARE 利用 LLM 推理能力，提升临床预测的可信度。

> Large language models (LLMs) have demonstrated significant potential in clinical decision support. Yet LLMs still suffer from hallucinations and lack fine-grained contextual medical knowledge, limiting their high-stake healthcare applications such as clinical diagnosis. Traditional retrieval-augmented generation (RAG) methods attempt to address these limitations but frequently retrieve sparse or irrelevant information, undermining prediction accuracy. We introduce KARE, a novel framework that integrates knowledge graph (KG) community-level retrieval with LLM reasoning to enhance healthcare predictions. KARE constructs a comprehensive multi-source KG by integrating biomedical databases, clinical literature, and LLM-generated insights, and organizes it using hierarchical graph community detection and summarization for precise and contextually relevant information retrieval. Our key innovations include: (1) a dense medical knowledge structuring approach enabling accurate retrieval of relevant information; (2) a dynamic knowledge retrieval mechanism that enriches patient contexts with focused, multi-faceted medical insights; and (3) a reasoning-enhanced prediction framework that leverages these enriched contexts to produce both accurate and interpretable clinical predictions. Extensive experiments demonstrate that KARE outperforms leading models by up to 10.8-15.0% on MIMIC-III and 12.6-12.7% on MIMIC-IV for mortality and readmission predictions. In addition to its impressive prediction accuracy, our framework leverages the reasoning capabilities of LLMs, enhancing the trustworthiness of clinical predictions.

[Arxiv](https://arxiv.org/abs/2410.04585)