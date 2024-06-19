# PDSS：大型语言模型逐步蒸馏的隐私保护框架

发布时间：2024年06月18日

`Agent

理由：这篇论文介绍了一种名为PDSS的框架，该框架设计用于在实际应用场景中处理特定领域任务时保护隐私和应对资源限制。PDSS框架通过服务器-客户端架构运作，利用大型语言模型（LLMs）生成推理依据，并用于优化小型语言模型（SLM）的训练。这种框架可以被视为一个智能代理（Agent），因为它能够根据接收到的扰动提示进行决策和行动，以保护隐私并优化模型性能。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论。` `隐私保护`

> PDSS: A Privacy-Preserving Framework for Step-by-Step Distillation of Large Language Models

# 摘要

> 在实际应用场景中，利用大型语言模型（LLMs）处理特定领域任务时，常遭遇领域知识隐私和资源限制的双重挑战。为此，我们设计了PDSS框架，一种逐步蒸馏LLMs的隐私保护方案。PDSS基于服务器-客户端架构运作，客户端向服务器的LLM发送经过扰动的提示，以生成推理依据。这些推理依据由客户端解码，并用于在多任务学习框架下优化特定任务的小型语言模型（SLM）的训练。PDSS巧妙融合了指数机制与编码器-解码器两种隐私保护策略，确保了提示隐私与推理依据效用的平衡。实验结果显示，PDSS在各类文本生成任务中表现出色，不仅提升了特定任务SLM的性能，更在数据隐私保护上做出了优先考虑。

> In the context of real-world applications, leveraging large language models (LLMs) for domain-specific tasks often faces two major challenges: domain-specific knowledge privacy and constrained resources. To address these issues, we propose PDSS, a privacy-preserving framework for step-by-step distillation of LLMs. PDSS works on a server-client architecture, wherein client transmits perturbed prompts to the server's LLM for rationale generation. The generated rationales are then decoded by the client and used to enrich the training of task-specific small language model(SLM) within a multi-task learning paradigm. PDSS introduces two privacy protection strategies: the Exponential Mechanism Strategy and the Encoder-Decoder Strategy, balancing prompt privacy and rationale usability. Experiments demonstrate the effectiveness of PDSS in various text generation tasks, enabling the training of task-specific SLM with enhanced performance while prioritizing data privacy protection.

![PDSS：大型语言模型逐步蒸馏的隐私保护框架](../../../paper_images/2406.12403/pdss_framework_1.png)

![PDSS：大型语言模型逐步蒸馏的隐私保护框架](../../../paper_images/2406.12403/example.png)

![PDSS：大型语言模型逐步蒸馏的隐私保护框架](../../../paper_images/2406.12403/encoder.png)

![PDSS：大型语言模型逐步蒸馏的隐私保护框架](../../../paper_images/2406.12403/decoder.png)

![PDSS：大型语言模型逐步蒸馏的隐私保护框架](../../../paper_images/2406.12403/task.png)

![PDSS：大型语言模型逐步蒸馏的隐私保护框架](../../../paper_images/2406.12403/p-d-rationale.png)

[Arxiv](https://arxiv.org/abs/2406.12403)