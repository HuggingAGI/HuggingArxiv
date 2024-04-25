# Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力

发布时间：2024年04月23日

`LLM应用` `视觉问答` `知识库`

> Wiki-LLaVA: Hierarchical Retrieval-Augmented Generation for Multimodal LLMs

# 摘要

> 多模态大型语言模型（LLMs）作为语言模型的自然演进，拓宽了其功能，超越了单一的文本模态。本篇论文，我们在研究新型架构和视觉-语言适配器的同时，致力于赋予这些模型以外部知识为基础回答问题的能力。我们提出的Wiki-LLaVA方法，旨在整合多模态文档的外部知识库，并通过分层检索流程进行访问。通过这种方法，我们从外部知识库中检索到的相关文段，作为额外的上下文信息，以增强LLM生成对话的有效性和准确性。我们在视觉问答任务的专门数据集上进行了广泛的实验，证明了我们方法的有效性。

> Multimodal LLMs are the natural evolution of LLMs, and enlarge their capabilities so as to work beyond the pure textual modality. As research is being carried out to design novel architectures and vision-and-language adapters, in this paper we concentrate on endowing such models with the capability of answering questions that require external knowledge. Our approach, termed Wiki-LLaVA, aims at integrating an external knowledge source of multimodal documents, which is accessed through a hierarchical retrieval pipeline. Relevant passages, using this approach, are retrieved from the external knowledge source and employed as additional context for the LLM, augmenting the effectiveness and precision of generated dialogues. We conduct extensive experiments on datasets tailored for visual question answering with external data and demonstrate the appropriateness of our approach.

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/x1.png)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/x2.png)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_encyclopedic_27c590f5dfe2d909.jpg)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_encyclopedic_27e011f811e7b62e.jpg)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_encyclopedic_41b81647e136ee90.jpg)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_infoseek_val_00000016.jpeg)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_infoseek_val_00000048.jpeg)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_infoseek_val_00000131.jpg)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_infoseek_val_00000210.jpg)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_encyclopedic_fa07f04eea2fdcf0.jpg)

![Wiki-LLaVA：为多模态大型语言模型注入分层检索增强的生成能力](../../../paper_images/2404.15406/resized_infoseek_val_00000169.jpg)

[Arxiv](https://arxiv.org/abs/2404.15406)