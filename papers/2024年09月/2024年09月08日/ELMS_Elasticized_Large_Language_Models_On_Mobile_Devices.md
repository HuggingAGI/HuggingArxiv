# ELMS：移动设备上的弹性大型语言模型

发布时间：2024年09月08日

`LLM应用` `移动设备` `人工智能`

> ELMS: Elasticized Large Language Models On Mobile Devices

# 摘要

> On-device 大型语言模型 (LLMs) 正在重塑移动 AI，不仅支持 UI 自动化等应用，还解决了隐私问题。当前，普遍做法是部署一个全能的 LLM 作为各种应用的通用解决方案，即 LLM-as-a-Service (LLMaaS)。然而，这一方法面临一个关键挑战：现有 LLMs 缺乏灵活性，难以适应不同应用中多样化的推理延迟服务级别目标 (SLOs)。为此，我们推出了 ELMS，一种专为 LLMaaS 模型和提示维度提供弹性的 on-device LLM 服务。该系统包含：一次性神经元重排技术，利用 transformer 模型的内在排列一致性，创建高质量、弹性子模型，切换成本极低；双头紧凑语言模型，高效优化提示并协调模型与提示间的弹性适应。我们在多款现成智能手机上实现了 ELMS，并通过独立 NLP/移动代理数据集和合成端到端跟踪进行评估。结果显示，在各种 SLOs 下，ELMS 在平均绝对准确率上分别比四个强基线高出最多 16.83% 和 11.04%，且 Time-To-First-Token (TTFT) 切换开销小于 1%，内存使用相当，离线 GPU 小时数少于 100。

> On-device Large Language Models (LLMs) are revolutionizing mobile AI, enabling applications such as UI automation while addressing privacy concerns. Currently, the standard approach involves deploying a single, robust LLM as a universal solution for various applications, often referred to as LLM-as-a-Service (LLMaaS). However, this approach faces a significant system challenge: existing LLMs lack the flexibility to accommodate the diverse Service-Level Objectives (SLOs) regarding inference latency across different applications. To address this issue, we introduce ELMS, an on-device LLM service designed to provide elasticity in both the model and prompt dimensions of an LLMaaS. This system includes: A one-time neuron reordering technique, which utilizes the inherent permutation consistency within transformer models to create high-quality, elastic sub-models with minimal runtime switching costs. A dual-head compact language model, which efficiently refines prompts and coordinates the elastic adaptation between the model and the prompt. We have implemented this elastic on-device LLM service on several off-the-shelf (COTS) smartphones and evaluate ELMS using both standalone NLP/mobile-agent datasets and synthesized end-to-end traces. Across a range of SLOs, ELMS surpasses four strong baselines by up to 16.83% and 11.04% in absolute accuracy on average, with less than 1% Time-To-First-Token (TTFT) switching overhead, comparable memory usage, and fewer than 100 offline GPU hours.

[Arxiv](https://arxiv.org/abs/2409.09071)