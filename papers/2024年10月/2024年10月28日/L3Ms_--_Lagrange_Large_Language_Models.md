# L3Ms——拉格朗日大型语言模型

发布时间：2024年10月28日

`LLM应用` `语言模型` `优化问题`

> L3Ms -- Lagrange Large Language Models

# 摘要

> 监督微调（SFT）与大型语言模型（LLMs）的对齐是提供优质用户体验的关键环节。然而，合适对齐的概念本质上因应用而异，当下的方法往往依赖启发式选择来推动优化。在本研究中，我们把 SFT 和对齐构建为一个约束优化问题，即 LLM 在执行任务时需满足特定应用要求，且不借助启发式方法。为此，我们提出了拉格朗日大型语言模型（L3Ms），它运用对数障碍来强化约束。这种方式能够在不同应用中定制 L3Ms，同时规避启发式驱动流程。我们通过实验展示了 L3Ms 在为各类应用实现定制对齐方面的通用性和有效性。

> Supervised fine-tuning (SFT) and alignment of large language models (LLMs) are key steps in providing a good user experience. However, the concept of an appropriate alignment is inherently application-dependent, and current methods often rely on heuristic choices to drive the optimization. In this work, we formulate SFT and alignment as a constrained optimization problem, where the LLM is trained on a task while being required to meet application-specific requirements, without resorting to heuristics. To solve this, we propose Lagrange Large Language Models (L3Ms), which employ logarithmic barriers to enforce the constraints. This approach allows for the customization of L3Ms across diverse applications while avoiding heuristic-driven processes. We demonstrate experimentally the versatility and efficacy of L3Ms in achieving tailored alignments for various applications.

[Arxiv](https://arxiv.org/abs/2410.21533)