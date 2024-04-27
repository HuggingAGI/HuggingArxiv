# MMT-Bench 是一套全面的多模态基准测试，专为评估大型视觉-语言模型在迈向多任务通用人工智能（AGI）进程中的表现而设计。

发布时间：2024年04月24日

`分类：LLM应用

这篇论文讨论了大型视觉-语言模型（LVLMs）在多模态应用领域的进展，并提出了一个全面的评估基准MMT-Bench，用于衡量LVLMs在一系列复杂多模态任务中的表现。这属于LLM应用的范畴，因为它涉及到如何评估和改进LLM在实际应用中的表现。` `多模态` `人工智能`

> MMT-Bench: A Comprehensive Multimodal Benchmark for Evaluating Large Vision-Language Models Towards Multitask AGI

# 摘要

> 大型视觉-语言模型（LVLMs）在多模态应用领域，如视觉对话和具身导航，取得了显著进步。但目前多模态评估标准仅覆盖了少数基础能力的测试任务，未能全面反映LVLMs的发展水平。本研究推出了MMT-Bench，这是一个全面的评估基准，用于衡量LVLMs在一系列复杂多模态任务中的表现，这些任务需要专业知识和深入的视觉识别、定位、推理及规划能力。MMT-Bench精心整合了31,325个多选视觉问题，涵盖车辆驾驶、具身导航等多样化场景，包含32个核心元任务和162个子任务。其广泛的任务覆盖使得MMT-Bench能够通过任务图来评估LVLMs，从而更容易识别模型在特定领域内外的表现。对包括GPT-4V、GeminiProVision和InternVL-Chat在内的30个LVLMs的评估结果显示，MMT-Bench提出了重大挑战。我们期望MMT-Bench能够激发社区开发出下一代多模态基础模型，以实现更广泛的多模态智能。

> Large Vision-Language Models (LVLMs) show significant strides in general-purpose multimodal applications such as visual dialogue and embodied navigation. However, existing multimodal evaluation benchmarks cover a limited number of multimodal tasks testing rudimentary capabilities, falling short in tracking LVLM development. In this study, we present MMT-Bench, a comprehensive benchmark designed to assess LVLMs across massive multimodal tasks requiring expert knowledge and deliberate visual recognition, localization, reasoning, and planning. MMT-Bench comprises $31,325$ meticulously curated multi-choice visual questions from various multimodal scenarios such as vehicle driving and embodied navigation, covering $32$ core meta-tasks and $162$ subtasks in multimodal understanding. Due to its extensive task coverage, MMT-Bench enables the evaluation of LVLMs using a task map, facilitating the discovery of in- and out-of-domain tasks. Evaluation results involving $30$ LVLMs such as the proprietary GPT-4V, GeminiProVision, and open-sourced InternVL-Chat, underscore the significant challenges posed by MMT-Bench. We anticipate that MMT-Bench will inspire the community to develop next-generation multimodal foundation models aimed at achieving general-purpose multimodal intelligence.

[Arxiv](https://arxiv.org/abs/2404.16006)