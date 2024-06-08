# 极简稀疏下的零阶微调：大型语言模型的精炼之道

发布时间：2024年06月05日

`LLM应用

理由：这篇论文主要探讨了在内存受限的设备上如何高效地微调大型语言模型（LLM），通过零阶优化（ZO）策略结合稀疏性和量化技术来实现。这种方法直接应用于LLM的优化和微调，属于LLM的具体应用场景，而非理论研究或Agent、RAG相关的研究。因此，将其归类为LLM应用是合适的。` `移动设备` `机器学习`

> Zeroth-Order Fine-Tuning of LLMs with Extreme Sparsity

# 摘要

> 零阶优化（ZO）是一种高效的内存策略，通过仅使用前向传播来微调大型语言模型（LLM）。但在内存受限的设备如手机和笔记本电脑上实施ZO微调仍面临挑战，因为全精度计算不可行。本研究通过结合稀疏性和量化技术，解决了这一难题。我们发现，预训练能识别出“敏感参数”，这些参数在下游任务中指导LLM的ZO微调。实验表明，仅微调LLM中0.1%的敏感参数，就能超越全参数微调的效果，并大幅缩短处理时间。此外，结合4位量化技术，我们成功在内存不足8GiB的GPU上对Llama2-7B模型进行了高效的ZO微调，显著降低了延迟。

> Zeroth-order optimization (ZO) is a memory-efficient strategy for fine-tuning Large Language Models using only forward passes. However, the application of ZO fine-tuning in memory-constrained settings such as mobile phones and laptops is still challenging since full precision forward passes are infeasible. In this study, we address this limitation by integrating sparsity and quantization into ZO fine-tuning of LLMs. Specifically, we investigate the feasibility of fine-tuning an extremely small subset of LLM parameters using ZO. This approach allows the majority of un-tuned parameters to be quantized to accommodate the constraint of limited device memory. Our findings reveal that the pre-training process can identify a set of "sensitive parameters" that can guide the ZO fine-tuning of LLMs on downstream tasks. Our results demonstrate that fine-tuning 0.1% sensitive parameters in the LLM with ZO can outperform the full ZO fine-tuning performance, while offering wall-clock time speedup. Additionally, we show that ZO fine-tuning targeting these 0.1% sensitive parameters, combined with 4 bit quantization, enables efficient ZO fine-tuning of an Llama2-7B model on a GPU device with less than 8 GiB of memory and notably reduced latency.

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x1.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x2.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x3.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x4.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x5.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x6.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x7.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x8.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x9.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x10.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x11.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x12.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x13.png)

![极简稀疏下的零阶微调：大型语言模型的精炼之道](../../../paper_images/2406.02913/x14.png)

[Arxiv](https://arxiv.org/abs/2406.02913)