# NeMo-Aligner：高效模型对齐的可扩展工具集

发布时间：2024年05月02日

`LLM应用` `人工智能` `机器学习`

> NeMo-Aligner: Scalable Toolkit for Efficient Model Alignment

# 摘要

> 确保大型语言模型（LLMs）与人类的价值观和偏好保持一致，对于提升其实用性和安全性至关重要。然而，为这些参数量庞大的模型构建高效的对齐工具并非易事。为此，我们开发了 NeMo-Aligner，这是一款能够高效扩展至数百个 GPU 并行训练的模型对齐工具包。它集成了多种模型对齐范式的优化实现，包括基于人类反馈的强化学习（RLHF）、直接偏好优化（DPO）、SteerLM 以及自对弈微调（SPIN）。NeMo-Aligner 还支持在参数高效微调（PEFT）环境下运行大多数对齐技术。该工具包设计上注重扩展性，易于添加其他对齐技术。NeMo-Aligner 已在 Apache 2.0 许可下开源，并在 https://github.com/NVIDIA/NeMo-Aligner 欢迎社区贡献。

> Aligning Large Language Models (LLMs) with human values and preferences is essential for making them helpful and safe. However, building efficient tools to perform alignment can be challenging, especially for the largest and most competent LLMs which often contain tens or hundreds of billions of parameters. We create NeMo-Aligner, a toolkit for model alignment that can efficiently scale to using hundreds of GPUs for training. NeMo-Aligner comes with highly optimized and scalable implementations for major paradigms of model alignment such as: Reinforcement Learning from Human Feedback (RLHF), Direct Preference Optimization (DPO), SteerLM, and Self-Play Fine-Tuning (SPIN). Additionally, our toolkit supports running most of the alignment techniques in a Parameter Efficient Fine-Tuning (PEFT) setting. NeMo-Aligner is designed for extensibility, allowing support for other alignment techniques with minimal effort. It is open-sourced with Apache 2.0 License and we invite community contributions at https://github.com/NVIDIA/NeMo-Aligner

[Arxiv](https://arxiv.org/abs/2405.01481)