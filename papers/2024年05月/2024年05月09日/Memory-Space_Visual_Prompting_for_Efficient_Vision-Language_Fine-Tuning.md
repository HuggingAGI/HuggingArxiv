# 记忆空间视觉提示：高效视觉语言微调的新途径

发布时间：2024年05月09日

`LLM应用

这篇论文探讨了如何将视觉信息有效地整合到大型语言模型中，以提高处理视觉任务的效率和性能。通过提出的记忆空间视觉提示（MemVP）方法，作者展示了如何将视觉提示与语言模型的前馈网络权重结合，从而在不增加输入长度的情况下，有效地将视觉知识注入模型。这种方法在实际应用中提高了训练和推理的效率，并在性能上超越了现有方法。因此，这篇论文属于大型语言模型（LLM）的应用范畴，因为它关注的是如何将LLM应用于视觉-语言任务，并提出了具体的应用方法。` `计算机视觉`

> Memory-Space Visual Prompting for Efficient Vision-Language Fine-Tuning

# 摘要

> 当前构建大型视觉-语言模型的方法采用两步走策略：首先将视觉信息转化为语言模型的输入提示，然后通过高效微调将模型应用于特定任务。但这种方法因增加输入长度而效率受限。本文提出了一种新思路，将视觉提示视为辅助语言模型处理视觉任务的额外知识。基于语言模型前馈网络具有“键值记忆”功能的发现，我们创新性地提出了记忆空间视觉提示（MemVP）方法，将视觉提示与前馈网络权重结合，实现视觉知识的注入。实验证明，MemVP不仅大幅缩短了训练和推理时间，而且在性能上超越了现有的高效微调方法。详细代码可访问：https://github.com/JieShibo/MemVP。

> Current solutions for efficiently constructing large vision-language (VL) models follow a two-step paradigm: projecting the output of pre-trained vision encoders to the input space of pre-trained language models as visual prompts; and then transferring the models to downstream VL tasks via end-to-end parameter-efficient fine-tuning (PEFT). However, this paradigm still exhibits inefficiency since it significantly increases the input length of the language models. In this paper, in contrast to integrating visual prompts into inputs, we regard visual prompts as additional knowledge that facilitates language models in addressing tasks associated with visual information. Motivated by the finding that Feed-Forward Network (FFN) of language models acts as "key-value memory", we introduce a novel approach termed memory-space visual prompting (MemVP), wherein visual prompts are concatenated with the weights of FFN for visual knowledge injection. Experimental results across various VL tasks and language models reveal that MemVP significantly reduces the training time and inference latency of the finetuned VL models and surpasses the performance of previous PEFT methods. Code: https://github.com/JieShibo/MemVP

[Arxiv](https://arxiv.org/abs/2405.05615)