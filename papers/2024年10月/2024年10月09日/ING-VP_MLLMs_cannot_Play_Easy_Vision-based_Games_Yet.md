# ING-VP: 多模态大型语言模型尚无法应对简单的视觉游戏挑战

发布时间：2024年10月09日

`LLM应用` `人工智能` `游戏开发`

> ING-VP: MLLMs cannot Play Easy Vision-based Games Yet

# 摘要

> 随着多模态大型语言模型 (MLLM) 在各类任务中表现愈发强劲，评估这些前沿模型的基准测试也日趋复杂和全面。这些基准测试不仅考验模型的感知、推理和规划能力，还引入了新的挑战。然而，现有基准在评估基于图像空间关系的多步骤规划方面仍有不足。为此，我们推出了 ING-VP，首个基于互动游戏的视觉规划基准，专为测试 MLLM 的空间想象力和多步骤推理能力而设计。ING-VP 包含 6 款游戏，300 个关卡，每关 6 种配置，单个模型需进行 6 万多次互动。基准框架支持多种比较设置，如图像-文本与纯文本输入、单步与多步推理、有历史与无历史条件，深入剖析模型能力。我们测试了多款顶尖 MLLM，表现最佳的 Claude-3.5 Sonnet 平均准确率仅 3.37%，远低于预期。本研究旨在提供一个专业评估框架，推动 MLLM 在复杂空间推理和规划方面的进步。代码已公开，详见 https://github.com/Thisisus7/ING-VP.git。

> As multimodal large language models (MLLMs) continue to demonstrate increasingly competitive performance across a broad spectrum of tasks, more intricate and comprehensive benchmarks have been developed to assess these cutting-edge models. These benchmarks introduce new challenges to core capabilities such as perception, reasoning, and planning. However, existing multimodal benchmarks fall short in providing a focused evaluation of multi-step planning based on spatial relationships in images. To bridge this gap, we present ING-VP, the first INteractive Game-based Vision Planning benchmark, specifically designed to evaluate the spatial imagination and multi-step reasoning abilities of MLLMs. ING-VP features 6 distinct games, encompassing 300 levels, each with 6 unique configurations. A single model engages in over 60,000 rounds of interaction. The benchmark framework allows for multiple comparison settings, including image-text vs. text-only inputs, single-step vs. multi-step reasoning, and with-history vs. without-history conditions, offering valuable insights into the model's capabilities. We evaluated numerous state-of-the-art MLLMs, with the highest-performing model, Claude-3.5 Sonnet, achieving an average accuracy of only 3.37%, far below the anticipated standard. This work aims to provide a specialized evaluation framework to drive advancements in MLLMs' capacity for complex spatial reasoning and planning. The code is publicly available at https://github.com/Thisisus7/ING-VP.git.

[Arxiv](https://arxiv.org/abs/2410.06555)