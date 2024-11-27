# g3D-LF：适用于具身任务的可通用化 3D 语言特征场

发布时间：2024年11月25日

`Agent` `3D 技术` `具身任务`

> g3D-LF: Generalizable 3D-Language Feature Fields for Embodied Tasks

# 摘要

> 我们推出了通用化 3D 语言特征场（g3D-LF），这是一个基于大规模 3D 语言数据集预训练而成的 3D 表示模型，服务于具身任务。我们的 g3D-LF 对来自代理的姿态 RGB-D 图像进行处理，以编码特征场，用于：1. 从 3D 场景的任意位置进行新视图表示预测；2. 生成以代理为中心的 BEV 地图；3. 在上述表示中借助多粒度语言查询目标。我们的这种表示能够推广到未曾见过的环境，达成实时构建与动态更新。通过沿采样光线对潜在特征进行体积渲染，并借助多尺度编码器整合语义和空间关系，我们的 g3D-LF 经由多级对比学习，在不同尺度和视角生成与多粒度语言相契合的表示。另外，我们还准备了一个大规模 3D 语言数据集，让特征场的表示与语言相匹配。在全景和单目设置下的视觉和语言导航、零样本对象导航以及情境问答任务中的大量实验，彰显了我们的 g3D-LF 在具身任务中的显著优势和有效性。

> We introduce Generalizable 3D-Language Feature Fields (g3D-LF), a 3D representation model pre-trained on large-scale 3D-language dataset for embodied tasks. Our g3D-LF processes posed RGB-D images from agents to encode feature fields for: 1) Novel view representation predictions from any position in the 3D scene; 2) Generations of BEV maps centered on the agent; 3) Querying targets using multi-granularity language within the above-mentioned representations. Our representation can be generalized to unseen environments, enabling real-time construction and dynamic updates. By volume rendering latent features along sampled rays and integrating semantic and spatial relationships through multiscale encoders, our g3D-LF produces representations at different scales and perspectives, aligned with multi-granularity language, via multi-level contrastive learning. Furthermore, we prepare a large-scale 3D-language dataset to align the representations of the feature fields with language. Extensive experiments on Vision-and-Language Navigation under both Panorama and Monocular settings, Zero-shot Object Navigation, and Situated Question Answering tasks highlight the significant advantages and effectiveness of our g3D-LF for embodied tasks.

[Arxiv](https://arxiv.org/abs/2411.17030)