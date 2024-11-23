# 保留预训练的表示空间：论前缀调整对大型多模态模型的有效性

发布时间：2024年10月29日

`LLM应用` `多模态` `机器交互`

> Preserving Pre-trained Representation Space: On Effectiveness of Prefix-tuning for Large Multi-modal Models

# 摘要

> 最近，我们发现大型多模态模型（LMMs）正在变革机器与世界交互的方式，为各类多模态应用创造了新的可能。为让 LMMs 适配下游任务，仅训练额外前缀标记或模块的参数高效微调（PEFT）颇受欢迎。然而，PEFT 在 LMMs 中的运作方式鲜少有人分析。本文深入探究了每种微调策略的优劣，将关注点从通常与之相关的效率问题转移开来。我们首先发现，像 LoRA 和 Adapters 这类模型参数微调方法扭曲了预训练时学习的特征表示空间，限制了预训练知识的充分运用。同时也证实，尽管前缀微调在下游任务中的表现欠佳，但在保留表示空间方面表现出色。这些发现催生了一种名为前缀微调 PEFT（PT-PEFT）的简单两步 PEFT 策略，即先进行前缀微调，再进行 PEFT（如 Adapter、LoRA），融合了两者的长处。实验结果显示，与常规 PEFT 方法相比，PT-PEFT 不仅在图像描述和视觉问答中提升了性能，还有助于保留四个预训练模型的表示空间。

> Recently, we have observed that Large Multi-modal Models (LMMs) are revolutionizing the way machines interact with the world, unlocking new possibilities across various multi-modal applications. To adapt LMMs for downstream tasks, parameter-efficient fine-tuning (PEFT) which only trains additional prefix tokens or modules, has gained popularity. Nevertheless, there has been little analysis of how PEFT works in LMMs. In this paper, we delve into the strengths and weaknesses of each tuning strategy, shifting the focus from the efficiency typically associated with these approaches. We first discover that model parameter tuning methods such as LoRA and Adapters distort the feature representation space learned during pre-training and limit the full utilization of pre-trained knowledge. We also demonstrate that prefix-tuning excels at preserving the representation space, despite its lower performance on downstream tasks. These findings suggest a simple two-step PEFT strategy called Prefix-Tuned PEFT (PT-PEFT), which successively performs prefix-tuning and then PEFT (i.e., Adapter, LoRA), combines the benefits of both. Experimental results show that PT-PEFT not only improves performance in image captioning and visual question answering compared to vanilla PEFT methods but also helps preserve the representation space of the four pre-trained models.

[Arxiv](https://arxiv.org/abs/2411.00029)