# PEAR：位置嵌入无关的注意力重新加权技术，无需额外推理开销，即可提升检索增强生成的性能。

发布时间：2024年09月29日

`RAG` `网络搜索` `人工智能`

> PEAR: Position-Embedding-Agnostic Attention Re-weighting Enhances Retrieval-Augmented Generation with Zero Inference Overhead

# 摘要

> 结合检索生成（RAG）的大型语言模型（LLM）为网络搜索带来了新变革。然而，LLM 对上下文的感知有限，影响了其在 RAG 任务中的表现。现有提升上下文感知的方法往往效率低下，推理时产生额外的时间或内存开销，且多针对特定位置嵌入。本文提出位置嵌入无关的注意力重加权（PEAR），在零推理开销下增强 LLM 的上下文感知。具体而言，通过代理任务检测抑制上下文感知的头部，并用可学习系数重加权其输出，优化 LLM 参数以最小化任务损失。结果显示，这些系数优化至小于1，减少了对 RAG 性能的抑制。推理时，这些优化系数固定用于重加权，不受具体任务影响。PEAR 相比以往方法，不仅在内存和时间上零额外开销，且在各类 RAG 任务中表现更优，同时独立于位置嵌入算法，适用性更广。

> Large language models (LLMs) enhanced with retrieval-augmented generation (RAG) have introduced a new paradigm for web search. However, the limited context awareness of LLMs degrades their performance on RAG tasks. Existing methods to enhance context awareness are often inefficient, incurring time or memory overhead during inference, and many are tailored to specific position embeddings. In this paper, we propose Position-Embedding-Agnostic attention Re-weighting (PEAR), which enhances the context awareness of LLMs with zero inference overhead. Specifically, on a proxy task focused on context copying, we first detect heads which suppress the models' context awareness thereby diminishing RAG performance. To weaken the impact of these heads, we re-weight their outputs with learnable coefficients. The LLM (with frozen parameters) is optimized by adjusting these coefficients to minimize loss on the proxy task. As a result, the coefficients are optimized to values less than one, thereby reducing their tendency to suppress RAG performance. During inference, the optimized coefficients are fixed to re-weight these heads, regardless of the specific task at hand. Our proposed PEAR offers two major advantages over previous approaches: (1) It introduces zero additional inference overhead in terms of memory usage or inference time, while outperforming competitive baselines in accuracy and efficiency across various RAG tasks. (2) It is independent of position embedding algorithms, ensuring broader applicability.

[Arxiv](https://arxiv.org/abs/2409.19745)