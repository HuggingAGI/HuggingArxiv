# 自我修正远不止于优化，它是一个专为视觉与语言推理任务设计的新颖学习框架。

发布时间：2024年10月05日

`LLM应用` `人工智能` `计算机视觉`

> Self-Correction is More than Refinement: A Learning Framework for Visual and Language Reasoning Tasks

# 摘要

> 尽管视觉-语言模型 (VLM) 在视觉和语言推理任务中表现出色，但它们的响应往往存在缺陷。自我修正，即指导模型改进输出的方法，为解决这一问题提供了新思路。以往研究主要集中在大型语言模型 (LLM) 上，而 VLM 的自我修正能力，尤其是结合视觉和语言信息的能力，仍未得到充分探索。本研究深入探讨了 VLM 在推理和微调阶段的自我修正能力。我们提出了一种自我修正学习 (SCL) 方法，通过直接偏好优化 (DPO) 使 VLM 从自我生成的修正数据中学习，无需外部反馈，从而实现自我提升。具体而言，我们根据初始和修正响应的正确性，收集了偏好和非偏好样本，这些样本通过 VLM 在推理阶段的两轮自我修正获得。实验结果显示，尽管 VLM 在没有额外微调和外部反馈的情况下，难以在迭代推理中有效自我修正，但通过将自我生成的修正数据分类为偏好和非偏好样本，进行偏好微调后，VLM 能够显著提升性能并避免先前的错误。本研究强调，自我修正不仅仅是简单的改进过程，更应通过额外训练增强模型的推理能力，使其能够直接生成高质量响应，无需进一步修正。

> While Vision-Language Models (VLMs) have shown remarkable abilities in visual and language reasoning tasks, they invariably generate flawed responses. Self-correction that instructs models to refine their outputs presents a promising solution to this issue. Previous studies have mainly concentrated on Large Language Models (LLMs), while the self-correction abilities of VLMs, particularly concerning both visual and linguistic information, remain largely unexamined. This study investigates the self-correction capabilities of VLMs during both inference and fine-tuning stages. We introduce a Self-Correction Learning (SCL) approach that enables VLMs to learn from their self-generated self-correction data through Direct Preference Optimization (DPO) without relying on external feedback, facilitating self-improvement. Specifically, we collect preferred and disfavored samples based on the correctness of initial and refined responses, which are obtained by two-turn self-correction with VLMs during the inference stage. Experimental results demonstrate that although VLMs struggle to self-correct effectively during iterative inference without additional fine-tuning and external feedback, they can enhance their performance and avoid previous mistakes through preference fine-tuning when their self-generated self-correction data are categorized into preferred and disfavored samples. This study emphasizes that self-correction is not merely a refinement process; rather, it should enhance the reasoning abilities of models through additional training, enabling them to generate high-quality responses directly without further refinement.

[Arxiv](https://arxiv.org/abs/2410.04055)