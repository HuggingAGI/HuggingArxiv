# Inf-MLLM：单 GPU 上的高效多模态大型语言模型流式推理

发布时间：2024年09月11日

`LLM应用` `人工智能` `自动驾驶`

> Inf-MLLM: Efficient Streaming Inference of Multimodal Large Language Models on a Single GPU

# 摘要

> 多模态大型语言模型 (MLLM) 凭借其多模态综合能力，广泛应用于 GPT-4o、自动驾驶和机器人等领域。然而，多模态输入带来的长上下文问题，导致推理时需要缓存大量 Key 和 Value 状态 (KV 缓存)，从而引发高延迟和内存消耗。这使得在边缘设备上部署 MLLM 的流式推理变得困难，限制了其在实际应用中的潜力。为此，我们提出了 Inf-MLLM，一个能够在单个 GPU 上实现无限上下文流式推理的高效框架。Inf-MLLM 基于“注意力鞍点”这一新发现的注意力模式，动态管理 KV 缓存，并引入注意力偏差以捕捉长期依赖。实验表明，Inf-MLLM 在处理长文本和多轮对话视频时表现稳定，且在推理质量和速度上均优于现有方法。

> Multimodal Large Language Models (MLLMs) are distinguished by their multimodal comprehensive ability and widely used in many real-world applications including GPT-4o, autonomous driving and robotics. Despite their impressive performance, the multimodal inputs always incur long context. The inference under long context requires caching massive Key and Value states (KV cache) of previous tokens, which introduces high latency and excessive memory consumption. Due to this reason, it is challenging to deploy streaming inference of MLLMs on edge devices, which largely constrains the power and usage of MLLMs in real-world applications. In this paper, we introduce Inf-MLLM, an efficient inference framework for MLLMs, which enable streaming inference of MLLM on a single GPU with infinite context. Inf-MLLM is based on our key observation of the attention pattern in both LLMs and MLLMs called "attention saddles". Thanks to the newly discovered attention pattern, Inf-MLLM maintains a size-constrained KV cache by dynamically caching recent tokens and relevant tokens. Furthermore, Inf-MLLM proposes attention bias, a novel approach to enable MLLMs to capture long-term dependency. We show that Inf-MLLM enables multiple LLMs and MLLMs to achieve stable performance over 4M-token long texts and multi-round conversations with 1-hour-long videos on a single GPU. In addition, Inf-MLLM exhibits superior streaming reasoning quality than existing methods such as StreamingLLM and 2x speedup than H2O.

[Arxiv](https://arxiv.org/abs/2409.09086)