# MoDex：借助神经手模型学习，实现高维灵巧控制规划

发布时间：2024年09月17日

`Agent` `机器人` `人工智能`

> MoDex: Planning High-Dimensional Dexterous Control via Learning Neural Hand Models

# 摘要

> 在高维动作空间中控制手部一直是个难题，但人类却能轻松完成灵巧任务。本文受人类具身认知启发，将灵巧手视为可学习系统，并推出MoDex框架。该框架利用神经手模型捕捉手部运动动态，开发了高效的双向规划方法。此外，结合大型语言模型，MoDex能生成“剪刀手”和“摇滚”等多样手势。理论与实验均证明，将系统动态分解为预训练手模型与外部模型，能显著提升数据效率。更多可视化结果请访问https://tongwu19.github.io/MoDex。

> Controlling hands in the high-dimensional action space has been a longstanding challenge, yet humans naturally perform dexterous tasks with ease. In this paper, we draw inspiration from the human embodied cognition and reconsider dexterous hands as learnable systems. Specifically, we introduce MoDex, a framework which employs a neural hand model to capture the dynamical characteristics of hand movements. Based on the model, a bidirectional planning method is developed, which demonstrates efficiency in both training and inference. The method is further integrated with a large language model to generate various gestures such as ``Scissorshand" and ``Rock\&Roll." Moreover, we show that decomposing the system dynamics into a pretrained hand model and an external model improves data efficiency, as supported by both theoretical analysis and empirical experiments. Additional visualization results are available at https://tongwu19.github.io/MoDex.

[Arxiv](https://arxiv.org/abs/2409.10983)