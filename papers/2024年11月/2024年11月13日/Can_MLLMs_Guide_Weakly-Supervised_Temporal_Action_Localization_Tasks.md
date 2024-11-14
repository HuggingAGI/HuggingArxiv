# 大型语言模型（MLLM）能够指导弱监督的时间动作定位任务吗？

发布时间：2024年11月13日

`LLM应用`

> Can MLLMs Guide Weakly-Supervised Temporal Action Localization Tasks?

# 摘要

> 多模态大型语言模型（MLLMs）的最新突破在深度学习社区中获得了极大的认可，其中视频基础模型（VFMs）和大型语言模型（LLMs）的融合已被证明在构建强大的视频理解系统方面发挥了重要作用，有效地克服了与预定义视觉任务相关的限制。这些复杂的 MLLMs 在理解视频方面表现出显著的能力，在各种基准测试中迅速达到前所未有的性能水平。然而，它们的运行需要大量的内存和计算资源，这突出了传统模型在视频理解任务中的持续重要性。在本文中，我们引入了一种称为 MLLM4WTAL 的新型学习范式。这种范式利用 MLLM 的潜力为传统的弱监督时间动作定位（WTAL）方法提供时间动作关键语义和完整的语义先验。MLLM4WTAL 通过利用 MLLM 指导促进 WTAL 的增强。它通过集成两个不同的模块来实现这一点：关键语义匹配（KSM）和完整语义重建（CSR）。这些模块协同工作，有效地解决了 WTAL 方法中常见的不完整和过度完整结果等普遍问题。进行了严格的实验来验证我们提出的方法在提高各种异构 WTAL 模型性能方面的有效性。

> Recent breakthroughs in Multimodal Large Language Models (MLLMs) have gained significant recognition within the deep learning community, where the fusion of the Video Foundation Models (VFMs) and Large Language Models(LLMs) has proven instrumental in constructing robust video understanding systems, effectively surmounting constraints associated with predefined visual tasks. These sophisticated MLLMs exhibit remarkable proficiency in comprehending videos, swiftly attaining unprecedented performance levels across diverse benchmarks. However, their operation demands substantial memory and computational resources, underscoring the continued importance of traditional models in video comprehension tasks. In this paper, we introduce a novel learning paradigm termed MLLM4WTAL. This paradigm harnesses the potential of MLLM to offer temporal action key semantics and complete semantic priors for conventional Weakly-supervised Temporal Action Localization (WTAL) methods. MLLM4WTAL facilitates the enhancement of WTAL by leveraging MLLM guidance. It achieves this by integrating two distinct modules: Key Semantic Matching (KSM) and Complete Semantic Reconstruction (CSR). These modules work in tandem to effectively address prevalent issues like incomplete and over-complete outcomes common in WTAL methods. Rigorous experiments are conducted to validate the efficacy of our proposed approach in augmenting the performance of various heterogeneous WTAL models.

[Arxiv](https://arxiv.org/abs/2411.08466)