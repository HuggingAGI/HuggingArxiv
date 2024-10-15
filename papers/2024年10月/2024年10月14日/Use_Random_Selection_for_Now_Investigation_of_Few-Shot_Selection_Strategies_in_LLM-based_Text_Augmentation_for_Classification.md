# 目前采用随机选择策略：探讨基于 LLM 的文本增强分类中少样本选择策略的影响

发布时间：2024年10月14日

`LLM应用` `机器学习`

> Use Random Selection for Now: Investigation of Few-Shot Selection Strategies in LLM-based Text Augmentation for Classification

# 摘要

> 生成式 LLM 在数据增强任务中日益普及，通过改写或新生成文本样本，用于分类器微调。现有研究多采用少样本场景，将样本嵌入提示中，以提升增强效果。然而，样本选择多为随机，缺乏对其他“有信息”策略效果的全面探讨。本研究对比了少样本学习中的样本选择策略，并评估其在 LLM 文本增强中的应用。结果显示，尽管某些“有信息”策略能提升模型性能，尤其在处理分布外数据时，但效果提升有限且不常见。除非有新突破，随机选择仍为增强实践者的优选。

> The generative large language models (LLMs) are increasingly used for data augmentation tasks, where text samples are paraphrased (or generated anew) and then used for classifier fine-tuning. Existing works on augmentation leverage the few-shot scenarios, where samples are given to LLMs as part of prompts, leading to better augmentations. Yet, the samples are mostly selected randomly and a comprehensive overview of the effects of other (more ``informed'') sample selection strategies is lacking. In this work, we compare sample selection strategies existing in few-shot learning literature and investigate their effects in LLM-based textual augmentation. We evaluate this on in-distribution and out-of-distribution classifier performance. Results indicate, that while some ``informed'' selection strategies increase the performance of models, especially for out-of-distribution data, it happens only seldom and with marginal performance increases. Unless further advances are made, a default of random sample selection remains a good option for augmentation practitioners.

[Arxiv](https://arxiv.org/abs/2410.10756)