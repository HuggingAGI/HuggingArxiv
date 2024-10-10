# HERM：以人为本，提升多模态 LLM 的理解力与基准测试

发布时间：2024年10月09日

`LLM应用` `人工智能` `计算机视觉`

> HERM: Benchmarking and Enhancing Multimodal LLMs for Human-Centric Understanding

# 摘要

> 多模态大型语言模型 (MLLM) 在视觉理解和指令跟随方面取得了显著进展，为更广泛的人类中心应用打开了新的大门。然而，现有图像-文本数据在精确模态对齐和多粒度信息整合方面存在不足，这对人类中心视觉理解至关重要。为此，我们推出了 HERM-Bench 基准，用于评估 MLLM 的人类中心理解能力。研究发现，现有 MLLM 在处理复杂人类中心场景时存在局限。为解决这一问题，我们创建了 HERM-100K 数据集，包含多层次人类中心注释，以提升 MLLM 训练效果。同时，我们开发了 HERM-7B 模型，利用 HERM-100K 数据进行增强训练。评估结果显示，HERM-7B 在人类中心维度上显著超越现有 MLLM，凸显了当前数据注释在人类中心视觉理解方面的不足。这项研究强调了专门数据集和基准在提升 MLLM 人类中心理解能力中的关键作用。

> The significant advancements in visual understanding and instruction following from Multimodal Large Language Models (MLLMs) have opened up more possibilities for broader applications in diverse and universal human-centric scenarios. However, existing image-text data may not support the precise modality alignment and integration of multi-grained information, which is crucial for human-centric visual understanding. In this paper, we introduce HERM-Bench, a benchmark for evaluating the human-centric understanding capabilities of MLLMs. Our work reveals the limitations of existing MLLMs in understanding complex human-centric scenarios. To address these challenges, we present HERM-100K, a comprehensive dataset with multi-level human-centric annotations, aimed at enhancing MLLMs' training. Furthermore, we develop HERM-7B, a MLLM that leverages enhanced training data from HERM-100K. Evaluations on HERM-Bench demonstrate that HERM-7B significantly outperforms existing MLLMs across various human-centric dimensions, reflecting the current inadequacy of data annotations used in MLLM training for human-centric visual understanding. This research emphasizes the importance of specialized datasets and benchmarks in advancing the MLLMs' capabilities for human-centric understanding.

[Arxiv](https://arxiv.org/abs/2410.06777)