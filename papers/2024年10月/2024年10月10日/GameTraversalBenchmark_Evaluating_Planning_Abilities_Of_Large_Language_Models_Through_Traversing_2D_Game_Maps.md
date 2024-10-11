# GameTraversalBenchmark：通过探索二维游戏地图，评估大型语言模型的规划能力

发布时间：2024年10月10日

`LLM应用` `人工智能`

> GameTraversalBenchmark: Evaluating Planning Abilities Of Large Language Models Through Traversing 2D Game Maps

# 摘要

> 大型语言模型（LLMs）在自然语言生成与理解方面表现卓越。然而，这些模型在规划能力上的表现仍待探索。为此，我们推出了 GameTraversalBenchmark（GTB），一个包含多样化2D游戏地图的基准测试。在GTB中，LLM需以最少步数和错误完成任务。测试结果显示，GPT-4-Turbo在GTB\_Score（GTBS）上以44.97%的得分领先。同时，我们对大型推理模型o1进行了初步测试，其GTBS得分为67.84%，凸显了当前模型的挑战。更多详情请访问：https://github.com/umair-nasir14/Game-Traversal-Benchmark。

> Large language models (LLMs) have recently demonstrated great success in generating and understanding natural language. While they have also shown potential beyond the domain of natural language, it remains an open question as to what extent and in which way these LLMs can plan. We investigate their planning capabilities by proposing GameTraversalBenchmark (GTB), a benchmark consisting of diverse 2D grid-based game maps. An LLM succeeds if it can traverse through given objectives, with a minimum number of steps and a minimum number of generation errors. We evaluate a number of LLMs on GTB and found that GPT-4-Turbo achieved the highest score of 44.97% on GTB\_Score (GTBS), a composite score that combines the three above criteria. Furthermore, we preliminarily test large reasoning models, namely o1, which scores $67.84\%$ on GTBS, indicating that the benchmark remains challenging for current models. Code, data, and documentation are available at https://github.com/umair-nasir14/Game-Traversal-Benchmark.

[Arxiv](https://arxiv.org/abs/2410.07765)