# 将领域适应的视觉与语言模型相结合，以提升医学视觉问答的性能。

发布时间：2024年04月24日

`分类：LLM应用` `视觉问答`

> Fusion of Domain-Adapted Vision and Language Models for Medical Visual Question Answering

# 摘要

> 视觉-语言模型在通用领域表现出色，并在视觉问答等多模态应用中表现强劲。但在专业如医学领域，其效能有所下降。为此，我们设计了一款专门针对医学领域的视觉-语言模型，该模型融合了专为医学定制的大型视觉和语言模型。通过三个阶段的高效参数训练，分别采用三组生物医学及放射学领域的多模态视觉与文本数据集，本模型在SLAKE 1.0医学视觉问答数据集上达到了87.5%的整体准确率，刷新了行业标准，并在VQA-RAD医学视觉问答数据集上也取得了73.2%的高准确率，表现卓越。

> Vision-language models, while effective in general domains and showing strong performance in diverse multi-modal applications like visual question-answering (VQA), struggle to maintain the same level of effectiveness in more specialized domains, e.g., medical. We propose a medical vision-language model that integrates large vision and language models adapted for the medical domain. This model goes through three stages of parameter-efficient training using three separate biomedical and radiology multi-modal visual and text datasets. The proposed model achieves state-of-the-art performance on the SLAKE 1.0 medical VQA (MedVQA) dataset with an overall accuracy of 87.5% and demonstrates strong performance on another MedVQA dataset, VQA-RAD, achieving an overall accuracy of 73.2%.

[Arxiv](https://arxiv.org/abs/2404.16192)