# 大型语言模型在非生成性医疗任务中的表现是否总是更优？本文旨在评估并提升其在这些任务中的效能。

发布时间：2024年07月26日

`LLM应用` `人工智能`

> Is larger always better? Evaluating and prompting large language models for non-generative medical tasks

# 摘要

> 大型语言模型（LLM）在医学领域的应用日益广泛，但其在处理结构化电子健康记录（EHR）和非结构化临床笔记方面的能力仍有待深入研究。本研究对包括基于GPT的LLM、BERT模型及传统临床预测模型在内的多种模型进行了基准测试，利用知名数据集评估其在非生成性医学任务中的表现。我们评估了14种语言模型（9种基于GPT，5种基于BERT）和7种传统预测模型，使用MIMIC和TJH数据集，聚焦于死亡率预测、再入院风险评估、疾病分类重建及生物医学文本匹配等任务，对比了零-shot与微调后的性能。结果表明，LLM在采用精心设计的提示策略时，对结构化EHR数据展现出卓越的零-shot预测能力，常优于传统模型。然而，在处理非结构化医学文本时，LLM的表现未能超越经过微调的BERT模型，后者在监督与非监督任务中均表现优异。因此，尽管LLM在结构化数据上的零-shot学习效果显著，但针对非结构化文本，微调的BERT模型更为适宜。这凸显了根据具体任务需求和数据特性选择合适模型的重要性，以期最大化NLP技术在医疗领域的应用效益。

> The use of Large Language Models (LLMs) in medicine is growing, but their ability to handle both structured Electronic Health Record (EHR) data and unstructured clinical notes is not well-studied. This study benchmarks various models, including GPT-based LLMs, BERT-based models, and traditional clinical predictive models, for non-generative medical tasks utilizing renowned datasets. We assessed 14 language models (9 GPT-based and 5 BERT-based) and 7 traditional predictive models using the MIMIC dataset (ICU patient records) and the TJH dataset (early COVID-19 EHR data), focusing on tasks such as mortality and readmission prediction, disease hierarchy reconstruction, and biomedical sentence matching, comparing both zero-shot and finetuned performance. Results indicated that LLMs exhibited robust zero-shot predictive capabilities on structured EHR data when using well-designed prompting strategies, frequently surpassing traditional models. However, for unstructured medical texts, LLMs did not outperform finetuned BERT models, which excelled in both supervised and unsupervised tasks. Consequently, while LLMs are effective for zero-shot learning on structured data, finetuned BERT models are more suitable for unstructured texts, underscoring the importance of selecting models based on specific task requirements and data characteristics to optimize the application of NLP technology in healthcare.

[Arxiv](https://arxiv.org/abs/2407.18525)