# 本研究通过置信度最大化方法，在测试时进行低秩适应，旨在提升视觉-语言模型在零-shot场景下的泛化能力。

发布时间：2024年07月22日

`LLM应用` `计算机视觉`

> Test-Time Low Rank Adaptation via Confidence Maximization for Zero-Shot Generalization of Vision-Language Models

# 摘要

> 传统上，在测试时调整预训练的视觉-语言模型（VLMs）是通过调整可学习提示来实现的，即测试时提示调整。本文提出了一种替代方案——测试时低秩适应（TTL），旨在提高大规模VLMs的零-shot泛化能力。借鉴了大型语言模型高效微调的最新进展，TTL通过最大化预测置信度来更新transformer编码器的注意力权重，实现了一种参数高效的测试时适应方法。通过加权熵损失，TTL确保了增强样本预测的一致性，同时仅在模型中引入了少量可训练参数，保持了提示和主干的冻结状态。在多种自然分布和跨域任务上的实验表明，TTL在严格的零-shot环境下，性能超越了其他测试时优化技术。具体来说，TTL在平均水平上显著优于传统的测试时提示调整方法。相关代码已公开在https://github.com/Razaimam45/TTL-Test-Time-Low-Rank-Adaptation。

> The conventional modus operandi for adapting pre-trained vision-language models (VLMs) during test-time involves tuning learnable prompts, ie, test-time prompt tuning. This paper introduces Test-Time Low-rank adaptation (TTL) as an alternative to prompt tuning for zero-shot generalization of large-scale VLMs. Taking inspiration from recent advancements in efficiently fine-tuning large language models, TTL offers a test-time parameter-efficient adaptation approach that updates the attention weights of the transformer encoder by maximizing prediction confidence. The self-supervised confidence maximization objective is specified using a weighted entropy loss that enforces consistency among predictions of augmented samples. TTL introduces only a small amount of trainable parameters for low-rank adapters in the model space while keeping the prompts and backbone frozen. Extensive experiments on a variety of natural distribution and cross-domain tasks show that TTL can outperform other techniques for test-time optimization of VLMs in strict zero-shot settings. Specifically, TTL outperforms test-time prompt tuning baselines with a significant improvement on average. Our code is available at at https://github.com/Razaimam45/TTL-Test-Time-Low-Rank-Adaptation.

[Arxiv](https://arxiv.org/abs/2407.15913)