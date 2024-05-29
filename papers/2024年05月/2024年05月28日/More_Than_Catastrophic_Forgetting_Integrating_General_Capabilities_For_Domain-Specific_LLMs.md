# 超越灾难性遗忘：为特定领域LLMs注入通用能力

发布时间：2024年05月28日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在特定领域微调后出现的灾难性遗忘（CF）问题，并提出了通用能力集成（GCI）的概念，旨在在单一模型中融合通用与领域知识。论文通过在法律领域的实例，设计了训练与测试任务，并构建了相应的数据集。此外，论文还创新性地引入了ALoRA，通过多头注意力机制优化信息传递，以实现在特定领域中融入通用能力。这些内容主要关注于LLM在实际应用中的问题和解决方案，因此属于LLM应用分类。` `人工智能`

> More Than Catastrophic Forgetting: Integrating General Capabilities For Domain-Specific LLMs

# 摘要

> 大型语言模型（LLMs）在特定领域微调后，通用任务表现下降，此现象称为灾难性遗忘（CF）。本文进一步提出实际应用挑战——通用能力集成（GCI），要求在单一模型中融合通用与领域知识。GCI旨在不仅保留原有通用能力，更需协调两者，提升特定领域任务性能。以法律领域为例，我们设计了实用性的训练与测试任务，并构建数据集。为在特定领域中融入通用能力，我们创新性地引入ALoRA，通过多头注意力机制优化信息传递，使模型能根据任务需求灵活切换知识与能力。实验结果验证了我们方法的重要性和有效性。

> The performance on general tasks decreases after Large Language Models (LLMs) are fine-tuned on domain-specific tasks, the phenomenon is known as Catastrophic Forgetting (CF). However, this paper presents a further challenge for real application of domain-specific LLMs beyond CF, called General Capabilities Integration (GCI), which necessitates the integration of both the general capabilities and domain knowledge within a single instance. The objective of GCI is not merely to retain previously acquired general capabilities alongside new domain knowledge, but to harmonize and utilize both sets of skills in a cohesive manner to enhance performance on domain-specific tasks. Taking legal domain as an example, we carefully design three groups of training and testing tasks without lacking practicability, and construct the corresponding datasets. To better incorporate general capabilities across domain-specific scenarios, we introduce ALoRA, which utilizes a multi-head attention module upon LoRA, facilitating direct information transfer from preceding tokens to the current one. This enhancement permits the representation to dynamically switch between domain-specific knowledge and general competencies according to the attention. Extensive experiments are conducted on the proposed tasks. The results exhibit the significance of our setting, and the effectiveness of our method.

![超越灾难性遗忘：为特定领域LLMs注入通用能力](../../../paper_images/2405.17830/x1.png)

![超越灾难性遗忘：为特定领域LLMs注入通用能力](../../../paper_images/2405.17830/x2.png)

![超越灾难性遗忘：为特定领域LLMs注入通用能力](../../../paper_images/2405.17830/x3.png)

![超越灾难性遗忘：为特定领域LLMs注入通用能力](../../../paper_images/2405.17830/x4.png)

[Arxiv](https://arxiv.org/abs/2405.17830)