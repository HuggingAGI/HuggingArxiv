# 量化LoRA技术助力联邦学习，强化数据与模型隐私保护

发布时间：2024年06月16日

`Agent

理由：这篇论文主要关注的是在联邦学习中保护数据和模型隐私的新方法，特别是在大型语言模型（LLMs）的背景下。它提出了一种新的策略，即在训练时仅传输模型参数的量化版本，并结合了LoRA技术以降低通信成本。这种方法可以被视为一种智能代理（Agent）的行为，因为它在保护隐私的同时，有效地管理和优化了资源的使用。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论。` `联邦学习` `隐私保护`

> Promoting Data and Model Privacy in Federated Learning through Quantized LoRA

# 摘要

> 传统的联邦学习专注于保护分布式数据隐私，通过将全局模型发送到边缘设备进行参数更新。但随着大型语言模型（LLMs）的兴起，这些模型因其所需的大量数据和计算资源而成为宝贵的知识产权。为了在联邦学习中同时保护数据和模型隐私，我们提出了一种新方法，仅在训练时传输模型参数的量化版本。这种方法不仅确保了参数更新的准确性，还防止了客户端接触到与中央托管模型性能相当的模型。此外，我们将此量化策略与LoRA（一种高效的微调技术）结合，大幅降低了通信成本。我们的框架\textsc{FedLPP}在联邦学习中有效保障了数据和模型隐私，同时中央模型展现出优秀的泛化能力，并以高效利用资源的方式进行训练。

> Conventional federated learning primarily aims to secure the privacy of data distributed across multiple edge devices, with the global model dispatched to edge devices for parameter updates during the learning process. However, the development of large language models (LLMs) requires substantial data and computational resources, rendering them valuable intellectual properties for their developers and owners. To establish a mechanism that protects both data and model privacy in a federated learning context, we introduce a method that just needs to distribute a quantized version of the model's parameters during training. This method enables accurate gradient estimations for parameter updates while preventing clients from accessing a model whose performance is comparable to the centrally hosted one. Moreover, we combine this quantization strategy with LoRA, a popular and parameter-efficient fine-tuning method, to significantly reduce communication costs in federated learning. The proposed framework, named \textsc{FedLPP}, successfully ensures both data and model privacy in the federated learning context. Additionally, the learned central model exhibits good generalization and can be trained in a resource-efficient manner.

![量化LoRA技术助力联邦学习，强化数据与模型隐私保护](../../../paper_images/2406.10976/x1.png)

![量化LoRA技术助力联邦学习，强化数据与模型隐私保护](../../../paper_images/2406.10976/x2.png)

[Arxiv](https://arxiv.org/abs/2406.10976)