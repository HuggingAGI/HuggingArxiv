# BearLLM：融合先验知识与统一振动信号表示的轴承健康管理新框架

发布时间：2024年08月20日

`LLM应用` `机械工程`

> BearLLM: A Prior Knowledge-Enhanced Bearing Health Management Framework with Unified Vibration Signal Representation

# 摘要

> 我们创新性地提出了一种基于大型语言模型（BearLLM）的轴承健康管理框架，该框架通过处理用户提示和振动信号，统一了多个轴承相关任务。我们引入了先验知识增强的振动信号表示，以适应不同工作条件，并通过自适应采样、频域整合和无故障参考信号辅助输入，实现了输入维度的统一。我们首先训练故障分类网络，将提取的特征转换为词嵌入，并与文本嵌入结合，作为LLM的输入。为了验证方法的有效性，我们创建了首个大规模多模态轴承健康管理数据集，包含振动信号和文本描述。实验表明，BearLLM在九个故障诊断基准上表现卓越，超越了特定数据集的专用方法。我们公开了数据集、模型和代码，旨在推动工业多模态模型的发展（https://github.com/hatton613/BearLLM）。

> We propose a bearing health management framework leveraging large language models (BearLLM), a novel multimodal model that unifies multiple bearing-related tasks by processing user prompts and vibration signals. Specifically, we introduce a prior knowledge-enhanced unified vibration signal representation to handle various working conditions across multiple datasets. This involves adaptively sampling the vibration signals based on the sampling rate of the sensor, incorporating the frequency domain to unify input dimensions, and using a fault-free reference signal as an auxiliary input. To extract features from vibration signals, we first train a fault classification network, then convert and align the extracted features into word embedding, and finally concatenate these with text embedding as input to an LLM. To evaluate the performance of the proposed method, we constructed the first large-scale multimodal bearing health management (MBHM) dataset, including paired vibration signals and textual descriptions. With our unified vibration signal representation, BearLLM using one set of pre-trained weights achieves state-of-the-art performance on nine publicly available fault diagnosis benchmarks, outperforming specific methods designed for individual datasets. We provide a dataset, our model, and code to inspire future research on building more capable industrial multimodal models (https://github.com/hatton613/BearLLM).

[Arxiv](https://arxiv.org/abs/2408.11281)