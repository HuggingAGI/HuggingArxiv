# FedPT：在资源有限的边缘设备上，对大型语言模型进行联邦代理微调

发布时间：2024年09月30日

`LLM应用` `隐私保护` `联邦学习`

> FedPT: Federated Proxy-Tuning of Large Language Models on Resource-Constrained Edge Devices

# 摘要

> 尽管预训练的大型语言模型在多种语言任务中表现出色，但为了应对不同的下游任务，通常需要针对特定数据集进行微调。然而，这种微调过程涉及从个人收集数据，引发严重的隐私问题。联邦学习应运而生，成为在不共享原始数据的情况下协作训练模型的理想方案。尽管前景光明，但大型模型的联邦微调仍面临诸多挑战，如模型参数访问受限和高昂的计算、通信及内存开销。为此，本文提出了 \textbf{Fed}erated \textbf{P}roxy-\textbf{T}uning (FedPT)，一种仅需访问模型输出词汇预测的黑箱大型模型联邦微调新框架。具体而言，FedPT 首先让设备协作微调一个小型模型，然后服务器将微调后的小模型知识与预训练大模型的知识融合，构建一个性能媲美直接微调大模型的代理微调模型。实验结果显示，FedPT 在大幅降低计算、通信和内存开销的同时，仍能保持与直接联邦微调相当的性能。FedPT 为资源受限设备上高效、隐私保护的大型模型微调提供了可行方案，进一步提升了最先进大型模型的普及性和应用范围。

> Despite demonstrating superior performance across a variety of linguistic tasks, pre-trained large language models (LMs) often require fine-tuning on specific datasets to effectively address different downstream tasks. However, fine-tuning these LMs for downstream tasks necessitates collecting data from individuals, which raises significant privacy concerns. Federated learning (FL) has emerged as the de facto solution, enabling collaborative model training without sharing raw data. While promising, federated fine-tuning of large LMs faces significant challenges, including restricted access to model parameters and high computation, communication, and memory overhead. To address these challenges, this paper introduces \textbf{Fed}erated \textbf{P}roxy-\textbf{T}uning (FedPT), a novel framework for federated fine-tuning of black-box large LMs, requiring access only to their predictions over the output vocabulary instead of their parameters. Specifically, devices in FedPT first collaboratively tune a smaller LM, and then the server combines the knowledge learned by the tuned small LM with the knowledge learned by the larger pre-trained LM to construct a large proxy-tuned LM that can reach the performance of directly tuned large LMs. The experimental results demonstrate that FedPT can significantly reduce computation, communication, and memory overhead while maintaining competitive performance compared to directly federated fine-tuning of large LMs. FedPT offers a promising solution for efficient, privacy-preserving fine-tuning of large LMs on resource-constrained devices, broadening the accessibility and applicability of state-of-the-art large LMs.

[Arxiv](https://arxiv.org/abs/2410.00362)