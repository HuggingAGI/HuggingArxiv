# Groma：为多模态大型语言模型提供精准视觉标记化技术

发布时间：2024年04月19日

`分类：LLM应用

这篇论文描述了一款名为 Groma 的多模态大型语言模型（MLLM），它具备精确的视觉感知能力，擅长于区域级别的任务，如区域字幕生成和视觉定位。Groma 的设计和功能表明它是一个实际应用的大型语言模型，因此将其归类为LLM应用。` `计算机视觉` `人工智能`

> Groma: Localized Visual Tokenization for Grounding Multimodal Large Language Models

# 摘要

> 我们推出了 Groma，这是一款具备精确视觉感知能力的多模态大型语言模型（MLLM）。Groma 擅长于区域级别的任务，例如区域字幕生成和视觉定位。这一能力基于一种将图像分割成感兴趣区域并编码为区域标记的局部视觉标记机制。Groma 能够流畅地理解用户指定的区域输入，并将文本输出与图像紧密结合。此外，为了提升 Groma 的视觉定位对话能力，我们利用 GPT-4V 和视觉提示技术，精心构建了一个视觉定位指令数据集。与依赖外部模块定位的 MLLM 相比，Groma 在标准参照和定位基准测试中表现更为出色，彰显了将定位功能内嵌于图像标记化中的优势。项目详情可见：https://groma-mllm.github.io/。

> We introduce Groma, a Multimodal Large Language Model (MLLM) with grounded and fine-grained visual perception ability. Beyond holistic image understanding, Groma is adept at region-level tasks such as region captioning and visual grounding. Such capabilities are built upon a localized visual tokenization mechanism, where an image input is decomposed into regions of interest and subsequently encoded into region tokens. By integrating region tokens into user instructions and model responses, we seamlessly enable Groma to understand user-specified region inputs and ground its textual output to images. Besides, to enhance the grounded chat ability of Groma, we curate a visually grounded instruction dataset by leveraging the powerful GPT-4V and visual prompting techniques. Compared with MLLMs that rely on the language model or external module for localization, Groma consistently demonstrates superior performances in standard referring and grounding benchmarks, highlighting the advantages of embedding localization into image tokenization. Project page: https://groma-mllm.github.io/.

[Arxiv](https://arxiv.org/abs/2404.13013)