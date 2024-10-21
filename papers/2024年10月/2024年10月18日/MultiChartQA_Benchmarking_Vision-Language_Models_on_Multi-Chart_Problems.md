# MultiChartQA：评估视觉-语言模型在多图表问题上的表现

发布时间：2024年10月18日

`LLM应用` `人工智能` `数据分析`

> MultiChartQA: Benchmarking Vision-Language Models on Multi-Chart Problems

# 摘要

> 多模态大型语言模型 (MLLM) 在视觉问答和图表理解等任务中表现出色，但现有图表任务基准难以应对现实世界中多图表场景的复杂性。当前基准多聚焦于单图表任务，忽视了实际应用中必需的多图表信息整合与多跳推理。为此，我们推出了 MultiChartQA 基准，涵盖直接问答、并行问答、比较推理和顺序推理四大领域，全面评估 MLLM 能力。评估结果显示，MLLM 与人类表现存在显著差距，凸显了多图表理解的挑战，并展示了 MultiChartQA 推动该领域发展的潜力。代码与数据已公开，详见 https://github.com/Zivenzhu/Multi-chart-QA。

> Multimodal Large Language Models (MLLMs) have demonstrated impressive abilities across various tasks, including visual question answering and chart comprehension, yet existing benchmarks for chart-related tasks fall short in capturing the complexity of real-world multi-chart scenarios. Current benchmarks primarily focus on single-chart tasks, neglecting the multi-hop reasoning required to extract and integrate information from multiple charts, which is essential in practical applications. To fill this gap, we introduce MultiChartQA, a benchmark that evaluates MLLMs' capabilities in four key areas: direct question answering, parallel question answering, comparative reasoning, and sequential reasoning. Our evaluation of a wide range of MLLMs reveals significant performance gaps compared to humans. These results highlight the challenges in multi-chart comprehension and the potential of MultiChartQA to drive advancements in this field. Our code and data are available at https://github.com/Zivenzhu/Multi-chart-QA

[Arxiv](https://arxiv.org/abs/2410.14179)