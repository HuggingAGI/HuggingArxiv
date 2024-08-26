# IAA 架构通过内部适配器，为冻结的 LLM 注入多模态能力。

发布时间：2024年08月23日

`LLM应用` `人工智能` `计算机视觉`

> IAA: Inner-Adaptor Architecture Empowers Frozen Large Language Model with Multimodal Capabilities

# 摘要

> 在多模态大型语言模型领域，传统方法通过解冻语言模型来深化视觉理解，但这种微调常削弱其自然语言处理能力。为避免此问题，我们选择冻结语言模型并创新性地设计了内部适配器架构 (IAA)，通过在大语言模型中嵌入多模态适配器，实现了与文本变换器层的直接交互，从而赋予冻结模型多模态能力。与依赖大规模数据的方法不同，IAA在小规模数据集上表现卓越。实验证明，我们的方法在视觉-语言任务中大幅领先现有技术，同时保持了NLP性能。详细代码和模型已公开于GitHub。

> In the field of multimodal large language models (MLLMs), common methods typically involve unfreezing the language model during training to foster profound visual understanding. However, the fine-tuning of such models with vision-language data often leads to a diminution of their natural language processing (NLP) capabilities. To avoid this performance degradation, a straightforward solution is to freeze the language model while developing multimodal competencies. Unfortunately, previous works have not attained satisfactory outcomes. Building on the strategy of freezing the language model, we conduct thorough structural exploration and introduce the Inner-Adaptor Architecture (IAA). Specifically, the architecture incorporates multiple multimodal adaptors at varying depths within the large language model to facilitate direct interaction with the inherently text-oriented transformer layers, thereby enabling the frozen language model to acquire multimodal capabilities. Unlike previous approaches of freezing language models that require large-scale aligned data, our proposed architecture is able to achieve superior performance on small-scale datasets. We conduct extensive experiments to improve the general multimodal capabilities and visual grounding abilities of the MLLM. Our approach remarkably outperforms previous state-of-the-art methods across various vision-language benchmarks without sacrificing performance on NLP tasks. Code and models are available at https://github.com/360CVGroup/Inner-Adaptor-Architecture.

[Arxiv](https://arxiv.org/abs/2408.12902)