# TurboRAG：利用预计算的分块文本 KV 缓存，加速检索增强生成过程

发布时间：2024年10月09日

`RAG` `信息技术` `人工智能`

> TurboRAG: Accelerating Retrieval-Augmented Generation with Precomputed KV Caches for Chunked Text

# 摘要

> 现有的 RAG 系统因处理大量文档块而耗费大量计算，导致首次生成时间 (TTFT) 延迟显著。为此，我们推出了 TurboRAG，通过离线预计算和存储文档的关键值 (KV) 缓存，直接用于预填充，从而大幅减少在线计算，显著提升 TTFT 效率。我们还深入研究了掩码矩阵和位置嵌入机制，并微调了预训练模型以确保 TurboRAG 的准确性。这一创新无需修改现有模型和推理系统，适用于大多数大型语言模型及其应用。实验结果显示，TurboRAG 在 TTFT 上比传统 RAG 系统快 9.4 倍（平均 8.6 倍），且性能相当。

> Current Retrieval-Augmented Generation (RAG) systems concatenate and process numerous retrieved document chunks for prefill which requires a large volume of computation, therefore leading to significant latency in time-to-first-token (TTFT). To reduce the computation overhead as well as TTFT, we introduce TurboRAG, a novel RAG system that redesigns the inference paradigm of the current RAG system by first pre-computing and storing the key-value (KV) caches of documents offline, and then directly retrieving the saved KV cache for prefill. Hence, online computation of KV caches is eliminated during inference. In addition, we provide a number of insights into the mask matrix and positional embedding mechanisms, plus fine-tune a pretrained language model to maintain model accuracy of TurboRAG. Our approach is applicable to most existing large language models and their applications without any requirement in modification of models and inference systems. Experimental results across a suite of RAG benchmarks demonstrate that TurboRAG reduces TTFT by up to 9.4x compared to the conventional RAG systems (on an average of 8.6x), but reserving comparable performance to the standard RAG systems.

[Arxiv](https://arxiv.org/abs/2410.07590)