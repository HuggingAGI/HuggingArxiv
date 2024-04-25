# MMT-Bench 是一套全面的多模态基准测试工具，旨在评估大型视觉-语言模型在迈向多任务通用人工智能（AGI）进程中的性能。

发布时间：2024年04月24日

`LLM应用` `多模态学习` `基准测试`

> MMT-Bench: A Comprehensive Multimodal Benchmark for Evaluating Large Vision-Language Models Towards Multitask AGI

# 摘要

> 大型视觉-语言模型（LVLMs）在多模态应用领域取得了显著进步，如视觉对话和导航。但现行的多模态评估标准仅覆盖了有限的多模态任务，无法全面反映LVLMs的发展水平。本研究提出了MMT-Bench，这是一个全新的全面基准测试，用以评估LVLMs在一系列复杂多模态任务上的表现，这些任务需要专业知识和精细的视觉识别、定位、推理与规划能力。MMT-Bench精心挑选了31,325道多选视觉问题，涵盖车辆驾驶、导航等多模态场景，包括32个核心元任务和162个子任务。其广泛的任务覆盖范围使得MMT-Bench能够通过任务图谱来评估LVLMs，从而识别出模型在特定领域内和跨领域的性能。对包括GPT-4V、GeminiProVision和InternVL-Chat在内的30个LVLMs的评估结果显示，MMT-Bench提出了重大挑战。我们期望MMT-Bench能够激发社区开发出下一代多模态基础模型，以实现更广泛的多模态智能。

> Large Vision-Language Models (LVLMs) show significant strides in general-purpose multimodal applications such as visual dialogue and embodied navigation. However, existing multimodal evaluation benchmarks cover a limited number of multimodal tasks testing rudimentary capabilities, falling short in tracking LVLM development. In this study, we present MMT-Bench, a comprehensive benchmark designed to assess LVLMs across massive multimodal tasks requiring expert knowledge and deliberate visual recognition, localization, reasoning, and planning. MMT-Bench comprises $31,325$ meticulously curated multi-choice visual questions from various multimodal scenarios such as vehicle driving and embodied navigation, covering $32$ core meta-tasks and $162$ subtasks in multimodal understanding. Due to its extensive task coverage, MMT-Bench enables the evaluation of LVLMs using a task map, facilitating the discovery of in- and out-of-domain tasks. Evaluation results involving $30$ LVLMs such as the proprietary GPT-4V, GeminiProVision, and open-sourced InternVL-Chat, underscore the significant challenges posed by MMT-Bench. We anticipate that MMT-Bench will inspire the community to develop next-generation multimodal foundation models aimed at achieving general-purpose multimodal intelligence.

[Arxiv](https://arxiv.org/abs/2404.16006)