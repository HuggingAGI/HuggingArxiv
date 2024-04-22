# Groma：为多模态大型语言模型提供精准定位的视觉标记化技术

发布时间：2024年04月19日

`分类：LLM应用

这篇论文的摘要描述了一个名为 Groma 的多模态大型语言模型（MLLM），它具备精细的视觉感知能力，并在区域级任务上表现出色。Groma 的设计和功能强调了其在视觉和文本理解方面的应用，这符合“LLM应用”这一分类。此外，论文还提到了使用 GPT-4V 和视觉提示技术来提升模型的性能，这进一步表明了该研究在实际应用中的探索。` `视觉感知` `多模态交互`

> Groma: Localized Visual Tokenization for Grounding Multimodal Large Language Models

# 摘要

> 我们推出了 Groma，这是一款具备精细视觉感知能力的多模态大型语言模型（MLLM）。Groma 精于区域级任务，例如区域字幕生成和视觉定位，超越了对图像的整体理解。这一能力源自其局部视觉标记化机制，该机制将图像分解为关键区域并转换为区域标记。Groma 能够流畅地理解和响应用户指定的区域输入，并将文本输出与图像紧密结合。为了提升 Groma 的视觉基础对话能力，我们利用先进的 GPT-4V 和视觉提示技术，创建了一个视觉基础指令数据集。与依赖外部模块定位的 MLLM 相比，Groma 在标准参照和定位测试中持续展现出更优的表现，彰显了将定位功能内嵌于图像标记化中的优势。项目详情见：https://groma-mllm.github.io/。

> We introduce Groma, a Multimodal Large Language Model (MLLM) with grounded and fine-grained visual perception ability. Beyond holistic image understanding, Groma is adept at region-level tasks such as region captioning and visual grounding. Such capabilities are built upon a localized visual tokenization mechanism, where an image input is decomposed into regions of interest and subsequently encoded into region tokens. By integrating region tokens into user instructions and model responses, we seamlessly enable Groma to understand user-specified region inputs and ground its textual output to images. Besides, to enhance the grounded chat ability of Groma, we curate a visually grounded instruction dataset by leveraging the powerful GPT-4V and visual prompting techniques. Compared with MLLMs that rely on the language model or external module for localization, Groma consistently demonstrates superior performances in standard referring and grounding benchmarks, highlighting the advantages of embedding localization into image tokenization. Project page: https://groma-mllm.github.io/.

[Arxiv](https://arxiv.org/abs/2404.13013)