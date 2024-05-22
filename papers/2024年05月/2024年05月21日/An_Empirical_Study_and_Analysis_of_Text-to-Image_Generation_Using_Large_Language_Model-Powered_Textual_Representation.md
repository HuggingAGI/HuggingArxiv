# 大型语言模型驱动文本表示在文本到图像生成中的实证研究与分析

发布时间：2024年05月21日

`LLM应用

这篇论文探讨了将大型语言模型（LLMs）应用于文本到图像生成任务中，以提升对文本输入的理解能力。论文提出了一种三阶段训练流程和一个轻量级适配器，以有效地将LLMs集成到现有模型中，从而支持多语言和长上下文处理，并提高图像生成的质量。这与LLM的应用相关，特别是在改进现有的文本到图像生成技术方面。` `图像生成`

> An Empirical Study and Analysis of Text-to-Image Generation Using Large Language Model-Powered Textual Representation

# 摘要

> 文本到图像生成中，准确理解文本输入是关键。现有技术多依赖CLIP模型的文本编码器，但其仅能处理77个令牌的英文输入，且与能处理多语言、长上下文的大型语言模型（LLMs）相比，能力有限。本文探讨了使用LLMs作为文本编码器，以提升文本到图像生成中的语言理解。然而，从头训练这样的模型耗费巨大。为此，我们设计了一个三阶段训练流程，巧妙地将LLMs融入现有模型。我们提出的轻量级适配器，使得模型能快速利用LLMs的文本表示进行训练。实验证明，我们的模型不仅支持多语言和长上下文，还显著提升了图像生成质量。

> One critical prerequisite for faithful text-to-image generation is the accurate understanding of text inputs. Existing methods leverage the text encoder of the CLIP model to represent input prompts. However, the pre-trained CLIP model can merely encode English with a maximum token length of 77. Moreover, the model capacity of the text encoder from CLIP is relatively limited compared to Large Language Models (LLMs), which offer multilingual input, accommodate longer context, and achieve superior text representation. In this paper, we investigate LLMs as the text encoder to improve the language understanding in text-to-image generation. Unfortunately, training text-to-image generative model with LLMs from scratch demands significant computational resources and data. To this end, we introduce a three-stage training pipeline that effectively and efficiently integrates the existing text-to-image model with LLMs. Specifically, we propose a lightweight adapter that enables fast training of the text-to-image model using the textual representations from LLMs. Extensive experiments demonstrate that our model supports not only multilingual but also longer input context with superior image generation quality.

[Arxiv](https://arxiv.org/abs/2405.12914)