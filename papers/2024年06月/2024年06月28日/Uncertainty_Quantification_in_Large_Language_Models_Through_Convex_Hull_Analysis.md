# 利用凸包分析在大语言模型中量化不确定性

发布时间：2024年06月28日

`LLM理论` `人工智能` `数据分析`

> Uncertainty Quantification in Large Language Models Through Convex Hull Analysis

# 摘要

> 在大语言模型 (LLM) 中，特别是在高风险应用中，不确定性量化方法变得尤为关键。然而，传统的概率模型和集成技术在处理 LLM 生成输出的复杂性和高维度时面临挑战。本研究提出了一种新颖的几何方法，通过凸包分析来量化不确定性。该方法利用响应嵌入的空间属性，测量模型输出的分散度和变异性。提示分为“简单”、“中等”和“混淆”三类，以不同温度设置下的 LLM 生成多个响应。这些响应通过 BERT 模型转换为高维嵌入，并使用 PCA 投影到二维空间。DBSCAN 算法用于聚类嵌入并计算每个聚类的凸包。实验结果显示，LLM 模型的不确定性受提示复杂性、模型和温度设置的影响。

> Uncertainty quantification approaches have been more critical in large language models (LLMs), particularly high-risk applications requiring reliable outputs. However, traditional methods for uncertainty quantification, such as probabilistic models and ensemble techniques, face challenges when applied to the complex and high-dimensional nature of LLM-generated outputs. This study proposes a novel geometric approach to uncertainty quantification using convex hull analysis. The proposed method leverages the spatial properties of response embeddings to measure the dispersion and variability of model outputs. The prompts are categorized into three types, i.e., `easy', `moderate', and `confusing', to generate multiple responses using different LLMs at varying temperature settings. The responses are transformed into high-dimensional embeddings via a BERT model and subsequently projected into a two-dimensional space using Principal Component Analysis (PCA). The Density-Based Spatial Clustering of Applications with Noise (DBSCAN) algorithm is utilized to cluster the embeddings and compute the convex hull for each selected cluster. The experimental results indicate that the uncertainty of the model for LLMs depends on the prompt complexity, the model, and the temperature setting.

[Arxiv](https://arxiv.org/abs/2406.19712)