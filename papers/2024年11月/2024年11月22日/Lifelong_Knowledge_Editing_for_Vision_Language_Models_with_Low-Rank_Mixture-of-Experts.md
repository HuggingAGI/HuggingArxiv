# 针对具有低秩混合专家的视觉语言模型的终身知识编辑

发布时间：2024年11月22日

`LLM应用` `计算机视觉` `语言模型`

> Lifelong Knowledge Editing for Vision Language Models with Low-Rank Mixture-of-Experts

# 摘要

> 模型编辑的目的是在大型语言模型（LLMs）中纠正错误知识、更新陈旧信息并融入新数据，且无需重新训练。此任务在终身场景中颇具挑战，因为在实际应用中必须持续进行编辑。尽管部分编辑器在纯LLMs的终身编辑方面展现出强大的稳健性，但融合了额外视觉模态的视觉LLMs（VLLMs）无法直接适配现有的LLM编辑器。本文中，我们提出了LiveEdit，这是一种终身视觉语言模型编辑，旨在填补终身LLM编辑与VLLMs之间的鸿沟。我们首先训练一个编辑专家生成器，为每个编辑实例独立生成低秩专家，以纠正VLLM的相关响应。我们开发了一种硬过滤机制来运用视觉语义知识，从而在编辑后模型的推理阶段粗略排除输入查询中视觉不相关的专家。最后，为整合视觉相关专家，我们引入基于文本语义相关性的软路由机制来实现多专家融合。为进行评估，我们为终身VLLM编辑设立了一个基准。大量实验表明，LiveEdit在终身VLLM编辑场景中优势显著。进一步的实验验证了LiveEdit中每个模块设计的合理性和有效性。

> Model editing aims to correct inaccurate knowledge, update outdated information, and incorporate new data into Large Language Models (LLMs) without the need for retraining. This task poses challenges in lifelong scenarios where edits must be continuously applied for real-world applications. While some editors demonstrate strong robustness for lifelong editing in pure LLMs, Vision LLMs (VLLMs), which incorporate an additional vision modality, are not directly adaptable to existing LLM editors. In this paper, we propose LiveEdit, a LIfelong Vision language modEl Edit to bridge the gap between lifelong LLM editing and VLLMs. We begin by training an editing expert generator to independently produce low-rank experts for each editing instance, with the goal of correcting the relevant responses of the VLLM. A hard filtering mechanism is developed to utilize visual semantic knowledge, thereby coarsely eliminating visually irrelevant experts for input queries during the inference stage of the post-edited model. Finally, to integrate visually relevant experts, we introduce a soft routing mechanism based on textual semantic relevance to achieve multi-expert fusion. For evaluation, we establish a benchmark for lifelong VLLM editing. Extensive experiments demonstrate that LiveEdit offers significant advantages in lifelong VLLM editing scenarios. Further experiments validate the rationality and effectiveness of each module design in LiveEdit.

[Arxiv](https://arxiv.org/abs/2411.15432)