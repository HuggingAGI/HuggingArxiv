# Open-Amp：音频效果基础模型的合成数据框架

发布时间：2024年11月22日

`其他` `音频处理`

> Open-Amp: Synthetic Data Framework for Audio Effect Foundation Models

# 摘要

> 本文介绍了 Open-Amp，这一用于生成大规模、多样化音频效果数据的合成数据框架。音频效果与众多音乐音频处理及音乐信息检索（MIR）任务密切相关，像模拟音频效果建模、自动混音、音调匹配与转录等。现有的音频效果数据集存在局限性，通常涵盖的音频效果处理器较少，输入音频信号的数量也有限。我们所提出的框架通过众包开源音频效果仿真软件用户创建的吉他放大器和效果的神经网络仿真，克服了这些难题。这让 Open-Amp 的用户能够完全掌控由效果模型处理的输入信号，还能提供数百种设备的高品质仿真。Open-Amp 能够在训练时在线渲染音频，在数据增强方面极具灵活性。我们的实验表明，利用 Open-Amp 训练吉他效果编码器，在多个吉他效果分类任务中取得了全新的顶尖成果。此外，我们用 Open-Amp 训练了一个一对多的吉他效果模型，并通过操控其学习的潜在空间来模拟未曾见过的模拟效果，这表明了其对模拟吉他效果数据的可迁移性。

> This paper introduces Open-Amp, a synthetic data framework for generating large-scale and diverse audio effects data. Audio effects are relevant to many musical audio processing and Music Information Retrieval (MIR) tasks, such as modelling of analog audio effects, automatic mixing, tone matching and transcription. Existing audio effects datasets are limited in scope, usually including relatively few audio effects processors and a limited amount of input audio signals. Our proposed framework overcomes these issues, by crowdsourcing neural network emulations of guitar amplifiers and effects, created by users of open-source audio effects emulation software. This allows users of Open-Amp complete control over the input signals to be processed by the effects models, as well as providing high-quality emulations of hundreds of devices. Open-Amp can render audio online during training, allowing great flexibility in data augmentation. Our experiments show that using Open-Amp to train a guitar effects encoder achieves new state-of-the-art results on multiple guitar effects classification tasks. Furthermore, we train a one-to-many guitar effects model using Open-Amp, and use it to emulate unseen analog effects via manipulation of its learned latent space, indicating transferability to analog guitar effects data.

[Arxiv](https://arxiv.org/abs/2411.14972)