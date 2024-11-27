# 借助 LLM 生成合成数据来优化抑郁症预测

发布时间：2024年11月26日

`LLM应用` `心理学`

> Synthetic Data Generation with LLM for Improved Depression Prediction

# 摘要

> 自动检测抑郁症在心理学与机器学习的交叉领域发展迅猛。然而，随着关注度呈指数级上升，因该主题的敏感性，对数据隐私和稀缺的担忧也与日俱增。本文中，我们为大型语言模型（LLMs）提出了一个生成合成数据的流程，以提升抑郁症预测模型的性能。从临床访谈记录转录本的非结构化、自然主义文本数据出发，我们借助开源的LLM，通过思维链提示来生成合成数据。此流程包含两个关键步骤：第一步是依据原始转录本和抑郁症得分生成概要及情感分析；第二步是基于第一步生成的摘要和新的抑郁症得分生成合成的概要/情感分析。合成数据不仅在保真度和隐私保护指标方面表现出色，还平衡了训练数据集中严重程度的分布，大幅增强了模型预测患者抑郁症严重程度的能力。通过利用LLMs生成能补充到有限且不平衡的现实世界数据集中的合成数据，我们展示了一种创新的方法，解决了自动抑郁症检测中常见的数据稀缺和隐私问题，同时维持了原始数据集的统计完整性。该方法为未来的心理健康研究和应用提供了有力框架。

> Automatic detection of depression is a rapidly growing field of research at the intersection of psychology and machine learning. However, with its exponential interest comes a growing concern for data privacy and scarcity due to the sensitivity of such a topic. In this paper, we propose a pipeline for Large Language Models (LLMs) to generate synthetic data to improve the performance of depression prediction models. Starting from unstructured, naturalistic text data from recorded transcripts of clinical interviews, we utilize an open-source LLM to generate synthetic data through chain-of-thought prompting. This pipeline involves two key steps: the first step is the generation of the synopsis and sentiment analysis based on the original transcript and depression score, while the second is the generation of the synthetic synopsis/sentiment analysis based on the summaries generated in the first step and a new depression score. Not only was the synthetic data satisfactory in terms of fidelity and privacy-preserving metrics, it also balanced the distribution of severity in the training dataset, thereby significantly enhancing the model's capability in predicting the intensity of the patient's depression. By leveraging LLMs to generate synthetic data that can be augmented to limited and imbalanced real-world datasets, we demonstrate a novel approach to addressing data scarcity and privacy concerns commonly faced in automatic depression detection, all while maintaining the statistical integrity of the original dataset. This approach offers a robust framework for future mental health research and applications.

[Arxiv](https://arxiv.org/abs/2411.17672)