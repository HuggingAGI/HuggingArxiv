# 极简稀疏下的零阶微调：大型语言模型的精炼之道

发布时间：2024年06月05日

`LLM应用

理由：这篇论文主要探讨了在内存受限的设备上如何高效地微调大型语言模型（LLM），通过引入稀疏性和量化技术来优化零阶优化（ZO）微调过程。这种方法直接应用于LLM的实际微调中，以提高性能和效率，特别是在资源受限的环境下。因此，它属于LLM应用类别，因为它关注的是LLM在实际应用中的优化和改进。` `移动设备` `机器学习`

> Zeroth-Order Fine-Tuning of LLMs with Extreme Sparsity

# 摘要

> 零阶优化（ZO）是一种高效的内存策略，用于通过前向传播微调大型语言模型。但在内存受限的设备如手机和笔记本电脑上实施ZO微调仍面临挑战，因为全精度计算不可行。本研究通过引入稀疏性和量化到LLM的ZO微调中，解决了这一难题。我们发现，预训练能识别出“敏感参数”，这些参数在下游任务中指导ZO微调，仅需微调LLM中0.1%的敏感参数，即可超越全参数微调的性能，并实现实时加速。此外，结合4位量化，针对这些敏感参数的ZO微调能在内存有限的GPU设备上高效微调Llama2-7B模型，大幅降低延迟。

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