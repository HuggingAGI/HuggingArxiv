# 从信息理论视角剖析变分自编码器里的多模态集成

发布时间：2024年11月01日

`Agent` `机器人` `多模态学习`

> Analyzing Multimodal Integration in the Variational Autoencoder from an Information-Theoretic Perspective

# 摘要

> 人类感知天生就是多模态的。比如，我们会把视觉、本体感觉和触觉等信息整合成一种体验。所以，多模态学习对于构建能与现实世界稳健交互的机器人系统意义重大。多模态集成的一种潜在模型是多模态变分自编码器。变分自编码器（VAE）由两个网络构成，一个编码器将数据映射到随机潜在空间，一个解码器从潜在空间的元素中重建这些数据。多模态 VAE 在潜在空间的两个时间点整合来自不同模态的输入，因而可用作机器人代理的控制器。在此，我们采用这种架构并引入信息理论度量，以剖析不同模态的集成对于输入数据重建的重要程度。于是，我们计算了两种不同类型的度量，第一种叫单模态误差，衡量单个模态的信息对于该模态或所有模态重建的重要性。其次，名为精度损失的度量计算仅一个模态缺失信息对该模态或整个向量重建的影响。VAE 通过证据下界进行训练，它可写成两个不同项的总和，即重建项和潜在损失项。潜在损失的影响可通过一个额外变量加权，引入该变量是为了应对后验崩溃。在这里，我们训练具有四种不同加权方案的网络，并就其多模态集成能力进行分析。

> Human perception is inherently multimodal. We integrate, for instance, visual, proprioceptive and tactile information into one experience. Hence, multimodal learning is of importance for building robotic systems that aim at robustly interacting with the real world. One potential model that has been proposed for multimodal integration is the multimodal variational autoencoder. A variational autoencoder (VAE) consists of two networks, an encoder that maps the data to a stochastic latent space and a decoder that reconstruct this data from an element of this latent space. The multimodal VAE integrates inputs from different modalities at two points in time in the latent space and can thereby be used as a controller for a robotic agent. Here we use this architecture and introduce information-theoretic measures in order to analyze how important the integration of the different modalities are for the reconstruction of the input data. Therefore we calculate two different types of measures, the first type is called single modality error and assesses how important the information from a single modality is for the reconstruction of this modality or all modalities. Secondly, the measures named loss of precision calculate the impact that missing information from only one modality has on the reconstruction of this modality or the whole vector. The VAE is trained via the evidence lower bound, which can be written as a sum of two different terms, namely the reconstruction and the latent loss. The impact of the latent loss can be weighted via an additional variable, which has been introduced to combat posterior collapse. Here we train networks with four different weighting schedules and analyze them with respect to their capabilities for multimodal integration.

[Arxiv](https://arxiv.org/abs/2411.00522)