# 提示缓存：通过模块化注意力重用实现低延迟推理

发布时间：2023年11月07日

`LLM应用` `人工智能` `软件工程`

> Prompt Cache: Modular Attention Reuse for Low-Latency Inference

# 摘要

> 我们推出了 Prompt Cache，通过在不同提示间重用注意力状态，显著提升大型语言模型（LLM）的推理速度。许多提示包含重叠文本段，如系统消息、模板和上下文文档。我们的核心思路是，预先计算并存储这些常见文本段的注意力状态，以便在用户提示中快速重用。Prompt Cache 定义了可重用的“提示模块”，确保重用时的位置准确，并提供用户接口访问缓存状态。实验表明，Prompt Cache 大幅缩短了首次生成 token 的时间，尤其在长提示任务中，如文档问答和推荐。性能提升显著，从 GPU 推理的 8 倍到 CPU 推理的 60 倍，且不影响输出准确性，无需调整模型参数。

> 
Abstract:We present Prompt Cache, an approach for accelerating inference for large language models (LLM) by reusing attention states across different LLM prompts. Many input prompts have overlapping text segments, such as system messages, prompt templates, and documents provided for context. Our key insight is that by precomputing and storing the attention states of these frequently occurring text segments on the inference server, we can efficiently reuse them when these segments appear in user prompts. Prompt Cache employs a schema to explicitly define such reusable text segments, called prompt modules. The schema ensures positional accuracy during attention state reuse and provides users with an interface to access cached states in their prompt. Using a prototype implementation, we evaluate Prompt Cache across several LLMs. We show that Prompt Cache significantly reduce latency in time-to-first-token, especially for longer prompts such as document-based question answering and recommendations. The improvements range from 8x for GPU-based inference to 60x for CPU-based inference, all while maintaining output accuracy and without the need for model parameter modifications.
    

[Arxiv](https://arxiv.org/pdf/2311.04934)