# 先思考，再观察：通过减少视觉幻觉来提升多模态 LLM 的推理能力

发布时间：2024年11月15日

`LLM应用` `语言模型`

> Thinking Before Looking: Improving Multimodal LLM Reasoning via Mitigating Visual Hallucination

# 摘要

> 多模态大型语言模型（MLLMs）促进了视觉与语言模态的融合，成为视觉语言任务的主流范式。当下像思维链（CoT）推理这样的方法提升了大型语言模型（LLMs）的认知能力，然而它们在适配 MLLMs 时，因跨模态理解中幻觉风险升高而受阻。在本文中，我们发现当前多模态 CoT 方法中的“边看边思考”范式，即在视觉输入的同时生成推理链，无法减轻由误导性图像导致的幻觉。为应对这些局限，我们提出了视觉推理链（VIC）框架，这是一种在引入视觉输入前仅利用文本上下文构建推理链的新方法，能有效降低跨模态偏差，提升多模态推理的准确性。综合评估显示，VIC 在各类与视觉相关的任务中大幅提高了零样本性能，减少了幻觉，同时优化了 MLLMs 的推理能力。我们的代码库位于 https://github.com/Terry-Xu-666/visual_inference_chain 。

> Multimodal large language models (MLLMs) have advanced the integration of visual and linguistic modalities, establishing themselves as the dominant paradigm for visual-language tasks. Current approaches like chain of thought (CoT) reasoning have augmented the cognitive capabilities of large language models (LLMs), yet their adaptation to MLLMs is hindered by heightened risks of hallucination in cross-modality comprehension. In this paper, we find that the thinking while looking paradigm in current multimodal CoT approaches--where reasoning chains are generated alongside visual input--fails to mitigate hallucinations caused by misleading images. To address these limitations, we propose the Visual Inference Chain (VIC) framework, a novel approach that constructs reasoning chains using textual context alone before introducing visual input, effectively reducing cross-modal biases and enhancing multimodal reasoning accuracy. Comprehensive evaluations demonstrate that VIC significantly improves zero-shot performance across various vision-related tasks, mitigating hallucinations while refining the reasoning capabilities of MLLMs. Our code repository can be found at https://github.com/Terry-Xu-666/visual_inference_chain.

[Arxiv](https://arxiv.org/abs/2411.12591)