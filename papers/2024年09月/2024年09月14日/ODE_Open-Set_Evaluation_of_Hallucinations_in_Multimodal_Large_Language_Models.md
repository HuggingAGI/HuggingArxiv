# ODE：多模态大型语言模型幻觉的开放集评估

发布时间：2024年09月14日

`LLM理论` `人工智能` `机器学习`

> ODE: Open-Set Evaluation of Hallucinations in Multimodal Large Language Models

# 摘要

> 幻觉是 MLLM 面临的一大难题，但现有评估基准的静态性可能引发数据污染。本文提出的 ODE 是一种开集、动态的幻觉评估协议。我们利用图结构模拟现实概念间的关联，生成新颖样本，涵盖通用与特定领域。动态概念组合与多样原则确保了样本的广泛分布。实验显示，ODE 样本使 MLLM 幻觉率更高，且有效避免数据污染。此外，这些样本还可用于微调，提升 MLLM 在现有基准上的表现。

> Hallucination poses a significant challenge for multimodal large language models (MLLMs). However, existing benchmarks for evaluating hallucinations are static, which can lead to potential data contamination. This paper introduces ODE, an open-set, dynamic protocol for evaluating object existence hallucinations in MLLMs. Our framework employs graph structures to model associations between real-word concepts and generates novel samples for both general and domain-specific scenarios. The dynamic combination of concepts, along with various combination principles, ensures a broad sample distribution. Experimental results show that MLLMs exhibit higher hallucination rates with ODE-generated samples, effectively avoiding data contamination. Moreover, these samples can also be used for fine-tuning to improve MLLM performance on existing benchmarks.

[Arxiv](https://arxiv.org/abs/2409.09318)