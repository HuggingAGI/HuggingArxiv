# UniTabNet：融合视觉与语言模型，提升表格结构识别能力

发布时间：2024年09月19日

`LLM应用` `数据分析` `文档处理`

> UniTabNet: Bridging Vision and Language Models for Enhanced Table Structure Recognition

# 摘要

> 在数字时代，表格结构识别技术是处理和分析大量表格数据的关键工具。传统方法主要关注视觉层面的表格结构恢复，但往往忽视了表格中的文本语义，尤其是描述性文本单元。为此，我们提出了 UniTabNet，一种基于图像到文本模型的新型表格结构解析框架。UniTabNet 采用“分而治之”的策略，通过图像到文本模型解耦表格单元，并结合物理和逻辑解码器重建完整表格结构。我们还引入了 Vision Guider 和 Language Guider，分别提升模型对相关区域的注意力和对文本语义的理解能力。在多个知名数据集上的评估结果显示，UniTabNet 达到了新的最先进水平，充分证明了其有效性。代码将公开发布，供大家参考。

> In the digital era, table structure recognition technology is a critical tool for processing and analyzing large volumes of tabular data. Previous methods primarily focus on visual aspects of table structure recovery but often fail to effectively comprehend the textual semantics within tables, particularly for descriptive textual cells. In this paper, we introduce UniTabNet, a novel framework for table structure parsing based on the image-to-text model. UniTabNet employs a ``divide-and-conquer'' strategy, utilizing an image-to-text model to decouple table cells and integrating both physical and logical decoders to reconstruct the complete table structure. We further enhance our framework with the Vision Guider, which directs the model's focus towards pertinent areas, thereby boosting prediction accuracy. Additionally, we introduce the Language Guider to refine the model's capability to understand textual semantics in table images. Evaluated on prominent table structure datasets such as PubTabNet, PubTables1M, WTW, and iFLYTAB, UniTabNet achieves a new state-of-the-art performance, demonstrating the efficacy of our approach. The code will also be made publicly available.

[Arxiv](https://arxiv.org/abs/2409.13148)