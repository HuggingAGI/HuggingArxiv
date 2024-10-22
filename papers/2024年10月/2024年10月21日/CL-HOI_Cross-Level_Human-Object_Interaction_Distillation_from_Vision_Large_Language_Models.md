# CL-HOI：从视觉大语言模型中提取跨层次的人-物交互

发布时间：2024年10月21日

`LLM应用` `计算机视觉` `人工智能`

> CL-HOI: Cross-Level Human-Object Interaction Distillation from Vision Large Language Models

# 摘要

> HOI 检测在 VLM 的助力下有所突破，但常需大量手动标注。VLLM 虽能识别图像级交互，但计算繁重且不适用于实例级检测。为此，我们设计了 CL-HOI 框架，无需手动标注即可从 VLLM 的图像理解中提取实例级 HOI。方法分两步：首先，VLT 将视觉信息转化为语言形式；其次，ICN 推理空间、视觉及上下文关系。通过对比蒸馏损失，我们成功将图像级知识传递至学生模型，实现实例级 HOI 检测。实验证明，CL-HOI 在 HICO-DET 和 V-COCO 数据集上表现优异，无需手动标签即可高效检测 HOI。

> Human-object interaction (HOI) detection has seen advancements with Vision Language Models (VLMs), but these methods often depend on extensive manual annotations. Vision Large Language Models (VLLMs) can inherently recognize and reason about interactions at the image level but are computationally heavy and not designed for instance-level HOI detection. To overcome these limitations, we propose a Cross-Level HOI distillation (CL-HOI) framework, which distills instance-level HOIs from VLLMs image-level understanding without the need for manual annotations. Our approach involves two stages: context distillation, where a Visual Linguistic Translator (VLT) converts visual information into linguistic form, and interaction distillation, where an Interaction Cognition Network (ICN) reasons about spatial, visual, and context relations. We design contrastive distillation losses to transfer image-level context and interaction knowledge from the teacher to the student model, enabling instance-level HOI detection. Evaluations on HICO-DET and V-COCO datasets demonstrate that our CL-HOI surpasses existing weakly supervised methods and VLLM supervised methods, showing its efficacy in detecting HOIs without manual labels.

[Arxiv](https://arxiv.org/abs/2410.15657)