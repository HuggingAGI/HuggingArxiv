# TurtleBench：海龟几何中的可视化编程基准

发布时间：2024年10月31日

`LLM应用` `人工智能` `几何图案推理`

> TurtleBench: A Visual Programming Benchmark in Turtle Geometry

# 摘要

> 人类自幼就具备对图像和场景中的几何图案进行推理的能力。然而，开发出能进行类似推理的大型多模态模型（LMMs）却困难重重，这凸显出我们急需强有力的评估方法来衡量这些能力。我们推出了 TurtleBench 基准，旨在评估 LMMs 对几何图案的解读能力（无论是基于视觉示例、文本指令，还是两者兼具），并生成精确的代码输出。TurtleBench 受用于教导儿童基础编码和几何概念的乌龟几何理念启发，其任务包含具有底层算法逻辑的图案形状。我们的评估显示，主流的 LMMs 在这些任务上表现欠佳，GPT-4o 在最简单的任务上准确率仅为 19％，少量样本提示对其性能的提升也微乎其微（<2％）。TurtleBench 揭示了人类和人工智能在直观视觉几何理解方面的差距，为该领域的未来研究铺平了道路。TurtleBench 是评估 LMMs 中视觉理解与代码生成能力整合的少数基准之一，为未来研究搭建了平台。本文的代码和数据集可在此获取：https://github.com/sinaris76/TurtleBench

> Humans have the ability to reason about geometric patterns in images and scenes from a young age. However, developing large multimodal models (LMMs) capable of similar reasoning remains a challenge, highlighting the need for robust evaluation methods to assess these capabilities. We introduce TurtleBench, a benchmark designed to evaluate LMMs' capacity to interpret geometric patterns -- given visual examples, textual instructions, or both -- and generate precise code outputs. Inspired by turtle geometry, a notion used to teach children foundational coding and geometric concepts, TurtleBench features tasks with patterned shapes that have underlying algorithmic logic. Our evaluation reveals that leading LMMs struggle significantly with these tasks, with GPT-4o achieving only 19\% accuracy on the simplest tasks and few-shot prompting only marginally improves their performance ($<2\%$). TurtleBench highlights the gap between human and AI performance in intuitive and visual geometrical understanding, setting the stage for future research in this area. TurtleBench stands as one of the few benchmarks to evaluate the integration of visual understanding and code generation capabilities in LMMs, setting the stage for future research. Code and Dataset for this paper is provided here: https://github.com/sinaris76/TurtleBench

[Arxiv](https://arxiv.org/abs/2411.00264)