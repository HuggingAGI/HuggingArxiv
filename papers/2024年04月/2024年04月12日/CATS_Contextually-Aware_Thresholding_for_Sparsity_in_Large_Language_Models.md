# CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略

发布时间：2024年04月12日

`LLM理论` `人工智能` `计算效率`

> CATS: Contextually-Aware Thresholding for Sparsity in Large Language Models

# 摘要

> 大型语言模型（LLMs）为人工智能应用带来了飞跃，但其高昂的推理成本令其应用部署步履维艰。最新研究通过提升激活的稀疏度来减轻LLMs的计算负担，却也导致了在下游任务上的性能大幅下滑。本研究提出了一种新颖的框架——上下文感知阈值稀疏化（CATS），旨在为LLMs的激活进行稀疏化处理，同时降低推理成本。CATS框架简洁易用，效果显著。其核心是一种创新的非线性激活函数。我们发现，CATS可广泛适用于包括Mistral-7B和Llama2-7B在内的多种基础模型，并在下游任务性能上超越了现有的稀疏化方法。具体来说，基于CATS的模型在无需任何微调的情况下，其下游任务性能通常能达到基础模型的98%-100%，即便在激活稀疏度达到50%的情况下亦然。此外，当进行微调时，CATS模型相较于其他技术能更快收敛，并展现出更佳的任务性能。我们还开发了一款定制的GPU内核，用以高效执行CATS，将激活稀疏性的优势转化为实实在在的墙钟时间加速。这款定制的CATS内核在Llama-7B和Mistral-7B的令牌生成墙钟推理延迟上实现了约15%的提升。

> Large Language Models (LLMs) have dramatically advanced AI applications, yet their deployment remains challenging due to their immense inference costs. Recent studies ameliorate the computational costs of LLMs by increasing their activation sparsity but suffer from significant performance degradation on downstream tasks. In this work, we introduce a new framework for sparsifying the activations of base LLMs and reducing inference costs, dubbed Contextually Aware Thresholding for Sparsity (CATS). CATS is relatively simple, easy to implement, and highly effective. At the heart of our framework is a new non-linear activation function. We demonstrate that CATS can be applied to various base models, including Mistral-7B and Llama2-7B, and outperforms existing sparsification techniques in downstream task performance. More precisely, CATS-based models often achieve downstream task performance within 1-2% of their base models without any fine-tuning and even at activation sparsity levels of 50%. Furthermore, CATS-based models converge faster and display better task performance than competing techniques when fine-tuning is applied. Finally, we develop a custom GPU kernel for efficient implementation of CATS that translates the activation of sparsity of CATS to real wall-clock time speedups. Our custom kernel implementation of CATS results in a ~15% improvement in wall-clock inference latency of token generation on both Llama-7B and Mistral-7B.

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x1.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x2.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x3.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x4.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x5.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x6.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/mistral_training_steps_vs_zero_shot_accuracy.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/llama_training_steps_vs_zero_shot_accuracy.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x7.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x8.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x9.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x10.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/sparsity_per_layer_mistral.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/sparsity_per_layer_llama.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x11.png)

![CATS：针对大型语言模型的稀疏性，采用情境感知的阈值策略](../../../paper_images/2404.08763/x12.png)

[Arxiv](https://arxiv.org/abs/2404.08763)