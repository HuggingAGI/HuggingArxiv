# 利用LMM诱导的情感嵌入识别扰动图像

发布时间：2024年06月18日

`RAG

理由：这篇论文主要探讨了如何利用大型多模态模型（如CLIP）的知识来解决扰动图像检测任务。它提出了一种结合图像和文本嵌入的方法来提高检测性能。这种方法涉及到多模态数据的处理和分析，与RAG（Retrieval-Augmented Generation）模型中处理和整合多源信息的概念相似。因此，将其归类为RAG是合适的。虽然论文中使用了大型模型，但重点在于模型的应用而非理论探讨，因此不适合归类为LLM理论或LLM应用。同时，该论文并未特别强调Agent的概念，因此也不适合归类为Agent。` `图像处理` `情感分析`

> Disturbing Image Detection Using LMM-Elicited Emotion Embeddings

# 摘要

> 本文探讨了扰动图像检测任务，巧妙地利用了大型多模态模型的知识。我们提出了一种双管齐下的策略：首先提取图像的通用语义信息，其次捕捉图像引发的情感反应。通过CLIP的文本编码器，我们获取了这些语义和情感的文本嵌入。结合这些文本嵌入与对应的图像嵌入，我们的方法在扰动图像检测任务中大放异彩，不仅显著提升了分类准确率，还在增强的数据集上刷新了性能记录。

> In this paper we deal with the task of Disturbing Image Detection (DID), exploiting knowledge encoded in Large Multimodal Models (LMMs). Specifically, we propose to exploit LMM knowledge in a two-fold manner: first by extracting generic semantic descriptions, and second by extracting elicited emotions. Subsequently, we use the CLIP's text encoder in order to obtain the text embeddings of both the generic semantic descriptions and LMM-elicited emotions. Finally, we use the aforementioned text embeddings along with the corresponding CLIP's image embeddings for performing the DID task. The proposed method significantly improves the baseline classification accuracy, achieving state-of-the-art performance on the augmented Disturbing Image Detection dataset.

![利用LMM诱导的情感嵌入识别扰动图像](../../../paper_images/2406.12668/did-method3.png)

![利用LMM诱导的情感嵌入识别扰动图像](../../../paper_images/2406.12668/des_emotions0.png)

![利用LMM诱导的情感嵌入识别扰动图像](../../../paper_images/2406.12668/misclassified1.png)

[Arxiv](https://arxiv.org/abs/2406.12668)