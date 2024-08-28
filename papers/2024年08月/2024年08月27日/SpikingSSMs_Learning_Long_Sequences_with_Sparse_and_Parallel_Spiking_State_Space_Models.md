# SpikingSSMs：利用稀疏并行的尖峰状态空间模型，高效学习长序列。

发布时间：2024年08月27日

`LLM应用` `人工智能` `神经网络`

> SpikingSSMs: Learning Long Sequences with Sparse and Parallel Spiking State Space Models

# 摘要

> 脉冲神经网络（SNNs），作为一种低能耗网络，近几十年来备受瞩目。尽管在视觉任务上SNNs与人工神经网络（ANNs）的竞争日益激烈，但它们在长序列任务中的应用却鲜有涉及，尽管其内在的时间动态特性。本研究中，我们通过结合状态空间模型（SSMs）的序列学习能力，开发了脉冲状态空间模型（SpikingSSMs），专门用于长序列学习。借鉴树突神经元结构，我们将神经元动态与SSM块分层融合，同时实现了稀疏突触计算。为解决事件驱动神经元动态与并行计算的矛盾，我们设计了一种轻量级替代动态网络，能精确预测重置后的膜电位，并兼容可学习阈值，大幅提升了训练速度。在长范围竞技基准任务中，SpikingSSM不仅与顶尖SSMs性能相当，还实现了高达90%的网络稀疏性。在语言建模领域，我们的网络在WikiText-103数据集上以仅三分之一的模型大小，显著超越了现有脉冲大型语言模型（spikingLLMs），彰显了其作为低计算成本LLMs骨干架构的潜力。

> Known as low energy consumption networks, spiking neural networks (SNNs) have gained a lot of attention within the past decades. While SNNs are increasing competitive with artificial neural networks (ANNs) for vision tasks, they are rarely used for long sequence tasks, despite their intrinsic temporal dynamics. In this work, we develop spiking state space models (SpikingSSMs) for long sequence learning by leveraging on the sequence learning abilities of state space models (SSMs). Inspired by dendritic neuron structure, we hierarchically integrate neuronal dynamics with the original SSM block, meanwhile realizing sparse synaptic computation. Furthermore, to solve the conflict of event-driven neuronal dynamics with parallel computing, we propose a light-weight surrogate dynamic network which accurately predicts the after-reset membrane potential and compatible to learnable thresholds, enabling orders of acceleration in training speed compared with conventional iterative methods. On the long range arena benchmark task, SpikingSSM achieves competitive performance to state-of-the-art SSMs meanwhile realizing on average 90\% of network sparsity. On language modeling, our network significantly surpasses existing spiking large language models (spikingLLMs) on the WikiText-103 dataset with only a third of the model size, demonstrating its potential as backbone architecture for low computation cost LLMs.

[Arxiv](https://arxiv.org/abs/2408.14909)