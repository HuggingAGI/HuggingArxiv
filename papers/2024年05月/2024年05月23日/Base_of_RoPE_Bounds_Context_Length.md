# RoPE基础对上下文长度设定了界限

发布时间：2024年05月23日

`LLM理论

理由：这篇论文主要探讨了旋转位置嵌入（RoPE）在大型语言模型（LLMs）中的作用及其对模型处理长上下文能力的限制。论文通过理论分析和实践验证，揭示了RoPE的一个新特性——长期衰减，并指出这限制了上下文长度的上限。这一研究深入分析了LLMs的理论基础，特别是位置嵌入的机制，因此属于LLM理论分类。` `机器学习`

> Base of RoPE Bounds Context Length

# 摘要

> 位置嵌入是大型语言模型的关键部分，其中旋转位置嵌入（RoPE）通过旋转矩阵编码位置信息，已成为众多模型的首选。RoPE不仅用于增强长上下文处理能力，还通过调整其基础参数来解决位置嵌入中的分布外问题。然而，本文揭示了一个现象：LLMs可能仅表面地增强了长上下文能力。我们重新评估了RoPE在模型中的作用，并发现了一种长期衰减的新特性，指出RoPE的基础参数实际上限制了上下文长度，存在一个绝对下限。这一发现不仅理论上有据，实践上也得到了验证，为未来长上下文模型的训练提供了新的视角。

> Position embedding is a core component of current Large Language Models (LLMs). Rotary position embedding (RoPE), a technique that encodes the position information with a rotation matrix, has been the de facto choice for position embedding in many LLMs, such as the Llama series. RoPE has been further utilized to extend long context capability, which is roughly based on adjusting the \textit{base} parameter of RoPE to mitigate out-of-distribution (OOD) problems in position embedding. However, in this paper, we find that LLMs may obtain a superficial long-context ability based on the OOD theory. We revisit the role of RoPE in LLMs and propose a novel property of long-term decay, we derive that the \textit{base of RoPE bounds context length}: there is an absolute lower bound for the base value to obtain certain context length capability. Our work reveals the relationship between context length and RoPE base both theoretically and empirically, which may shed light on future long context training.

[Arxiv](https://arxiv.org/abs/2405.14591)