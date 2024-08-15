# LLMI3D：让LLM从一张2D图像中获得3D感知力

发布时间：2024年08月14日

`LLM应用` `自动驾驶` `增强现实`

> LLMI3D: Empowering LLM with 3D Perception from a Single 2D Image

# 摘要

> 随着自动驾驶、增强现实等领域的快速发展，3D感知算法变得至关重要。尽管如此，小型3D感知模型在逻辑推理和开放场景处理上仍显不足。同时，多模态大型语言模型虽在通用任务上表现优异，但在3D任务中因空间感知和几何输出能力不足而受限。为此，我们提出空间增强特征挖掘、3D信息精确解码及几何投影推理等创新方案，通过高效微调预训练模型，打造出强大的3D感知模型LLMI3D。我们还创建了包含详细描述和问答标注的IG3D数据集。实验结果显示，LLMI3D性能卓越，大幅领先现有技术。

> Recent advancements in autonomous driving, augmented reality, robotics, and embodied intelligence have necessitated 3D perception algorithms. However, current 3D perception methods, particularly small models, struggle with processing logical reasoning, question-answering, and handling open scenario categories. On the other hand, generative multimodal large language models (MLLMs) excel in general capacity but underperform in 3D tasks, due to weak spatial and local object perception, poor text-based geometric numerical output, and inability to handle camera focal variations. To address these challenges, we propose the following solutions: Spatial-Enhanced Local Feature Mining for better spatial feature extraction, 3D Query Token-Derived Info Decoding for precise geometric regression, and Geometry Projection-Based 3D Reasoning for handling camera focal length variations. We employ parameter-efficient fine-tuning for a pre-trained MLLM and develop LLMI3D, a powerful 3D perception MLLM. Additionally, we have constructed the IG3D dataset, which provides fine-grained descriptions and question-answer annotations. Extensive experiments demonstrate that our LLMI3D achieves state-of-the-art performance, significantly outperforming existing methods.

[Arxiv](https://arxiv.org/abs/2408.07422)