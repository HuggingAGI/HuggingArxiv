# Fit and Prune：一种快速且无需训练的视觉标记剪枝技术，专为多模态大型语言模型设计。

发布时间：2024年09月16日

`LLM应用` `人工智能` `计算机视觉`

> Fit and Prune: Fast and Training-free Visual Token Pruning for Multi-modal Large Language Models

# 摘要

> 多模态大型语言模型（MLLM）的进步常依赖大量图像标记来弥补视觉短板，但这不仅造成冗余，还加剧了高计算负担。标记修剪虽能提速，但何时及如何修剪仍具挑战。本文提出无需训练的 FitPrune 方法，能根据预算快速生成修剪方案，将修剪视为统计问题，旨在最小化修剪前后注意力分布的偏差。FitPrune 基于少量推理数据的注意力统计即可快速实现，避免昂贵试验。根据方案，MLLM 可在推理时直接移除冗余视觉标记。实验显示，FitPrune 大幅降低计算复杂度，同时保持高性能，如 LLaVA-NEXT 的 FLOPs 减少 54.9%，准确率仅下降 0.5%。修剪方案仅需约 5 分钟即可获得。代码详见 https://github.com/ywh187/FitPrune。

> Recent progress in Multimodal Large Language Models(MLLMs) often use large image tokens to compensate the visual shortcoming of MLLMs, which not only exhibits obvious redundancy but also greatly exacerbates the already high computation. Token pruning is an effective solution for speeding up MLLMs, but when and how to drop tokens still remains a challenge. In this paper, we propose a novel and training-free approach for the effective visual token pruning of MLLMs, termed FitPrune, which can quickly produce a complete pruning recipe for MLLMs according to a pre-defined budget. Specifically, FitPrune considers token pruning as a statistical problem of MLLM and its objective is to find out an optimal pruning scheme that can minimize the divergence of the attention distributions before and after pruning. In practice, FitPrune can be quickly accomplished based on the attention statistics from a small batch of inference data, avoiding the expensive trials of MLLMs. According to the pruning recipe, an MLLM can directly remove the redundant visual tokens of different examples during inference. To validate FitPrune, we apply it to a set of recent MLLMs, including LLaVA-1.5, LLaVA-HR and LLaVA-NEXT, and conduct extensive experiments on a set of benchmarks. The experimental results show that our FitPrune can not only reduce the computational complexity to a large extent, while retaining high performance, e.g., -54.9% FLOPs for LLaVA-NEXT with only 0.5% accuracy drop. Notably, the pruning recipe can be obtained in about 5 minutes. Our code is available at https://github.com/ywh187/FitPrune.

[Arxiv](https://arxiv.org/abs/2409.10197)