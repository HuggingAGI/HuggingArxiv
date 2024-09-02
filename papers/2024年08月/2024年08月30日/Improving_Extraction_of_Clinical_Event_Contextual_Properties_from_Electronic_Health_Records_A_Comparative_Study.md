# 本研究旨在比较不同方法，以提升从电子健康记录中提取临床事件上下文属性的效率。

发布时间：2024年08月30日

`LLM应用`

> Improving Extraction of Clinical Event Contextual Properties from Electronic Health Records: A Comparative Study

# 摘要

> 电子健康记录中的非结构化文本数据，如临床事件，若能大规模准确提取，将助力疾病预测等下游应用。本研究采用MedCAT方法，对这些数据进行上下文分类，以评估其与患者的相关性及时间、否定状态。通过比较多种自然语言模型，我们发现BERT结合类别不平衡缓解技术，在医学文本分类中表现卓越，召回率提升显著。该成果已融入CogStack/MedCAT框架，供社区深入研究。

> Electronic Health Records are large repositories of valuable clinical data, with a significant portion stored in unstructured text format. This textual data includes clinical events (e.g., disorders, symptoms, findings, medications and procedures) in context that if extracted accurately at scale can unlock valuable downstream applications such as disease prediction. Using an existing Named Entity Recognition and Linking methodology, MedCAT, these identified concepts need to be further classified (contextualised) for their relevance to the patient, and their temporal and negated status for example, to be useful downstream. This study performs a comparative analysis of various natural language models for medical text classification. Extensive experimentation reveals the effectiveness of transformer-based language models, particularly BERT. When combined with class imbalance mitigation techniques, BERT outperforms Bi-LSTM models by up to 28% and the baseline BERT model by up to 16% for recall of the minority classes. The method has been implemented as part of CogStack/MedCAT framework and made available to the community for further research.

[Arxiv](https://arxiv.org/abs/2408.17181)