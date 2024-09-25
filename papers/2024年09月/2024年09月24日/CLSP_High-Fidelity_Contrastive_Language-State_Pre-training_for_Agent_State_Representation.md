# CLSP：高保真对比语言-状态预训练，专为代理状态表示设计

发布时间：2024年09月24日

`Agent` `人工智能`

> CLSP: High-Fidelity Contrastive Language-State Pre-training for Agent State Representation

# 摘要

> 随着AI的迅猛发展，多模态学习成为研究热点。智能体的状态信息，与图像、视频和语言并列，是传递精确信息的关键。尽管强化学习和多模态大模型广泛应用，状态模态的表示仍显滞后。为此，我们提出了高保真对比语言-状态预训练（CLSP）方法，能将状态信息精准编码，适用于强化学习和多模态大模型。我们首先通过分类任务预训练编码器，获取粗粒度信息。接着，构建状态与语言描述的数据对，用预训练编码器初始化CLSP编码器。随后，通过对比学习训练CLSP编码器，有效表示精确状态信息。此外，采用随机傅里叶特征（RFF）方法增强数值信息表示，实现高保真映射。实验结果显示，我们的表示方法在精度与泛化能力上表现卓越，在文本-状态检索、强化学习导航任务及多模态大模型理解中均取得优异成绩。

> With the rapid development of artificial intelligence, multimodal learning has become an important research area. For intelligent agents, the state is a crucial modality to convey precise information alongside common modalities like images, videos, and language. This becomes especially clear with the broad adoption of reinforcement learning and multimodal large language models. Nevertheless, the representation of state modality still lags in development. To this end, we propose a High-Fidelity Contrastive Language-State Pre-training (CLSP) method, which can accurately encode state information into general representations for both reinforcement learning and multimodal large language models. Specifically, we first design a pre-training task based on the classification to train an encoder with coarse-grained information. Next, we construct data pairs of states and language descriptions, utilizing the pre-trained encoder to initialize the CLSP encoder. Then, we deploy contrastive learning to train the CLSP encoder to effectively represent precise state information. Additionally, we enhance the representation of numerical information using the Random Fourier Features (RFF) method for high-fidelity mapping. Extensive experiments demonstrate the superior precision and generalization capabilities of our representation, achieving outstanding results in text-state retrieval, reinforcement learning navigation tasks, and multimodal large language model understanding.

[Arxiv](https://arxiv.org/abs/2409.15806)