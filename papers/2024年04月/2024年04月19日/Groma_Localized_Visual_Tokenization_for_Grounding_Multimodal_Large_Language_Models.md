# Groma：为多模态大型语言模型的语义锚定提供本地化的视觉标记化技术

发布时间：2024年04月19日

`分类：LLM应用` `视觉识别` `人工智能`

> Groma: Localized Visual Tokenization for Grounding Multimodal Large Language Models

# 摘要

> 我们推出了 Groma，这是一款具备精确视觉感知能力的多模态大型语言模型（MLLM）。Groma 精于细节，擅长处理如区域字幕和视觉定位等区域级任务。这一能力基于一种将图像分解为关键区域并转化为区域标记的局部视觉标记机制。通过将这些区域标记融入用户指令和模型反馈，Groma 能够流畅地识别用户指定的区域并将其文本输出与图像紧密结合。此外，为了提升 Groma 的视觉基础对话能力，我们利用先进的 GPT-4V 和视觉提示技术，精心构建了一个视觉基础指令数据集。与依赖外部模块定位的 MLLM 相比，Groma 在标准参照和定位测试中持续展现出更优异的表现，彰显了将定位功能内嵌于图像标记化的优势。项目详情可见：https://groma-mllm.github.io/。

> We introduce Groma, a Multimodal Large Language Model (MLLM) with grounded and fine-grained visual perception ability. Beyond holistic image understanding, Groma is adept at region-level tasks such as region captioning and visual grounding. Such capabilities are built upon a localized visual tokenization mechanism, where an image input is decomposed into regions of interest and subsequently encoded into region tokens. By integrating region tokens into user instructions and model responses, we seamlessly enable Groma to understand user-specified region inputs and ground its textual output to images. Besides, to enhance the grounded chat ability of Groma, we curate a visually grounded instruction dataset by leveraging the powerful GPT-4V and visual prompting techniques. Compared with MLLMs that rely on the language model or external module for localization, Groma consistently demonstrates superior performances in standard referring and grounding benchmarks, highlighting the advantages of embedding localization into image tokenization. Project page: https://groma-mllm.github.io/.

[Arxiv](https://arxiv.org/abs/2404.13013)