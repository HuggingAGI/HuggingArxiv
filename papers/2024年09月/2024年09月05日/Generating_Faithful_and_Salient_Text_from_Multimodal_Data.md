# 从多模态数据中生成忠实且突出的文本

发布时间：2024年09月05日

`LLM应用` `计算机视觉`

> Generating Faithful and Salient Text from Multimodal Data

# 摘要

> 尽管大型多模态模型在多模态任务中表现出色，但在生成文本时仍可能出现幻觉，且在视觉数据中检测显著特征的能力尚不明确。为此，我们设计了一个框架，能够从包含图像和结构化数据的混合模态中生成既忠实又显著的文本。我们训练了一个小型视觉批评模型，专门用于识别图像中的幻觉和非显著特征，并生成显著特征列表。这些信息在后续编辑中用于提升生成质量。实验结果显示，我们的框架在提高生成文本的忠实度和显著性方面表现优异，超越了现有减少幻觉的技术。

> While large multimodal models (LMMs) have obtained strong performance on many multimodal tasks, they may still hallucinate while generating text. Their performance on detecting salient features from visual data is also unclear. In this paper, we develop a framework to generate faithful and salient text from mixed-modal data, which includes images and structured data ( represented in knowledge graphs or tables). Specifically, we train a small vision critic model to identify hallucinated and non-salient features from the image modality. The critic model also generates a list of salient image features. This information is used in the post editing step to improve the generation quality. Experiments on two datasets show that our framework improves LMMs' generation quality on both faithfulness and saliency, outperforming recent techniques aimed at reducing hallucination.

[Arxiv](https://arxiv.org/abs/2409.03961)