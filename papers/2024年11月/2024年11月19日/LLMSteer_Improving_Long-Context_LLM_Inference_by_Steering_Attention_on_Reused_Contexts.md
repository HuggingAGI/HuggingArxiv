# LLMSteer：借助对复用上下文注意力的引导来优化长上下文 LLM 的推理

发布时间：2024年11月19日

`LLM应用` `语言模型` `计算效率`

> LLMSteer: Improving Long-Context LLM Inference by Steering Attention on Reused Contexts

# 摘要

> 虽然大型语言模型（LLMs）在复杂任务中表现抢眼，但在较长的上下文理解和高昂的计算成本方面仍有不足。为兼顾效率与质量，我们推出了 LLMSteer，这是一个无需微调的框架，借助与查询无关的注意力引导来强化 LLMs。在热门的 LLMs 和数据集上进行测试，LLMSteer 相比基线将性能差距缩小了 65.9%，且与近期的注意力引导方法相比，运行时延迟最多降低 4.8 倍。

> As large language models (LLMs) show impressive performance on complex tasks, they still struggle with longer contextual understanding and high computational costs. To balance efficiency and quality, we introduce LLMSteer, a fine-tuning-free framework that enhances LLMs through query-independent attention steering. Tested on popular LLMs and datasets, LLMSteer narrows the performance gap with baselines by 65.9% and reduces the runtime delay by up to 4.8x compared to recent attention steering methods.

[Arxiv](https://arxiv.org/abs/2411.13009)