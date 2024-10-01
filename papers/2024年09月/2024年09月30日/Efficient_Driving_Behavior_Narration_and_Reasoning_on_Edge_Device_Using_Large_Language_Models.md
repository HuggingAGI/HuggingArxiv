# 利用大型语言模型在边缘设备上实现高效驾驶行为的叙述与推理

发布时间：2024年09月30日

`LLM应用` `自动驾驶` `边缘计算`

> Efficient Driving Behavior Narration and Reasoning on Edge Device Using Large Language Models

# 摘要

> 深度学习与强大推理能力的结合，极大地推动了自动驾驶技术的发展。大型语言模型（LLM）在此领域中，能够以接近人类感知的精度描述驾驶场景和行为，尤其是在视觉任务中表现出色。与此同时，边缘计算的迅猛发展，凭借其数据源近在咫尺的优势，使得边缘设备在自动驾驶中的地位日益重要。这些设备在本地处理数据，有效减少传输延迟，节省带宽，并实现更快的响应速度。在此背景下，我们提出了一种将LLM应用于边缘设备的驾驶行为叙述与推理框架。该框架由多个路边单元构成，每个单元均部署有LLM，通过5G网络高效收集并交换道路数据。实验结果显示，边缘设备上的LLM能够实现令人满意的响应速度。为进一步优化系统性能，我们设计了一种提示策略，该策略巧妙融合了环境、代理及运动等多模态信息。在OpenDV-Youtube数据集上的实验验证了我们的方法在两项任务中均显著提升了性能。

> Deep learning architectures with powerful reasoning capabilities have driven significant advancements in autonomous driving technology. Large language models (LLMs) applied in this field can describe driving scenes and behaviors with a level of accuracy similar to human perception, particularly in visual tasks. Meanwhile, the rapid development of edge computing, with its advantage of proximity to data sources, has made edge devices increasingly important in autonomous driving. Edge devices process data locally, reducing transmission delays and bandwidth usage, and achieving faster response times. In this work, we propose a driving behavior narration and reasoning framework that applies LLMs to edge devices. The framework consists of multiple roadside units, with LLMs deployed on each unit. These roadside units collect road data and communicate via 5G NSR/NR networks. Our experiments show that LLMs deployed on edge devices can achieve satisfactory response speeds. Additionally, we propose a prompt strategy to enhance the narration and reasoning performance of the system. This strategy integrates multi-modal information, including environmental, agent, and motion data. Experiments conducted on the OpenDV-Youtube dataset demonstrate that our approach significantly improves performance across both tasks.

[Arxiv](https://arxiv.org/abs/2409.20364)