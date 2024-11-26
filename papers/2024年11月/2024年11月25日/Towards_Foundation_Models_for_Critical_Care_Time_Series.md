# 朝着重症监护时间序列的基础模型进发

发布时间：2024年11月25日

`LLM应用` `重症监护`

> Towards Foundation Models for Critical Care Time Series

# 摘要

> 在各个医疗保健领域，通才医疗大型语言模型已取得显著进步。然而，像重症监护中的生命体征、实验室结果和治疗等医院内时间序列数据的大规模建模仍有待深入探索。现有的数据集规模相对较小，但将其整合能够增加患者的多样性，提升模型的稳健性。要想有效利用这些组合数据集进行大规模建模，就必须应对因不同治疗政策引发的分布变化，这就需要对不同数据集中的治疗变量进行协调。此项工作旨在为基于重症监护数据训练大规模多变量时间序列模型筑牢根基，并为医院间转移学习中的机器学习模型设立基准，以研究和化解分布变化带来的挑战。我们推出了一个用于序列建模和转移学习研究的协调数据集，这是首个涵盖核心治疗变量的大规模集合。未来的规划包括扩充此数据集，以助力转移学习的进一步发展以及关键医疗保健应用中可扩展、通用模型的开发。

> Notable progress has been made in generalist medical large language models across various healthcare areas. However, large-scale modeling of in-hospital time series data - such as vital signs, lab results, and treatments in critical care - remains underexplored. Existing datasets are relatively small, but combining them can enhance patient diversity and improve model robustness. To effectively utilize these combined datasets for large-scale modeling, it is essential to address the distribution shifts caused by varying treatment policies, necessitating the harmonization of treatment variables across the different datasets. This work aims to establish a foundation for training large-scale multi-variate time series models on critical care data and to provide a benchmark for machine learning models in transfer learning across hospitals to study and address distribution shift challenges. We introduce a harmonized dataset for sequence modeling and transfer learning research, representing the first large-scale collection to include core treatment variables. Future plans involve expanding this dataset to support further advancements in transfer learning and the development of scalable, generalizable models for critical healthcare applications.

[Arxiv](https://arxiv.org/abs/2411.16346)