# SimLayerKV：简化层级 KV 缓存减少的简易框架

发布时间：2024年10月17日

`LLM理论` `软件工程` `人工智能`

> SimLayerKV: A Simple Framework for Layer-Level KV Cache Reduction

# 摘要

> 大型语言模型 (LLM) 在处理长上下文方面取得了显著进展，但这也带来了存储键值 (KV) 缓存的高内存需求，影响了推理效率。为此，我们推出了 SimLayerKV，一种通过识别并减少“懒惰”层 KV 缓存来优化内存使用的方法。SimLayerKV 无需额外训练，通用性强，仅需几行代码即可实现。实验结果显示，结合 4 位量化，SimLayerKV 在保持性能小幅下降的同时，将 KV 缓存压缩了 5 倍。详细代码请访问 https://github.com/sail-sg/SimLayerKV。

> Recent advancements in large language models (LLMs) have extended their capabilities to handle long contexts. However, increasing the number of model layers and the length of input sequences significantly escalates the memory required to store key-value (KV) cache, posing challenges for efficient inference. To mitigate this issue, we present SimLayerKV, a simple yet effective method that reduces inter-layer KV cache redundancies by selectively dropping cache in identified lazy layers. Our approach is based on the observation that certain layers in long-context LLMs exhibit "lazy" behavior, contributing less to modeling long-range dependencies compared to non-lazy layers. By analyzing attention weight patterns, we find that the behavior of these lazy layers is consistent across tokens during generation for a given input. This insight motivates our SimLayerKV, which identifies lazy layers and reduces their KV cache accordingly. SimLayerKV is training-free, generalizable, and can be implemented with only seven lines of code. We conduct extensive experiments on three representative LLMs, e.g., LLaMA2-7B, LLaMA3-8B, and Mistral-7B across 16 tasks from the LongBench benchmark. The results demonstrate that SimLayerKV achieves a KV cache compression ratio of 5$\times$ with only a 1.2% performance drop when combined with 4-bit quantization. Our code is available at https://github.com/sail-sg/SimLayerKV.

[Arxiv](https://arxiv.org/abs/2410.13846)