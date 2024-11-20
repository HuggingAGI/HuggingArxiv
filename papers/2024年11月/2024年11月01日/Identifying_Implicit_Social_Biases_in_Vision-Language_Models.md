# 探寻视觉语言模型里的隐性社会偏见

发布时间：2024年11月01日

`LLM应用` `多模态检索` `视觉语言模型`

> Identifying Implicit Social Biases in Vision-Language Models

# 摘要

> 像 CLIP（对比语言图像预训练）这样的视觉语言模型，在众多多模态检索任务中愈发流行。然而，此前的研究表明，大型语言和深度视觉模型会习得训练集中的历史偏差，致使刻板印象延续，带来潜在的下游危害。在本项工作中，我们针对 CLIP 中存在的社会偏差展开了系统分析，重点探究图像与文本模态的相互作用。我们首先提出了一种名为 So-B-IT 的社会偏差分类法，涵盖 374 个单词，划分为十种偏差类型。若与特定人群相关联，每种类型都可能造成社会危害。运用此分类法，我们以每个单词作为提示的一部分，从面部图像数据集中审视 CLIP 检索的图像。我们发现，CLIP 常常在有害词汇与特定人群之间呈现不良关联，比如要求检索“恐怖分子”的图像时，主要检索出的是中东男性的图片。最后，我们通过展示用于训练 CLIP 模型的大型图像 - 文本数据集中也存在相同的有害刻板印象，对这类偏差的来源加以分析，比如我们所发现的偏差实例。我们的发现凸显了评估和处理视觉语言模型中偏差的重要性，也表明需要对大型预训练数据集进行具有透明度和公平意识的管理。

> Vision-language models, like CLIP (Contrastive Language Image Pretraining), are becoming increasingly popular for a wide range of multimodal retrieval tasks. However, prior work has shown that large language and deep vision models can learn historical biases contained in their training sets, leading to perpetuation of stereotypes and potential downstream harm. In this work, we conduct a systematic analysis of the social biases that are present in CLIP, with a focus on the interaction between image and text modalities. We first propose a taxonomy of social biases called So-B-IT, which contains 374 words categorized across ten types of bias. Each type can lead to societal harm if associated with a particular demographic group. Using this taxonomy, we examine images retrieved by CLIP from a facial image dataset using each word as part of a prompt. We find that CLIP frequently displays undesirable associations between harmful words and specific demographic groups, such as retrieving mostly pictures of Middle Eastern men when asked to retrieve images of a "terrorist". Finally, we conduct an analysis of the source of such biases, by showing that the same harmful stereotypes are also present in a large image-text dataset used to train CLIP models for examples of biases that we find. Our findings highlight the importance of evaluating and addressing bias in vision-language models, and suggest the need for transparency and fairness-aware curation of large pre-training datasets.

[Arxiv](https://arxiv.org/abs/2411.00997)