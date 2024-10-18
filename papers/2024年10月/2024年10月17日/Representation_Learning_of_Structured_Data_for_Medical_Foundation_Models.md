# 医疗基础模型中的结构化数据表示学习

发布时间：2024年10月17日

`LLM应用` `健康信息技术`

> Representation Learning of Structured Data for Medical Foundation Models

# 摘要

> 大型语言模型（LLM）在医疗保健等多个领域表现出色，但在处理如 ICD-10 或 SNOMED-CT 等结构化医疗代码时，其能力有限。本文探讨了当前分词方法的不足，并提出了 UniStruct 架构，通过优化子词分词技术，设计了一个能同时处理非结构化文本和结构化数据的多模态医疗模型。经过在庞大医疗数据库上的预训练，该模型在评估中提升了高达 23%，其中 2% 的提升归功于新的分词方法。在 EHRSHOT 基准测试中，即使使用少量预训练数据，UniStruct 模型也在超过 42% 的下游任务中表现优异。这不仅增强了模型的表示和泛化能力，还填补了处理复杂医疗数据与非结构化文本之间的关键空白。

> Large Language Models (LLMs) have demonstrated remarkable performance across various domains, including healthcare. However, their ability to effectively represent structured non-textual data, such as the alphanumeric medical codes used in records like ICD-10 or SNOMED-CT, is limited and has been particularly exposed in recent research. This paper examines the challenges LLMs face in processing medical codes due to the shortcomings of current tokenization methods. As a result, we introduce the UniStruct architecture to design a multimodal medical foundation model of unstructured text and structured data, which addresses these challenges by adapting subword tokenization techniques specifically for the structured medical codes. Our approach is validated through model pre-training on both an extensive internal medical database and a public repository of structured medical records. Trained on over 1 billion tokens on the internal medical database, the proposed model achieves up to a 23% improvement in evaluation metrics, with around 2% gain attributed to our proposed tokenization. Additionally, when evaluated on the EHRSHOT public benchmark with a 1/1000 fraction of the pre-training data, the UniStruct model improves performance on over 42% of the downstream tasks. Our approach not only enhances the representation and generalization capabilities of patient-centric models but also bridges a critical gap in representation learning models' ability to handle complex structured medical data, alongside unstructured text.

[Arxiv](https://arxiv.org/abs/2410.13351)