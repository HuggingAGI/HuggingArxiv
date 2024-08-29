# 文本繁多，点云稀少：探索 3D 数据高效的语言与点云理解

发布时间：2024年08月28日

`LLM应用` `计算机视觉` `人工智能`

> More Text, Less Point: Towards 3D Data-Efficient Point-Language Understanding

# 摘要

> 让大型语言模型理解三维世界仍是一大挑战。因缺乏大规模3D-文本数据集，LLM在3D理解上的成功尚未复制。本文提出新任务：3D数据高效点-语言理解，旨在用最少3D点云和文本数据对实现稳健3D对象理解。为此，我们推出GreenPLM，通过更多文本数据弥补3D数据不足。借鉴CLIP对齐图像与文本，我们用预训练点云-文本编码器将3D点云空间映射到文本空间，无缝连接文本空间与LLM。建立点-文本-LLM连接后，我们扩展中间文本空间，增强文本-LLM对齐，减少对3D点云数据依赖。具体地，生成600万条3D对象自由文本描述，设计三阶段训练策略，帮助LLM探索不同模态间内在联系。为高效模态对齐，设计零参数跨注意力模块用于令牌池化。实验表明，GreenPLM仅需12%的3D训练数据即可实现卓越3D理解，且在纯文本数据上也表现出色。代码和权重详见：https://github.com/TangYuan96/GreenPLM。

> Enabling Large Language Models (LLMs) to comprehend the 3D physical world remains a significant challenge. Due to the lack of large-scale 3D-text pair datasets, the success of LLMs has yet to be replicated in 3D understanding. In this paper, we rethink this issue and propose a new task: 3D Data-Efficient Point-Language Understanding. The goal is to enable LLMs to achieve robust 3D object understanding with minimal 3D point cloud and text data pairs. To address this task, we introduce GreenPLM, which leverages more text data to compensate for the lack of 3D data. First, inspired by using CLIP to align images and text, we utilize a pre-trained point cloud-text encoder to map the 3D point cloud space to the text space. This mapping leaves us to seamlessly connect the text space with LLMs. Once the point-text-LLM connection is established, we further enhance text-LLM alignment by expanding the intermediate text space, thereby reducing the reliance on 3D point cloud data. Specifically, we generate 6M free-text descriptions of 3D objects, and design a three-stage training strategy to help LLMs better explore the intrinsic connections between different modalities. To achieve efficient modality alignment, we design a zero-parameter cross-attention module for token pooling. Extensive experimental results show that GreenPLM requires only 12% of the 3D training data used by existing state-of-the-art models to achieve superior 3D understanding. Remarkably, GreenPLM also achieves competitive performance using text-only data. The code and weights are available at: https://github.com/TangYuan96/GreenPLM.

[Arxiv](https://arxiv.org/abs/2408.15966)