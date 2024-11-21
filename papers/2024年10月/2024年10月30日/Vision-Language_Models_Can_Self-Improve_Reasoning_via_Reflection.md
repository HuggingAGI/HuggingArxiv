# 视觉语言模型能够借助反思来自我提升推理能力。

发布时间：2024年10月30日

`LLM应用` `多模态` `语言模型`

> Vision-Language Models Can Self-Improve Reasoning via Reflection

# 摘要

> 链式思维（CoT）已证实能够增强大型语言模型（LLMs）的推理能力。然而，鉴于多模态场景的复杂性以及收集高质量 CoT 数据的难度，多模态 LLMs 中的 CoT 推理很大程度上被忽略了。为此，我们提出了一个简洁却有效的自训练框架——R3V，它通过对 CoT 原理的反思来逐步提升模型的视觉语言推理水平。我们的框架包含两个相互交织的部分：（1）为推理数据集不断引导出正面和负面的解决方案；（2）通过反思原理来从错误中学习。具体而言，我们引入了自优化和自选择损失，让模型能够通过对比原理候选来优化有缺陷的原理并得出正确答案。在众多视觉语言任务上的实验表明，R3V 持续提升了多模态 LLM 的推理能力，相较于 GPT 提炼的基线，实现了 23%至 60%的相对提升。此外，我们的方法支持对生成的解决方案进行自我反思，通过测试时的计算进一步提高性能。

> Chain-of-thought (CoT) has proven to improve the reasoning capability of large language models (LLMs). However, due to the complexity of multimodal scenarios and the difficulty in collecting high-quality CoT data, CoT reasoning in multimodal LLMs has been largely overlooked. To this end, we propose a simple yet effective self-training framework, R3V, which iteratively enhances the model's Vision-language Reasoning by Reflecting on CoT Rationales. Our framework consists of two interleaved parts: (1) iteratively bootstrapping positive and negative solutions for reasoning datasets, and (2) reflection on rationale for learning from mistakes. Specifically, we introduce the self-refine and self-select losses, enabling the model to refine flawed rationale and derive the correct answer by comparing rationale candidates. Experiments on a wide range of vision-language tasks show that R3V consistently improves multimodal LLM reasoning, achieving a relative improvement of 23 to 60 percent over GPT-distilled baselines. Additionally, our approach supports self-reflection on generated solutions, further boosting performance through test-time computation.

[Arxiv](https://arxiv.org/abs/2411.00855)