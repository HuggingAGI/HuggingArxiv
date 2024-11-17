# BLIP3-KALE：知识增强型大规模密集字幕

发布时间：2024年11月11日

`LLM应用` `多模态`

> BLIP3-KALE: Knowledge Augmented Large-Scale Dense Captions

# 摘要

> 我们推出了 BLIP3-KALE，这一拥有 2.18 亿个图像 - 文本对的数据集，填补了描述性合成标题与基于事实的网络规模替代文本之间的空白。KALE 借助网络规模的替代文本增强合成的密集图像标题，从而生成基于事实的图像标题。我们采用两阶段的方式，借助大型视觉语言模型和语言模型来打造知识增强型标题，然后用于训练专门的 VLM 以扩充数据集。我们在 KALE 上训练视觉语言模型，并在视觉语言任务方面展现出了进步。我们的实验显示出 KALE 在训练更强大、更博学的多模态模型方面的作用。我们在 https://huggingface.co/datasets/Salesforce/blip3-kale 发布了 KALE 数据集。

> We introduce BLIP3-KALE, a dataset of 218 million image-text pairs that bridges the gap between descriptive synthetic captions and factual web-scale alt-text. KALE augments synthetic dense image captions with web-scale alt-text to generate factually grounded image captions. Our two-stage approach leverages large vision-language models and language models to create knowledge-augmented captions, which are then used to train a specialized VLM for scaling up the dataset. We train vision-language models on KALE and demonstrate improvements on vision-language tasks. Our experiments show the utility of KALE for training more capable and knowledgeable multimodal models. We release the KALE dataset at https://huggingface.co/datasets/Salesforce/blip3-kale

[Arxiv](https://arxiv.org/abs/2411.07461)