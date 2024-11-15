# 针对设备端语音情感识别的轻量级 Transformer 重新进行参数化

发布时间：2024年11月14日

`其他` `物联网` `语音情感识别`

> Re-Parameterization of Lightweight Transformer for On-Device Speech Emotion Recognition

# 摘要

> 随着机器学习模型在边缘或物联网设备上的应用日益增多，在资源受限的物联网设备上部署先进模型依旧困难重重。Transformer 模型作为当下主流的神经架构，在众多领域大获成功，但其复杂性致使其难以在计算和存储能力有限的物联网设备上部署。尽管已探索了众多模型压缩手段，但往往会出现严重的性能衰退。为应对此问题，我们推出一种新方法——Transformer 重参数化，以提升轻量级 Transformer 模型的性能。它涵盖两个流程：训练阶段的高秩分解（HRF）流程和推理阶段的去高秩分解（deHRF）流程。在前者中，我们在轻量级 Transformer 的前馈网络（FFN）前插入一个额外的线性层。假定插入的 HRF 层能够增强模型的学习能力。在后者中，辅助 HRF 层会与后续的 FFN 层合并为一个线性层，进而恢复轻量级模型的原有结构。为检验所提方法的有效性，我们在 IEMOCAP、M3ED 和 DAIC-WOZ 数据集上的语音情感识别应用中，对 ConvTransformer、Conformer 和 SpeechFormer 这三个广泛使用的 Transformer 变体进行了评估。实验结果显示，我们提出的方法持续提升了轻量级 Transformer 的性能，甚至能使其与大型模型媲美。所提出的重参数化方法让先进的 Transformer 模型得以在资源受限的物联网设备上部署。

> With the increasing implementation of machine learning models on edge or Internet-of-Things (IoT) devices, deploying advanced models on resource-constrained IoT devices remains challenging. Transformer models, a currently dominant neural architecture, have achieved great success in broad domains but their complexity hinders its deployment on IoT devices with limited computation capability and storage size. Although many model compression approaches have been explored, they often suffer from notorious performance degradation. To address this issue, we introduce a new method, namely Transformer Re-parameterization, to boost the performance of lightweight Transformer models. It consists of two processes: the High-Rank Factorization (HRF) process in the training stage and the deHigh-Rank Factorization (deHRF) process in the inference stage. In the former process, we insert an additional linear layer before the Feed-Forward Network (FFN) of the lightweight Transformer. It is supposed that the inserted HRF layers can enhance the model learning capability. In the later process, the auxiliary HRF layer will be merged together with the following FFN layer into one linear layer and thus recover the original structure of the lightweight model. To examine the effectiveness of the proposed method, we evaluate it on three widely used Transformer variants, i.e., ConvTransformer, Conformer, and SpeechFormer networks, in the application of speech emotion recognition on the IEMOCAP, M3ED and DAIC-WOZ datasets. Experimental results show that our proposed method consistently improves the performance of lightweight Transformers, even making them comparable to large models. The proposed re-parameterization approach enables advanced Transformer models to be deployed on resource-constrained IoT devices.

[Arxiv](https://arxiv.org/abs/2411.09339)