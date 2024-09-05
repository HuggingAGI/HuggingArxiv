# 大型语言模型对决经典机器学习：高维表格数据在 COVID-19 死亡率预测中的表现

发布时间：2024年09月02日

`LLM应用` `机器学习`

> Large Language Models versus Classical Machine Learning: Performance in COVID-19 Mortality Prediction Using High-Dimensional Tabular Data

# 摘要

> 本研究通过高维数据集，对比了经典机器学习模型（CMLs）与大型语言模型（LLMs）在预测COVID-19死亡率方面的表现。我们分析了9,134名患者的跨医院数据，训练了包括XGBoost和随机森林在内的七种CML模型，并将结构化数据转换为文本供LLMs进行零-shot分类。GPT-4在LLMs中表现最佳，而微调后的Mistral-7b召回率大幅提升至79%。结论显示，尽管LLMs通过微调可显著提升性能，但在高维数据任务中，CMLs仍占优势。

> Background: This study aimed to evaluate and compare the performance of classical machine learning models (CMLs) and large language models (LLMs) in predicting mortality associated with COVID-19 by utilizing a high-dimensional tabular dataset.
  Materials and Methods: We analyzed data from 9,134 COVID-19 patients collected across four hospitals. Seven CML models, including XGBoost and random forest (RF), were trained and evaluated. The structured data was converted into text for zero-shot classification by eight LLMs, including GPT-4 and Mistral-7b. Additionally, Mistral-7b was fine-tuned using the QLoRA approach to enhance its predictive capabilities.
  Results: Among the CML models, XGBoost and RF achieved the highest accuracy, with F1 scores of 0.87 for internal validation and 0.83 for external validation. In the LLM category, GPT-4 was the top performer with an F1 score of 0.43. Fine-tuning Mistral-7b significantly improved its recall from 1% to 79%, resulting in an F1 score of 0.74, which was stable during external validation.
  Conclusion: While LLMs show moderate performance in zero-shot classification, fine-tuning can significantly enhance their effectiveness, potentially aligning them closer to CML models. However, CMLs still outperform LLMs in high-dimensional tabular data tasks.

[Arxiv](https://arxiv.org/abs/2409.02136)