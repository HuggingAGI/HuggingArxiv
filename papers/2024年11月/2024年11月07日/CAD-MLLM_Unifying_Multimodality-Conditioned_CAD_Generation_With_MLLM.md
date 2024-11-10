# CAD-MLLM：用 MLLM 统一多模态条件下的 CAD 生成

发布时间：2024年11月07日

`LLM应用` `计算机辅助设计` `多模态数据`

> CAD-MLLM: Unifying Multimodality-Conditioned CAD Generation With MLLM

# 摘要

> 这篇论文旨在设计一个统一的计算机辅助设计（CAD）生成系统，该系统能够根据用户以文本描述、图像、点云甚至它们的组合形式输入的内容轻松生成 CAD 模型。为了实现这个目标，我们引入了 CAD-MLLM，这是第一个能够基于多模态输入生成参数化 CAD 模型的系统。具体来说，在 CAD-MLLM 框架内，我们利用 CAD 模型的命令序列，然后采用先进的大型语言模型（LLM）来对齐这些不同多模态数据和 CAD 模型的矢量化表示的特征空间。为了促进模型训练，我们设计了一个全面的数据构建和注释管道，为每个 CAD 模型配备相应的多模态数据。我们得到的数据集，名为 Omni-CAD，是第一个多模态 CAD 数据集，每个 CAD 模型都包含文本描述、多视图图像、点和命令序列。它包含大约 45 万个实例及其 CAD 构建序列。为了全面评估我们生成的 CAD 模型的质量，我们超越了当前专注于重建质量的评估指标，引入了评估拓扑质量和表面封闭程度的额外指标。大量实验结果表明，CAD-MLLM 显著优于现有的条件生成方法，并且对噪声和缺失点具有高度的鲁棒性。项目页面和更多可视化内容可以在：https://cad-mllm.github.io/ 找到。

> This paper aims to design a unified Computer-Aided Design (CAD) generation system that can easily generate CAD models based on the user's inputs in the form of textual description, images, point clouds, or even a combination of them. Towards this goal, we introduce the CAD-MLLM, the first system capable of generating parametric CAD models conditioned on the multimodal input. Specifically, within the CAD-MLLM framework, we leverage the command sequences of CAD models and then employ advanced large language models (LLMs) to align the feature space across these diverse multi-modalities data and CAD models' vectorized representations. To facilitate the model training, we design a comprehensive data construction and annotation pipeline that equips each CAD model with corresponding multimodal data. Our resulting dataset, named Omni-CAD, is the first multimodal CAD dataset that contains textual description, multi-view images, points, and command sequence for each CAD model. It contains approximately 450K instances and their CAD construction sequences. To thoroughly evaluate the quality of our generated CAD models, we go beyond current evaluation metrics that focus on reconstruction quality by introducing additional metrics that assess topology quality and surface enclosure extent. Extensive experimental results demonstrate that CAD-MLLM significantly outperforms existing conditional generative methods and remains highly robust to noises and missing points. The project page and more visualizations can be found at: https://cad-mllm.github.io/

[Arxiv](https://arxiv.org/abs/2411.04954)