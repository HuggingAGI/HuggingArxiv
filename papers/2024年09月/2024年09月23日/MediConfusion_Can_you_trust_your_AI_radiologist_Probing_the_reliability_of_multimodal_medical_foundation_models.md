# MediConfusion：你敢信你的 AI 放射科医生吗？深入探讨多模态医学基础模型的可靠性。

发布时间：2024年09月23日

`LLM应用` `人工智能`

> MediConfusion: Can you trust your AI radiologist? Probing the reliability of multimodal medical foundation models

# 摘要

> 多模态大型语言模型 (MLLM) 通过自动化解决方案或辅助医疗专业人员，有望大幅提升医疗保健的准确性、可用性和成本效益。尽管近年来在开发医疗 MLLM 方面取得了初步进展，但其性能和局限性仍未被充分理解。最近提出的许多基准数据集试图测试这些模型在多个医疗领域的通用知识，但这些模型的系统性失败模式和脆弱性仍未得到充分探索。本文中，我们推出了 MediConfusion，一个挑战性的医疗视觉问答 (VQA) 基准数据集，从视觉角度揭示了医疗 MLLM 的失败模式。研究发现，最先进的模型在处理视觉上不相似但对医疗专家来说明显不同的图像对时，表现不佳。所有可用模型在 MediConfusion 上的表现均低于随机猜测，这引发了人们对现有医疗 MLLM 可靠性的严重担忧。此外，我们还总结了模型失败的常见模式，为设计更可靠的医疗 MLLM 提供了参考。

> Multimodal Large Language Models (MLLMs) have tremendous potential to improve the accuracy, availability, and cost-effectiveness of healthcare by providing automated solutions or serving as aids to medical professionals. Despite promising first steps in developing medical MLLMs in the past few years, their capabilities and limitations are not well-understood. Recently, many benchmark datasets have been proposed that test the general medical knowledge of such models across a variety of medical areas. However, the systematic failure modes and vulnerabilities of such models are severely underexplored with most medical benchmarks failing to expose the shortcomings of existing models in this safety-critical domain. In this paper, we introduce MediConfusion, a challenging medical Visual Question Answering (VQA) benchmark dataset, that probes the failure modes of medical MLLMs from a vision perspective. We reveal that state-of-the-art models are easily confused by image pairs that are otherwise visually dissimilar and clearly distinct for medical experts. Strikingly, all available models (open-source or proprietary) achieve performance below random guessing on MediConfusion, raising serious concerns about the reliability of existing medical MLLMs for healthcare deployment. We also extract common patterns of model failure that may help the design of a new generation of more trustworthy and reliable MLLMs in healthcare.

[Arxiv](https://arxiv.org/abs/2409.15477)