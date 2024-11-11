# 通过潜在概念变量实现公平的上下文学习

发布时间：2024年11月04日

`LLM应用` `语言模型` `数据处理`

> Fair In-Context Learning via Latent Concept Variables

# 摘要

> 大型语言模型（LLMs）新兴的上下文学习（ICL）能力促使它们通过序列化方法在不同领域的预测任务中使用不同类型的数据。然而，随着在高风险领域的应用不断增加，已经表明LLMs可以从其预训练数据中继承社会偏见和歧视。在这项工作中，我们研究了在使用表格数据的上下文学习期间LLMs中的这种固有偏差。我们专注于一种最优的演示选择方法，该方法利用潜在概念变量进行资源高效的任务适应。我们设计了数据增强策略，减少预测结果与敏感变量之间的相关性，有助于在潜在概念学习期间促进公平。我们利用学习到的概念，并从训练数据集中选择演示，以便在推理期间获得公平的预测，同时保持模型的实用性。潜在概念变量是使用较小的内部LLM学习的，所选的演示可以用于较大的外部LLM的推理。我们通过经验验证，与多种启发式演示选择方法相比，公平的潜在变量方法在表格数据集上提高了公平性结果。

> The emerging in-context learning (ICL) ability of large language models (LLMs) has prompted their use for predictive tasks in various domains with different types of data facilitated by serialization methods. However, with increasing applications in high-stakes domains, it has been shown that LLMs can inherit social bias and discrimination from their pre-training data. In this work, we investigate this inherent bias in LLMs during in-context learning with tabular data. We focus on an optimal demonstration selection approach that utilizes latent concept variables for resource-efficient task adaptation. We design data augmentation strategies that reduce correlation between predictive outcomes and sensitive variables helping to promote fairness during latent concept learning. We utilize the learned concept and select demonstrations from a training dataset to obtain fair predictions during inference while maintaining model utility. The latent concept variable is learned using a smaller internal LLM and the selected demonstrations can be used for inference with larger external LLMs. We empirically verify that the fair latent variable approach improves fairness results on tabular datasets compared to multiple heuristic demonstration selection methods.

[Arxiv](https://arxiv.org/abs/2411.02671)