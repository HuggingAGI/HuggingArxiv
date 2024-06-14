# Delta-CoMe：大型语言模型中的混合精度增量压缩技术，无需额外训练。

发布时间：2024年06月13日

`LLM应用

这篇论文主要探讨了微调大型语言模型（LLMs）以适应特定任务的技术，特别是在多租户服务等复杂需求下的应用。论文提出了一种新的混合精度增量量化策略，用于优化微调后的LLM的性能，并通过实验验证了其在多种任务和不同LLM模型上的有效性。因此，这篇论文的内容更偏向于LLM的实际应用，而不是理论研究或Agent、RAG相关的研究。` `人工智能` `云计算`

> Delta-CoMe: Training-Free Delta-Compression with Mixed-Precision for Large Language Models

# 摘要

> 微调对于将大型语言模型（LLMs）应用于多样化的场景至关重要。在多租户服务等复杂需求下，部署多个LLMs成为必要。近期研究提出将微调后的LLM分解为基础模型与增量权重，并采用低秩或低比特技术压缩以节约成本。然而，我们发现这些压缩技术对特定任务（如WizardMath解决数学问题）的LLMs性能影响显著。基于增量权重中奇异值的长尾分布，我们提出了一种混合精度增量量化策略，对较大奇异值对应的奇异向量采用更高比特表示。我们在数学、代码、聊天等多种LLMs上验证了这一方法，结果显示其性能与完全微调的LLMs相当，且显著优于传统低秩和低比特方法。此外，我们的方法与Llama-2、Llama-3和Mistral等多种LLMs兼容，展现了其广泛的适用性。

> Fine-tuning is a crucial process for adapting large language models (LLMs) to diverse applications. In certain scenarios, such as multi-tenant serving, deploying multiple LLMs becomes necessary to meet complex demands. Recent studies suggest decomposing a fine-tuned LLM into a base model and corresponding delta weights, which are then compressed using low-rank or low-bit approaches to reduce costs. In this work, we observe that existing low-rank and low-bit compression methods can significantly harm the model performance for task-specific fine-tuned LLMs (e.g., WizardMath for math problems). Motivated by the long-tail distribution of singular values in the delta weights, we propose a delta quantization approach using mixed-precision. This method employs higher-bit representation for singular vectors corresponding to larger singular values. We evaluate our approach on various fine-tuned LLMs, including math LLMs, code LLMs, chat LLMs, and even VLMs. Experimental results demonstrate that our approach performs comparably to full fine-tuned LLMs, surpassing both low-rank and low-bit baselines by a considerable margin. Additionally, we show that our method is compatible with various backbone LLMs, such as Llama-2, Llama-3, and Mistral, highlighting its generalizability.

![Delta-CoMe：大型语言模型中的混合精度增量压缩技术，无需额外训练。](../../../paper_images/2406.08903/x1.png)

![Delta-CoMe：大型语言模型中的混合精度增量压缩技术，无需额外训练。](../../../paper_images/2406.08903/x2.png)

![Delta-CoMe：大型语言模型中的混合精度增量压缩技术，无需额外训练。](../../../paper_images/2406.08903/x3.png)

[Arxiv](https://arxiv.org/abs/2406.08903)