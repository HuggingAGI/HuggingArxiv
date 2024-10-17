# FiRST：通过微调路由器选择性变压器，实现输入自适应的延迟降低

发布时间：2024年10月16日

`LLM理论` `人工智能` `计算机视觉`

> FiRST: Finetuning Router-Selective Transformers for Input-Adaptive Latency Reduction

# 摘要

> 自回归大型语言模型 (LLM) 在视觉和语言处理等领域表现出色。然而，由于通过变换器层的顺序处理，自回归解码在资源受限的环境中面临显著的计算/延迟挑战。现有方法通过跳过层来改善延迟，但存在局限性：早期退出无法处理现代框架中加速所需的 KV 缓存，而输入无关的启发式方法无法捕捉层重要性的变化。为此，我们提出了 FIRST 算法，通过层特定路由器自适应选择变换器层，减少推理延迟。FIRST 兼容 KV 缓存，实现更快推理，同时保持质量。该算法模型无关，可轻松应用于任何预训练 LLM。结合 LoRA 适配器进行微调，进一步提高任务特定准确性，同时保持延迟优势。实验表明，FIRST 显著减少延迟，保持竞争力，是低资源环境中部署 LLM 的高效解决方案。

> Auto-regressive Large Language Models (LLMs) demonstrate remarkable performance across domanins such as vision and language processing. However, due to sequential processing through a stack of transformer layers, autoregressive decoding faces significant computation/latency challenges, particularly in resource constrained environments like mobile and edge devices. Existing approaches in literature that aim to improve latency via skipping layers have two distinct flavors - 1) Early exit 2) Input-agnostic heuristics where tokens exit at pre-determined layers irrespective of input sequence. Both the above strategies have limitations - the former cannot be applied to handle KV Caching necessary for speed-ups in modern framework and the latter does not capture the variation in layer importance across tasks or more generally, across input sequences. To address both limitations, we propose FIRST, an algorithm that reduces inference latency by using layer-specific routers to select a subset of transformer layers adaptively for each input sequence - the prompt (during prefill stage) decides which layers will be skipped during decoding. FIRST preserves compatibility with KV caching enabling faster inference while being quality-aware. FIRST is model-agnostic and can be easily enabled on any pre-trained LLM. We further improve performance by incorporating LoRA adapters for fine-tuning on external datasets, enhancing task-specific accuracy while maintaining latency benefits. Our approach reveals that input adaptivity is critical - indeed, different task-specific middle layers play a crucial role in evolving hidden representations depending on task. Extensive experiments show that FIRST significantly reduces latency while retaining competitive performance (as compared to baselines), making our approach an efficient solution for LLM deployment in low-resource environments.

[Arxiv](https://arxiv.org/abs/2410.12513)