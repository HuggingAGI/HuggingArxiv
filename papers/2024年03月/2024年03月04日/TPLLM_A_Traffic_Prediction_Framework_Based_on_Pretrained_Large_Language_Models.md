# TPLLM 是一种基于预训练大型语言模型的交通预测方案，该框架利用大规模语言模型的强大泛化和学习能力，对交通流量进行精准预测。

发布时间：2024年03月04日

`LLM应用`

> TPLLM: A Traffic Prediction Framework Based on Pretrained Large Language Models

# 摘要

> 交通预测是ITS领域的核心组成部分，高精度预测对于提升交通管理水平至关重要。尽管深度学习驱动的交通预测模型在大量训练数据的支持下精度普遍提高，但因为空间-temporal交通数据集采集与存储成本高昂，往往难以获取。因此，在历史交通数据稀少的情况下，设计能够精准预测且具有良好泛化能力的模型是一项颇具挑战的任务。近年来，预训练的大型语言模型（LLMs）因其在跨模态知识转移及少量样本学习方面的突出表现引人注目。鉴于交通数据与语言数据类似的时间序列特性，我们创新性地提出了一种名为TPLLM的交通预测框架，它巧妙利用LLMs的优势。在这个框架内，我们运用CNNs构建序列嵌入层以捕获时间序列特征，并采用GCNs建立图嵌入层来提取空间特征，两者融合后转化为LLMs可接受的输入格式。通过采用LoRA微调策略优化TPLLM，不仅提升了学习效率，还降低了计算资源的需求。实验证明，TPLLM在面对完整样本集和少量样本预测场景时，均展现出了优异的表现力，有力支持了那些历史交通数据匮乏地区ITS技术的发展。

> Traffic prediction constitutes a pivotal facet within the purview of Intelligent Transportation Systems (ITS), and the attainment of highly precise predictions holds profound significance for efficacious traffic management. The precision of prevailing deep learning-driven traffic prediction models typically sees an upward trend with a rise in the volume of training data. However, the procurement of comprehensive spatiotemporal datasets for traffic is often fraught with challenges, primarily stemming from the substantial costs associated with data collection and retention. Consequently, developing a model that can achieve accurate predictions and good generalization ability in areas with limited historical traffic data is a challenging problem. It is noteworthy that the rapidly advancing pretrained Large Language Models (LLMs) of recent years have demonstrated exceptional proficiency in cross-modality knowledge transfer and few-shot learning. Recognizing the sequential nature of traffic data, similar to language, we introduce TPLLM, a novel traffic prediction framework leveraging LLMs. In this framework, we construct a sequence embedding layer based on Convolutional Neural Networks (CNNs) and a graph embedding layer based on Graph Convolutional Networks (GCNs) to extract sequence features and spatial features, respectively. These are subsequently integrated to form inputs that are suitable for LLMs. A Low-Rank Adaptation (LoRA) fine-tuning approach is applied to TPLLM, thereby facilitating efficient learning and minimizing computational demands. Experiments on two real-world datasets demonstrate that TPLLM exhibits commendable performance in both full-sample and few-shot prediction scenarios, effectively supporting the development of ITS in regions with scarce historical traffic data.

[Arxiv](https://arxiv.org/abs/2403.02221)