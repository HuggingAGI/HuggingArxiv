# 将领域适应的视觉与语言模型相结合，以提升医学视觉问答的性能。

发布时间：2024年04月24日

`分类：RAG

这篇论文摘要描述了一种针对医学领域的视觉-语言模型，它通过三个阶段的参数高效训练，使用了生物医学及放射学多模态视觉与文本数据集。这种模型的设计和训练方法属于RAG（Retrieval-Augmented Generation）的范畴，因为它结合了视觉和语言信息，并且针对特定领域进行了定制。` `视觉问答`

> Fusion of Domain-Adapted Vision and Language Models for Medical Visual Question Answering

# 摘要

> 视觉-语言模型在通用领域表现出色，并在多模态应用如视觉问答（VQA）中表现强劲。但在专业领域如医学中，其效能有所下降。为此，我们设计了一款专门针对医学领域的视觉-语言模型，该模型融合了专为医学定制的大型视觉和语言模型。通过三个阶段的参数高效训练，分别使用了三个不同的生物医学及放射学多模态视觉与文本数据集。在SLAKE 1.0医学VQA数据集上，该模型以87.5%的准确率刷新了最佳成绩，并在VQA-RAD数据集上也以73.2%的准确率展现了优异的性能。

> Vision-language models, while effective in general domains and showing strong performance in diverse multi-modal applications like visual question-answering (VQA), struggle to maintain the same level of effectiveness in more specialized domains, e.g., medical. We propose a medical vision-language model that integrates large vision and language models adapted for the medical domain. This model goes through three stages of parameter-efficient training using three separate biomedical and radiology multi-modal visual and text datasets. The proposed model achieves state-of-the-art performance on the SLAKE 1.0 medical VQA (MedVQA) dataset with an overall accuracy of 87.5% and demonstrates strong performance on another MedVQA dataset, VQA-RAD, achieving an overall accuracy of 73.2%.

[Arxiv](https://arxiv.org/abs/2404.16192)