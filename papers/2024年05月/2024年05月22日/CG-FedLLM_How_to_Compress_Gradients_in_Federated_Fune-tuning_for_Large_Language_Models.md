# CG-FedLLM：大型语言模型联邦微调中的梯度压缩策略

发布时间：2024年05月22日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在联邦学习（FL）环境下的应用，特别是在保护隐私和降低通信成本方面的创新方法。论文提出了CG-FedLLM流程和相关的策略（如TGAP和FAF），这些都是在实际应用中优化LLMs性能和效率的具体技术。因此，这篇论文更符合LLM应用分类，因为它关注的是LLMs在特定技术环境下的实际应用和改进。` `联邦学习` `隐私保护`

> CG-FedLLM: How to Compress Gradients in Federated Fune-tuning for Large Language Models

# 摘要

> 大型语言模型（LLMs）的成功关键在于集中学习（CL）模式下的大量训练数据。但这种集中收集方式引发了隐私担忧，联邦学习（FL）作为一种解决方案，通过传输梯度而非原始数据来保护隐私。然而，LLMs的FL因其巨大参数而面临高昂的通信成本。本研究创新性地提出了CG-FedLLM流程，通过在客户端和服务器端分别部署编码器和解码器来压缩梯度，从而提升通信效率。我们还设计了时间集成梯度感知预训练（TGAP）和联邦自编码器参与的微调（FAF）策略，有效识别并压缩关键梯度。实验结果表明，这种方法不仅降低了通信成本，还在C-Eval基准测试中使用LlaMA模型实现了平均3分的性能提升。我们的编码器-解码器能够智能过滤并保留重要梯度特征。此外，我们还深入分析了信号噪声比、压缩率和框架的鲁棒性，为构建更高效和安全的LLMs提供了重要见解。

> The success of current Large-Language Models (LLMs) hinges on extensive training data that is collected and stored centrally, called Centralized Learning (CL). However, such a collection manner poses a privacy threat, and one potential solution is Federated Learning (FL), which transfers gradients, not raw data, among clients. Unlike traditional networks, FL for LLMs incurs significant communication costs due to their tremendous parameters. This study introduces an innovative approach to compress gradients to improve communication efficiency during LLM FL, formulating the new FL pipeline named CG-FedLLM. This approach integrates an encoder on the client side to acquire the compressed gradient features and a decoder on the server side to reconstruct the gradients. We also developed a novel training strategy that comprises Temporal-ensemble Gradient-Aware Pre-training (TGAP) to identify characteristic gradients of the target model and Federated AutoEncoder-Involved Fine-tuning (FAF) to compress gradients adaptively. Extensive experiments confirm that our approach reduces communication costs and improves performance (e.g., average 3 points increment compared with traditional CL- and FL-based fine-tuning with LlaMA on a well-recognized benchmark, C-Eval). This improvement is because our encoder-decoder, trained via TGAP and FAF, can filter gradients while selectively preserving critical features. Furthermore, we present a series of experimental analyses focusing on the signal-to-noise ratio, compression rate, and robustness within this privacy-centric framework, providing insight into developing more efficient and secure LLMs.

[Arxiv](https://arxiv.org/abs/2405.13746)