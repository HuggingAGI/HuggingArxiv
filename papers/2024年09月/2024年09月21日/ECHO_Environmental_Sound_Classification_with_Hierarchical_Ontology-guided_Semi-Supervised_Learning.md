# ECHO：通过分层本体引导的半监督学习实现环境声音分类

发布时间：2024年09月21日

`LLM应用` `环境监测` `信号处理`

> ECHO: Environmental Sound Classification with Hierarchical Ontology-guided Semi-Supervised Learning

# 摘要

> 环境声音分类在信号处理领域备受关注，但近年来的研究重点已从全监督转向半监督和自监督方法。这些方法依赖大量未标记数据提升性能。我们提出的ECHO框架，通过本体层次结构定义新预文本任务，学习语义表示。模型先预测LLM定义的粗略标签，再微调以完成实际任务。在UrbanSound8K、ESC-10和ESC-50数据集上，ECHO框架比基线系统准确率提升1%至8%。

> Environment Sound Classification has been a well-studied research problem in the field of signal processing and up till now more focus has been laid on fully supervised approaches. Over the last few years, focus has moved towards semi-supervised methods which concentrate on the utilization of unlabeled data, and self-supervised methods which learn the intermediate representation through pretext task or contrastive learning. However, both approaches require a vast amount of unlabelled data to improve performance. In this work, we propose a novel framework called Environmental Sound Classification with Hierarchical Ontology-guided semi-supervised Learning (ECHO) that utilizes label ontology-based hierarchy to learn semantic representation by defining a novel pretext task. In the pretext task, the model tries to predict coarse labels defined by the Large Language Model (LLM) based on ground truth label ontology. The trained model is further fine-tuned in a supervised way to predict the actual task. Our proposed novel semi-supervised framework achieves an accuracy improvement in the range of 1\% to 8\% over baseline systems across three datasets namely UrbanSound8K, ESC-10, and ESC-50.

[Arxiv](https://arxiv.org/abs/2409.14043)