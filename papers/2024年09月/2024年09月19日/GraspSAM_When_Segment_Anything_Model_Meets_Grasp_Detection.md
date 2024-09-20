# GraspSAM：分割模型与抓取检测的邂逅

发布时间：2024年09月19日

`LLM应用` `机器人` `自动化`

> GraspSAM: When Segment Anything Model Meets Grasp Detection

# 摘要

> 抓取检测需要灵活应对各种形状的物体，且无需预知物体信息，同时提供用户友好的直观控制。本文推出的 GraspSAM 是 Segment Anything Model (SAM) 的创新扩展，专为提示驱动和类别无关的抓取检测设计。与依赖小规模训练数据的旧方法不同，GraspSAM 借助 SAM 的大规模训练和提示基础分割能力，高效支持目标物体和类别无关的抓取。通过适配器、可学习令牌嵌入和轻量级解码器的结合，GraspSAM 仅需少量微调即可将物体分割与抓取预测融为一体。该模型在 Jacquard、Grasp-Anything 和 Grasp-Anything++ 等多个数据集上达到顶尖性能。实验证明，GraspSAM 能灵活处理点、框和语言等多种提示，展现了其在实际机器人应用中的强大鲁棒性和高效性。

> Grasp detection requires flexibility to handle objects of various shapes without relying on prior knowledge of the object, while also offering intuitive, user-guided control. This paper introduces GraspSAM, an innovative extension of the Segment Anything Model (SAM), designed for prompt-driven and category-agnostic grasp detection. Unlike previous methods, which are often limited by small-scale training data, GraspSAM leverages the large-scale training and prompt-based segmentation capabilities of SAM to efficiently support both target-object and category-agnostic grasping. By utilizing adapters, learnable token embeddings, and a lightweight modified decoder, GraspSAM requires minimal fine-tuning to integrate object segmentation and grasp prediction into a unified framework. The model achieves state-of-the-art (SOTA) performance across multiple datasets, including Jacquard, Grasp-Anything, and Grasp-Anything++. Extensive experiments demonstrate the flexibility of GraspSAM in handling different types of prompts (such as points, boxes, and language), highlighting its robustness and effectiveness in real-world robotic applications.

[Arxiv](https://arxiv.org/abs/2409.12521)