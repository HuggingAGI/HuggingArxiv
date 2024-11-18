# LLaVA-o1：让视觉语言模型循序渐进地进行推理

发布时间：2024年11月15日

`LLM应用` `视觉语言模型` `多模态推理`

> LLaVA-o1: Let Vision Language Models Reason Step-by-Step

# 摘要

> 大型语言模型在推理能力上有了显著提升，像 OpenAI 的 o1 模型就通过推理时的缩放展现了这一点。但当下的视觉语言模型（VLMs）在进行系统和结构化推理时常常力不从心，处理复杂的视觉问答任务时更是如此。在本研究中，我们推出了 LLaVA-o1 这一新型 VLM，旨在开展自主的多阶段推理。和思维链提示不同，LLaVA-o1 能独立参与总结、视觉解读、逻辑推理和结论生成等连续阶段。这种结构化方式让 LLaVA-o1 在推理密集型任务的精度上有了大幅提高。为此，我们编制了 LLaVA-o1-100k 数据集，整合了来自各类视觉问答的样本，并给出了结构化的推理标注。另外，我们还提出了一种推理时的阶段级波束搜索方法，实现了有效的推理时缩放。令人瞩目的是，仅凭借 100k 个训练样本和简单却有效的推理时缩放方法，LLaVA-o1 不仅在众多多模态推理基准测试中比其基础模型高出 8.9%，还超越了像 Gemini-1.5-pro、GPT-4o-mini 和 Llama-3.2-90B-Vision-Instruct 等更大甚至闭源的模型。

> Large language models have demonstrated substantial advancements in reasoning capabilities, particularly through inference-time scaling, as illustrated by models such as OpenAI's o1. However, current Vision-Language Models (VLMs) often struggle to perform systematic and structured reasoning, especially when handling complex visual question-answering tasks. In this work, we introduce LLaVA-o1, a novel VLM designed to conduct autonomous multistage reasoning. Unlike chain-of-thought prompting, LLaVA-o1 independently engages in sequential stages of summarization, visual interpretation, logical reasoning, and conclusion generation. This structured approach enables LLaVA-o1 to achieve marked improvements in precision on reasoning-intensive tasks. To accomplish this, we compile the LLaVA-o1-100k dataset, integrating samples from various visual question answering sources and providing structured reasoning annotations. Besides, we propose an inference-time stage-level beam search method, which enables effective inference-time scaling. Remarkably, with only 100k training samples and a simple yet effective inference time scaling method, LLaVA-o1 not only outperforms its base model by 8.9% on a wide range of multimodal reasoning benchmarks, but also surpasses the performance of larger and even closed-source models, such as Gemini-1.5-pro, GPT-4o-mini, and Llama-3.2-90B-Vision-Instruct.

[Arxiv](https://arxiv.org/abs/2411.10440)