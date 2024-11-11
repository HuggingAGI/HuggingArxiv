# 针对大型视觉语言模型的成员推理攻击

发布时间：2024年11月05日

`LLM应用` `数据安全` `视觉语言模型`

> Membership Inference Attacks against Large Vision-Language Models

# 摘要

> 大型视觉语言模型（VLLMs）在各种应用场景中处理多模态任务时展现出了有前景的能力。然而，它们的出现也引发了重大的数据安全担忧，因为在其训练数据集中可能包含敏感信息，如私人照片和医疗记录。在 VLLMs 中检测不恰当使用的数据仍然是一个关键且未解决的问题，主要是由于缺乏标准化的数据集和合适的方法。在这项研究中，我们引入了第一个专为各种 VLLMs 定制的成员推理攻击（MIA）基准，以促进训练数据的检测。然后，我们提出了一种专门为令牌级图像检测设计的新型 MIA 管道。最后，我们提出了一个新的指标，称为 MaxRényi-K%，它基于模型输出的置信度，并且适用于文本和图像数据。我们相信，我们的工作可以加深在 VLLMs 背景下对 MIA 的理解和方法。我们的代码和数据集可在 https://github.com/LIONS-EPFL/VL-MIA 获得。

> Large vision-language models (VLLMs) exhibit promising capabilities for processing multi-modal tasks across various application scenarios. However, their emergence also raises significant data security concerns, given the potential inclusion of sensitive information, such as private photos and medical records, in their training datasets. Detecting inappropriately used data in VLLMs remains a critical and unresolved issue, mainly due to the lack of standardized datasets and suitable methodologies. In this study, we introduce the first membership inference attack (MIA) benchmark tailored for various VLLMs to facilitate training data detection. Then, we propose a novel MIA pipeline specifically designed for token-level image detection. Lastly, we present a new metric called MaxRényi-K%, which is based on the confidence of the model output and applies to both text and image data. We believe that our work can deepen the understanding and methodology of MIAs in the context of VLLMs. Our code and datasets are available at https://github.com/LIONS-EPFL/VL-MIA.

[Arxiv](https://arxiv.org/abs/2411.02902)