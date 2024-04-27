# Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术

发布时间：2024年04月23日

`LLM应用` `人工智能` `多模态交互`

> Wiki-LLaVA: Hierarchical Retrieval-Augmented Generation for Multimodal LLMs

# 摘要

> 多模态大型语言模型（LLM）作为LLM的进阶形态，不仅局限于文本模态，更拓展至更广阔的应用领域。目前，研究者正致力于开发创新的架构和视觉-语言适配器。本文聚焦于赋予这些模型检索外部知识以回答问题的能力。我们提出的Wiki-LLaVA方法，通过分层检索流程整合了一个多模态文档的外部知识库。利用此方法，能够从外部知识源中检索到相关文段，为LLM提供额外的上下文信息，从而提升对话生成的有效性和精确度。我们在结合外部数据的视觉问答数据集上进行了广泛的实验，验证了我们方法的有效性。

> Multimodal LLMs are the natural evolution of LLMs, and enlarge their capabilities so as to work beyond the pure textual modality. As research is being carried out to design novel architectures and vision-and-language adapters, in this paper we concentrate on endowing such models with the capability of answering questions that require external knowledge. Our approach, termed Wiki-LLaVA, aims at integrating an external knowledge source of multimodal documents, which is accessed through a hierarchical retrieval pipeline. Relevant passages, using this approach, are retrieved from the external knowledge source and employed as additional context for the LLM, augmenting the effectiveness and precision of generated dialogues. We conduct extensive experiments on datasets tailored for visual question answering with external data and demonstrate the appropriateness of our approach.

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/x1.png)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/x2.png)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_encyclopedic_27c590f5dfe2d909.jpg)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_encyclopedic_27e011f811e7b62e.jpg)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_encyclopedic_41b81647e136ee90.jpg)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_infoseek_val_00000016.jpeg)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_infoseek_val_00000048.jpeg)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_infoseek_val_00000131.jpg)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_infoseek_val_00000210.jpg)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_encyclopedic_fa07f04eea2fdcf0.jpg)

![Wiki-LLaVA：为多模态大型语言模型（LLMs）打造的层级化检索增强生成技术](../../../paper_images/2404.15406/resized_infoseek_val_00000169.jpg)

[Arxiv](https://arxiv.org/abs/2404.15406)