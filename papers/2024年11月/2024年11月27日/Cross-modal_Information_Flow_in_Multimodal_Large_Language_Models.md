# 多模态大型语言模型里的跨模态信息流

发布时间：2024年11月27日

`LLM应用` `视觉语言` `多模态`

> Cross-modal Information Flow in Multimodal Large Language Models

# 摘要

> 近期，自回归多模态大型语言模型（MLLMs）的发展在视觉语言任务上取得了可喜的进展。尽管有众多研究探索大型语言模型中的语言信息处理，然而目前对于 MLLMs 的内部运作机制以及语言和视觉信息在其中的相互作用却知之甚少。本研究旨在通过考察 MLLMs 中不同模态（语言和视觉）之间的信息流来填补这一空缺，重点聚焦于视觉问答。具体而言，给定一个图像 - 问题对作为输入，我们探究在模型中的何处以及视觉和语言信息如何结合从而生成最终的预测。对 LLaVA 系列的一系列模型进行实验后，我们发现这两种模态的融合过程存在两个不同阶段。在较低层，模型先将整个图像的更通用视觉特征转移到（语言）问题标记的表征中。在中间层，它再次将与问题相关的特定对象的视觉信息转移至问题的相应标记位置。最后，在较高层，所得的多模态表征被传播至输入序列的最后位置以进行最终预测。总之，我们的发现为 MLLMs 中图像和语言处理的空间与功能方面提供了全新且全面的视角，有助于未来对多模态信息定位和编辑的研究。

> The recent advancements in auto-regressive multimodal large language models (MLLMs) have demonstrated promising progress for vision-language tasks. While there exists a variety of studies investigating the processing of linguistic information within large language models, little is currently known about the inner working mechanism of MLLMs and how linguistic and visual information interact within these models. In this study, we aim to fill this gap by examining the information flow between different modalities -- language and vision -- in MLLMs, focusing on visual question answering. Specifically, given an image-question pair as input, we investigate where in the model and how the visual and linguistic information are combined to generate the final prediction. Conducting experiments with a series of models from the LLaVA series, we find that there are two distinct stages in the process of integration of the two modalities. In the lower layers, the model first transfers the more general visual features of the whole image into the representations of (linguistic) question tokens. In the middle layers, it once again transfers visual information about specific objects relevant to the question to the respective token positions of the question. Finally, in the higher layers, the resulting multimodal representation is propagated to the last position of the input sequence for the final prediction. Overall, our findings provide a new and comprehensive perspective on the spatial and functional aspects of image and language processing in the MLLMs, thereby facilitating future research into multimodal information localization and editing.

[Arxiv](https://arxiv.org/abs/2411.18620)