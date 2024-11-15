# VCBench：一个针对视频认知中符号与抽象挑战的可控基准

发布时间：2024年11月13日

`LLM应用` `模型评估`

> VCBench: A Controllable Benchmark for Symbolic and Abstract Challenges in Video Cognition

# 摘要

> 大型视频语言模型（LVLMs）的最新进展促使评估基于视频任务认知能力的基准得以发展。然而，现有的大多数基准严重依赖网络收集的视频与人工注释或模型生成的问题相结合，这既限制了对视频内容的把控，又难以评估涉及符号元素和抽象概念的高级认知能力。为克服这些局限，我们推出了 VCBench，这是一个可控的基准，用于评测 LVLMs 的认知能力，涵盖不同难度层级的符号和抽象概念。借助基于 Python 的引擎生成视频数据，VCBench 能够精准控制视频内容，打造出具有复杂场景和抽象概念的动态、任务导向型视频。每个任务都搭配了针对特定认知挑战的定制问题模板，提供了严格的评估测试。我们的评估表明，即便是像 Qwen2-VL-72B 这样的最先进模型，在涉及抽象概念的简单视频认知任务中也表现不佳，随着视频复杂程度的提高，性能大幅下降 19％。这些发现揭示了 LVLMs 在高级认知任务方面的当前短板，也突显了 VCBench 在推动针对复杂视频认知挑战研发更强大 LVLMs 研究中的关键作用。

> Recent advancements in Large Video-Language Models (LVLMs) have driven the development of benchmarks designed to assess cognitive abilities in video-based tasks. However, most existing benchmarks heavily rely on web-collected videos paired with human annotations or model-generated questions, which limit control over the video content and fall short in evaluating advanced cognitive abilities involving symbolic elements and abstract concepts. To address these limitations, we introduce VCBench, a controllable benchmark to assess LVLMs' cognitive abilities, involving symbolic and abstract concepts at varying difficulty levels. By generating video data with the Python-based engine, VCBench allows for precise control over the video content, creating dynamic, task-oriented videos that feature complex scenes and abstract concepts. Each task pairs with tailored question templates that target specific cognitive challenges, providing a rigorous evaluation test. Our evaluation reveals that even state-of-the-art (SOTA) models, such as Qwen2-VL-72B, struggle with simple video cognition tasks involving abstract concepts, with performance sharply dropping by 19% as video complexity rises. These findings reveal the current limitations of LVLMs in advanced cognitive tasks and highlight the critical role of VCBench in driving research toward more robust LVLMs for complex video cognition challenges.

[Arxiv](https://arxiv.org/abs/2411.09105)