# EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型

发布时间：2024年05月27日

`RAG

理由：这篇论文介绍了一个名为EMERGE的框架，该框架利用检索增强生成（RAG）技术来提升多模态电子健康记录（EHR）数据的预测建模能力。论文中提到的RAG技术是关键，它通过大型语言模型（LLMs）从时间序列数据和临床笔记中提取实体，并与专业知识图谱对齐，以确保知识的一致性。这种方法特别强调了RAG技术在医疗领域的应用，因此将其归类为RAG。` `临床预测`

> EMERGE: Integrating RAG for Improved Multimodal EHR Predictive Modeling

# 摘要

> 多模态电子健康记录（EHR）数据的整合显著提升了临床预测能力。然而，现有模型在使用临床笔记和多变量时间序列EHR数据时，往往缺乏精确临床任务所需的医学背景。为此，我们提出了EMERGE框架，它利用检索增强生成（RAG）技术，旨在提升多模态EHR的预测建模。我们的方法通过大型语言模型（LLMs）从时间序列数据和临床笔记中提取实体，并与专业PrimeKG对齐，确保知识的一致性。此外，我们还包含了实体的定义和描述，以丰富语义信息。提取的知识用于生成与任务相关的患者健康状况摘要，并通过自适应多模态融合网络与其他模态信息融合。在MIMIC-III和MIMIC-IV数据集上的实验表明，EMERGE框架在院内死亡率和30天再入院预测任务中优于基线模型。消融研究和分析进一步验证了每个模块的有效性及框架对数据稀疏性的鲁棒性。EMERGE框架有效弥合了复杂医学背景与临床预测之间的差距，显著提升了多模态EHR数据在医疗保健中的应用价值。

> The integration of multimodal Electronic Health Records (EHR) data has notably advanced clinical predictive capabilities. However, current models that utilize clinical notes and multivariate time-series EHR data often lack the necessary medical context for precise clinical tasks. Previous methods using knowledge graphs (KGs) primarily focus on structured knowledge extraction. To address this, we propose EMERGE, a Retrieval-Augmented Generation (RAG) driven framework aimed at enhancing multimodal EHR predictive modeling. Our approach extracts entities from both time-series data and clinical notes by prompting Large Language Models (LLMs) and aligns them with professional PrimeKG to ensure consistency. Beyond triplet relationships, we include entities' definitions and descriptions to provide richer semantics. The extracted knowledge is then used to generate task-relevant summaries of patients' health statuses. These summaries are fused with other modalities utilizing an adaptive multimodal fusion network with cross-attention. Extensive experiments on the MIMIC-III and MIMIC-IV datasets for in-hospital mortality and 30-day readmission tasks demonstrate the superior performance of the EMERGE framework compared to baseline models. Comprehensive ablation studies and analyses underscore the efficacy of each designed module and the framework's robustness to data sparsity. EMERGE significantly enhances the use of multimodal EHR data in healthcare, bridging the gap with nuanced medical contexts crucial for informed clinical predictions.

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x1.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x2.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x3.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x4.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x5.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x6.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x7.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x8.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x9.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x10.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x11.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x12.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x13.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x14.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x15.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x16.png)

![EMERGE：融合RAG技术，优化多模态电子健康记录的预测模型](../../../paper_images/2406.00036/x17.png)

[Arxiv](https://arxiv.org/abs/2406.00036)