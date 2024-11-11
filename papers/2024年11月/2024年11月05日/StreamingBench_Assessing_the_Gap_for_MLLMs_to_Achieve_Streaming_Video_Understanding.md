# StreamingBench：评估大型语言模型实现流媒体视频理解的差距

发布时间：2024年11月05日

`LLM应用` `语言模型`

> StreamingBench: Assessing the Gap for MLLMs to Achieve Streaming Video Understanding

# 摘要

> 多模态大型语言模型（MLLMs）的快速发展使其能力从图像理解扩展到了视频理解。然而，这些 MLLMs 中的大多数主要专注于离线视频理解，在进行任何查询之前需要对所有视频帧进行大量处理。这与人类实时观看、倾听、思考和响应流媒体输入的能力相比存在显著差距，凸显了当前 MLLMs 的局限性。在本文中，我们引入了 StreamingBench，这是第一个旨在评估 MLLMs 流媒体视频理解能力的综合基准。StreamingBench 评估了流媒体视频理解的三个核心方面：（1）实时视觉理解，（2）全源理解，（3）上下文理解。该基准包括 18 个任务，包含 900 个视频和 4500 个人工策划的问答对。每个视频在不同时间点呈现五个问题，以模拟连续的流媒体场景。我们在 StreamingBench 上对 13 个开源和专有 MLLMs 进行了实验，发现即使是像 Gemini 1.5 Pro 和 GPT-4o 这样最先进的专有 MLLMs，其流媒体视频理解能力也显著低于人类水平。我们希望我们的工作能够促进 MLLMs 的进一步发展，使它们能够在更现实的场景中接近人类水平的视频理解和交互。

> The rapid development of Multimodal Large Language Models (MLLMs) has expanded their capabilities from image comprehension to video understanding. However, most of these MLLMs focus primarily on offline video comprehension, necessitating extensive processing of all video frames before any queries can be made. This presents a significant gap compared to the human ability to watch, listen, think, and respond to streaming inputs in real time, highlighting the limitations of current MLLMs. In this paper, we introduce StreamingBench, the first comprehensive benchmark designed to evaluate the streaming video understanding capabilities of MLLMs. StreamingBench assesses three core aspects of streaming video understanding: (1) real-time visual understanding, (2) omni-source understanding, and (3) contextual understanding. The benchmark consists of 18 tasks, featuring 900 videos and 4,500 human-curated QA pairs. Each video features five questions presented at different time points to simulate a continuous streaming scenario. We conduct experiments on StreamingBench with 13 open-source and proprietary MLLMs and find that even the most advanced proprietary MLLMs like Gemini 1.5 Pro and GPT-4o perform significantly below human-level streaming video understanding capabilities. We hope our work can facilitate further advancements for MLLMs, empowering them to approach human-level video comprehension and interaction in more realistic scenarios.

[Arxiv](https://arxiv.org/abs/2411.03628)