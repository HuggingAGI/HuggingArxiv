# [本研究采用大规模多模态语言模型，利用电子健康记录数据来预测五年内慢性疾病队列的发展趋势。](https://arxiv.org/abs/2403.04785)

发布时间：2024年03月02日

`LLM应用` `慢性疾病诊断`

> Large Language Multimodal Models for 5-Year Chronic Disease Cohort Prediction Using EHR Data

> 糖尿病等慢性疾病作为全球主要的致病与死亡因素，已有多项研究运用各类深度学习模型探索其诊断效果。然而，过往研究多受限于仅使用公开数据集（如MIMIC）及应对数据不平衡问题。本次研究中，我们自台湾医院数据库采集了五年内的电子健康记录，内容包括140余万份临床记录、近38万份实验室检测结果及超过1500项实验室检测指标，侧重于对大型语言模型的预训练研究。我们创新性地提出了“大规模多模态语言模型（LLMMs）”框架，整合临床笔记与实验室检测结果的多模态信息，旨在预测慢性疾病的风险等级。研究中，我们运用文本嵌入编码器结合多头注意力机制理解实验室检测数值，并借由深度神经网络模块将血液特征与慢性疾病的语义深度融合至潜在空间。实验结果显示，当clinicalBERT与PubMed-BERT结合注意力融合技术时，在多类别的慢性疾病及糖尿病预测任务上可实现高达73%的准确度。此外，我们将实验室检测数值转化为文本描述并引入Flan T-5模型后，在ROC曲线下的面积(AUROC)达到了76%，有力证明了在语言模型训练和推断过程中充分利用数值型文本数据的有效性。这一方法对于提升糖尿病早期预测的准确性具有显著意义。

> Chronic diseases such as diabetes are the leading causes of morbidity and mortality worldwide. Numerous research studies have been attempted with various deep learning models in diagnosis. However, most previous studies had certain limitations, including using publicly available datasets (e.g. MIMIC), and imbalanced data. In this study, we collected five-year electronic health records (EHRs) from the Taiwan hospital database, including 1,420,596 clinical notes, 387,392 laboratory test results, and more than 1,505 laboratory test items, focusing on research pre-training large language models. We proposed a novel Large Language Multimodal Models (LLMMs) framework incorporating multimodal data from clinical notes and laboratory test results for the prediction of chronic disease risk. Our method combined a text embedding encoder and multi-head attention layer to learn laboratory test values, utilizing a deep neural network (DNN) module to merge blood features with chronic disease semantics into a latent space. In our experiments, we observe that clinicalBERT and PubMed-BERT, when combined with attention fusion, can achieve an accuracy of 73% in multiclass chronic diseases and diabetes prediction. By transforming laboratory test values into textual descriptions and employing the Flan T-5 model, we achieved a 76% Area Under the ROC Curve (AUROC), demonstrating the effectiveness of leveraging numerical text data for training and inference in language models. This approach significantly improves the accuracy of early-stage diabetes prediction.

[Arxiv](https://arxiv.org/abs/2403.04785)