# MC-CoT：一个模块化协作 CoT 框架，专为零-shot 医学-VQA 设计，集成了 LLM 和 MLLM。

发布时间：2024年10月06日

`LLM应用` `人工智能`

> MC-CoT: A Modular Collaborative CoT Framework for Zero-shot Medical-VQA with LLM and MLLM Integration

# 摘要

> 近期，多模态大型语言模型 (MLLM) 在特定医学图像数据集上的微调，虽能应对医学视觉问答 (Med-VQA) 任务，但这种任务特定微调成本高且需为每个下游任务单独建模，限制了零-shot 能力的发挥。为此，我们提出 MC-CoT，一个模块化跨模态协作的 Chain-of-Thought (CoT) 框架，通过整合大型语言模型 (LLM) 来提升 MLLM 在 Med-VQA 中的零-shot 表现。MC-CoT 融合医学知识与任务指导，LLM 提供复杂推理链，MLLM 则根据指令解读医学图像。实验显示，MC-CoT 在 SLAKE、VQA-RAD 和 PATH-VQA 等数据集上，召回率与准确性均超越独立 MLLM 及多模态 CoT 框架。这表明，在处理复杂零-shot Med-VQA 任务时，背景信息与详细指导的整合至关重要。

> In recent advancements, multimodal large language models (MLLMs) have been fine-tuned on specific medical image datasets to address medical visual question answering (Med-VQA) tasks. However, this common approach of task-specific fine-tuning is costly and necessitates separate models for each downstream task, limiting the exploration of zero-shot capabilities. In this paper, we introduce MC-CoT, a modular cross-modal collaboration Chain-of-Thought (CoT) framework designed to enhance the zero-shot performance of MLLMs in Med-VQA by leveraging large language models (LLMs). MC-CoT improves reasoning and information extraction by integrating medical knowledge and task-specific guidance, where LLM provides various complex medical reasoning chains and MLLM provides various observations of medical images based on instructions of the LLM. Our experiments on datasets such as SLAKE, VQA-RAD, and PATH-VQA show that MC-CoT surpasses standalone MLLMs and various multimodality CoT frameworks in recall rate and accuracy. These findings highlight the importance of incorporating background information and detailed guidance in addressing complex zero-shot Med-VQA tasks.

[Arxiv](https://arxiv.org/abs/2410.04521)