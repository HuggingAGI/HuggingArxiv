# CCExpert：借助差异感知集成与基础数据集增强多语言大型模型于遥感变化字幕方面的能力

发布时间：2024年11月18日

`LLM应用` `图像识别`

> CCExpert: Advancing MLLM Capability in Remote Sensing Change Captioning with Difference-Aware Integration and a Foundational Dataset

# 摘要

> 遥感图像变化描述（RSICC）旨在为多时相遥感图像间的地表变化生成自然语言描述，详述变化对象（如增加或消失）的类别、位置和动态。当下许多方法试图借助多模态大型语言模型（MLLMs）的长序列理解与推理能力来完成这一任务。然而，若缺乏全面的数据支撑，这些方法往往会改变 MLLMs 的基本特征传输路径，破坏模型内的固有知识，限制其在 RSICC 中的潜力。本文中，我们基于全新的先进多模态大型模型框架提出了一种新型模型——CCExpert。首先，我们设计了一个差异感知集成模块，用于捕捉双时态图像间的多尺度差异，并将其融入原始图像语境，从而提升差异特征的信噪比。其次，我们构建了名为 CC-Foundation 的高质量、多元化数据集，包含 20 万对图像和 120 万个标题，为该领域的持续预训练提供充足的数据支持。最后，我们采用了三阶段渐进式训练流程，确保差异感知集成模块与预训练的 MLLM 深度融合。CCExpert 在 LEVIR-CC 基准上表现出色，$S^*_m = 81.80$，大幅超越以往的前沿方法。代码及部分数据集即将在 https://github.com/Meize0729/CCExpert 开源。

> Remote Sensing Image Change Captioning (RSICC) aims to generate natural language descriptions of surface changes between multi-temporal remote sensing images, detailing the categories, locations, and dynamics of changed objects (e.g., additions or disappearances). Many current methods attempt to leverage the long-sequence understanding and reasoning capabilities of multimodal large language models (MLLMs) for this task. However, without comprehensive data support, these approaches often alter the essential feature transmission pathways of MLLMs, disrupting the intrinsic knowledge within the models and limiting their potential in RSICC. In this paper, we propose a novel model, CCExpert, based on a new, advanced multimodal large model framework. Firstly, we design a difference-aware integration module to capture multi-scale differences between bi-temporal images and incorporate them into the original image context, thereby enhancing the signal-to-noise ratio of differential features. Secondly, we constructed a high-quality, diversified dataset called CC-Foundation, containing 200,000 image pairs and 1.2 million captions, to provide substantial data support for continue pretraining in this domain. Lastly, we employed a three-stage progressive training process to ensure the deep integration of the difference-aware integration module with the pretrained MLLM. CCExpert achieved a notable performance of $S^*_m=81.80$ on the LEVIR-CC benchmark, significantly surpassing previous state-of-the-art methods. The code and part of the dataset will soon be open-sourced at https://github.com/Meize0729/CCExpert.

[Arxiv](https://arxiv.org/abs/2411.11360)