# 超越视觉理解：引入 PARROT-360V 用于视觉语言模型基准测评

发布时间：2024年11月19日

`LLM应用` `视觉语言模型` `评估基准`

> Beyond Visual Understanding: Introducing PARROT-360V for Vision Language Model Benchmarking

# 摘要

> 当前评估视觉语言模型（VLMs）的基准，往往难以全面测评模型理解与处理复杂视觉及文本内容的能力。它们一般聚焦于简单任务，这些任务无需深度推理或融合多种数据模式来解决初始问题。为弥补这一缺陷，我们推出了 PARROT-360V 基准，这是一个新颖且全面的基准，包含 2487 个富有挑战性的视觉谜题，旨在测试 VLMs 处理复杂视觉推理任务的水平。我们借助 PARROT-360V 对领先的模型，如 GPT-4o、Claude-3.5-Sonnet 以及 Gemini-1.5-Pro 进行了评估，以衡量它们将视觉线索与语言技能相结合，像人类解决问题那样完成任务的能力。我们的发现表明存在显著的性能差距：前沿模型在我们的基准上得分在 28%至 56%之间，远低于它们在热门基准上的表现。这凸显了当前 VLMs 在应对复杂多步推理任务时的局限性，也强调了需要更有力的评估框架来推动该领域的进步。

> Current benchmarks for evaluating Vision Language Models (VLMs) often fall short in thoroughly assessing model abilities to understand and process complex visual and textual content. They typically focus on simple tasks that do not require deep reasoning or the integration of multiple data modalities to solve an original problem. To address this gap, we introduce the PARROT-360V Benchmark, a novel and comprehensive benchmark featuring 2487 challenging visual puzzles designed to test VLMs on complex visual reasoning tasks. We evaluated leading models: GPT-4o, Claude-3.5-Sonnet, and Gemini-1.5-Pro, using PARROT-360V to assess their capabilities in combining visual clues with language skills to solve tasks in a manner akin to human problem-solving. Our findings reveal a notable performance gap: state-of-the-art models scored between 28 to 56 percentage on our benchmark, significantly lower than their performance on popular benchmarks. This underscores the limitations of current VLMs in handling complex, multi-step reasoning tasks and highlights the need for more robust evaluation frameworks to advance the field.

[Arxiv](https://arxiv.org/abs/2411.15201)