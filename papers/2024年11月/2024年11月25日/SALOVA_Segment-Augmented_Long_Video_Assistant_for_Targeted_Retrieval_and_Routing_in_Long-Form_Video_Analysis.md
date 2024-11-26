# SALOVA：在长视频分析中用于目标检索和路由的分段增强型长视频助手

发布时间：2024年11月25日

`LLM应用` `智能助手`

> SALOVA: Segment-Augmented Long Video Assistant for Targeted Retrieval and Routing in Long-Form Video Analysis

# 摘要

> 尽管大型多模态模型有所进步，但受限于上下文长度和巨大的内存开销，将其应用于冗长且未经剪辑的视频内容仍困难重重。这些限制往往会造成大量信息丢失，降低模型响应的相关性。随着网络平台上视频数据呈指数增长，理解长视频对于推进广义智能意义重大。在本文中，我们推出了 SALOVA：段增强长视频助手，这是一个全新的视频-LLM 框架，旨在通过针对性的检索流程提升对长视频内容的理解。为达成此目标，我们攻克了两大主要难题：（i）我们推出了 SceneWalk 数据集，这是一个包含 87.8K 长视频的高质量集合，每个视频在段级别都有密集标注，能让模型捕捉场景的连续性并保持丰富的描述性语境。（ii）我们研发了强大的架构设计，融合了动态路由机制和时空投影仪，能依据用户的查询高效检索和处理相关视频段。我们的框架通过针对查询精准识别和检索相关视频段，缓解了当前视频-LMM 的局限性，进而提高了生成响应的上下文相关性。通过大量实验，SALOVA 在处理复杂长视频方面展现出更强的能力，在扩展序列中表现出保持上下文完整性的显著能力。

> Despite advances in Large Multi-modal Models, applying them to long and untrimmed video content remains challenging due to limitations in context length and substantial memory overhead. These constraints often lead to significant information loss and reduced relevance in the model responses. With the exponential growth of video data across web platforms, understanding long-form video is crucial for advancing generalized intelligence. In this paper, we introduce SALOVA: Segment-Augmented LOng Video Assistant, a novel video-LLM framework designed to enhance the comprehension of lengthy video content through targeted retrieval process. We address two main challenges to achieve it: (i) We present the SceneWalk dataset, a high-quality collection of 87.8K long videos, each densely captioned at the segment level to enable models to capture scene continuity and maintain rich descriptive context. (ii) We develop robust architectural designs integrating dynamic routing mechanism and spatio-temporal projector to efficiently retrieve and process relevant video segments based on user queries. Our framework mitigates the limitations of current video-LMMs by allowing for precise identification and retrieval of relevant video segments in response to queries, thereby improving the contextual relevance of the generated responses. Through extensive experiments, SALOVA demonstrates enhanced capability in processing complex long-form videos, showing significant capability to maintain contextual integrity across extended sequences.

[Arxiv](https://arxiv.org/abs/2411.16173)