# FedMLLM：针对多模态异质性数据的联邦微调式 MLLM

发布时间：2024年11月21日

`LLM应用` `联邦学习` `多模态语言模型`

> FedMLLM: Federated Fine-tuning MLLM on Multimodal Heterogeneity Data

# 摘要

> 多模态大型语言模型（MLLMs）进步显著，在处理和理解多模态数据时展现出强大能力。借助联邦学习（FL）对 MLLMs 进行微调，能把私人数据源纳入进来，扩大训练数据的范围，进而增强其在隐私敏感领域的实际应用价值。不过，当下的研究尚处早期，尤其在应对现实应用中的	extbf{多模态异质性}方面。本文引入了一个基准，用于评估多模态异质场景下 MLLMs 联邦微调的各类下游任务，为该领域的研究打下基础。我们的基准涵盖两个数据集、五条比较基线、四个多模态场景，包含十多种模态异质性。为应对模态异质性带来的挑战，我们开发了通用的 FedMLLM 框架，它整合了四种有代表性的 FL 方法以及两种与模态无关的策略。大量实验结果表明，我们提出的 FL 范式通过拓展训练数据的范围和缓解多模态异质性，提升了 MLLMs 的性能。代码可在 https://github.com/1xbq1/FedMLLM 获取。

> Multimodal Large Language Models (MLLMs) have made significant advancements, demonstrating powerful capabilities in processing and understanding multimodal data. Fine-tuning MLLMs with Federated Learning (FL) allows for expanding the training data scope by including private data sources, thereby enhancing their practical applicability in privacy-sensitive domains. However, current research remains in the early stage, particularly in addressing the \textbf{multimodal heterogeneities} in real-world applications. In this paper, we introduce a benchmark for evaluating various downstream tasks in the federated fine-tuning of MLLMs within multimodal heterogeneous scenarios, laying the groundwork for the research in the field. Our benchmark encompasses two datasets, five comparison baselines, and four multimodal scenarios, incorporating over ten types of modal heterogeneities. To address the challenges posed by modal heterogeneity, we develop a general FedMLLM framework that integrates four representative FL methods alongside two modality-agnostic strategies. Extensive experimental results show that our proposed FL paradigm improves the performance of MLLMs by broadening the range of training data and mitigating multimodal heterogeneity. Code is available at https://github.com/1xbq1/FedMLLM

[Arxiv](https://arxiv.org/abs/2411.14717)