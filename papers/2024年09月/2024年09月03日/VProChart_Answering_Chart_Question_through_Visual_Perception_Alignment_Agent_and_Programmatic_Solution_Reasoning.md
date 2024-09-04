# VProChart：借助视觉感知对齐与程序化推理，精准解答图表问题

发布时间：2024年09月03日

`Agent` `数据可视化` `人工智能`

> VProChart: Answering Chart Question through Visual Perception Alignment Agent and Programmatic Solution Reasoning

# 摘要

> 图表在多个领域中广泛用于数据可视化，而图表问答（CQA）则是一项新兴任务，旨在自动解读图表数据并进行推理。然而，图表的复杂性及其问题的逻辑数值要求高，常使现有模型表现受限。为此，本文提出了VProChart框架，它通过结合视觉感知对齐代理（VPAgent）和程序化解决方案推理方法，有效应对了这些挑战。VPAgent模拟人类视觉感知，优化图表元素处理，提升上下文理解；而程序化解决方案推理则借助大型语言模型，将自然语言问题转化为结构化程序，实现精确推理。实验证明，VProChart在多个基准数据集上表现卓越，显著提升了图表理解和推理的能力。

> Charts are widely used for data visualization across various fields, including education, research, and business. Chart Question Answering (CQA) is an emerging task focused on the automatic interpretation and reasoning of data presented in charts. However, chart images are inherently difficult to interpret, and chart-related questions often involve complex logical and numerical reasoning, which hinders the performance of existing models. This paper introduces VProChart, a novel framework designed to address these challenges in CQA by integrating a lightweight Visual Perception Alignment Agent (VPAgent) and a Programmatic Solution Reasoning approach. VPAgent aligns and models chart elements based on principles of human visual perception, enhancing the understanding of chart context. The Programmatic Solution Reasoning approach leverages large language models (LLMs) to transform natural language reasoning questions into structured solution programs, facilitating precise numerical and logical reasoning. Extensive experiments on benchmark datasets such as ChartQA and PlotQA demonstrate that VProChart significantly outperforms existing methods, highlighting its capability in understanding and reasoning with charts.

[Arxiv](https://arxiv.org/abs/2409.01667)