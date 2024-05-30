# MindSemantix：借助脑语言模型，解码大脑的视觉世界

发布时间：2024年05月29日

`Agent

理由：这篇论文介绍了一种名为MindSemantix的创新框架，它利用大型语言模型（LLMs）来解读通过fMRI捕捉的大脑活动中的视觉语义内容。该框架构建了一个端到端的脑-语言模型，可以被视为一个智能代理（Agent），因为它能够理解和解释大脑活动中的信息，并生成相应的描述。此外，该论文强调了模型的自主性和对大脑活动的解释能力，这些都是Agent类研究的特点。虽然该研究涉及LLM的应用，但其核心在于开发一个能够理解和解释大脑活动的系统，这更符合Agent的定义，而不是单纯的LLM应用或理论研究。` `神经科学` `人工智能`

> MindSemantix: Deciphering Brain Visual Experiences with a Brain-Language Model

# 摘要

> 通过fMRI捕捉的大脑活动来解读人类的视觉体验，是神经科学研究中一项前沿且引人入胜的挑战。与简单预测图像相比，将大脑活动转化为有意义的描述，为视觉信息提供了更深层次的解读，增强了实际应用的灵活性。本研究中，我们推出了MindSemantix，一种创新的多模态框架，它使大型语言模型能够理解大脑活动中的视觉语义内容。MindSemantix通过整合LLMs与大脑活动分析，构建了一个端到端的脑-语言模型，探索了更理想的大脑描述生成方式。我们提出的脑文本Transformer，核心为脑Q-Former，能有效提取大脑反应中的语义信息。该模型结合预训练的大脑编码器与冻结的LLM，实现了脑-视觉-语言的精准对齐。为提升神经表示的泛化性，我们采用自监督学习在大规模跨主题fMRI数据集上预训练大脑编码器。MindSemantix不仅增强了大脑解码任务的可行性，如刺激重建，还通过与先进生成模型如稳定扩散的结合，在理解大脑视觉感知方面取得了显著进展。MindSemantix生成的描述深入反映了大脑活动中的视觉与语义信息，定量上显著超越了现有技术。我们将会公开相关代码。

> Deciphering the human visual experience through brain activities captured by fMRI represents a compelling and cutting-edge challenge in the field of neuroscience research. Compared to merely predicting the viewed image itself, decoding brain activity into meaningful captions provides a higher-level interpretation and summarization of visual information, which naturally enhances the application flexibility in real-world situations. In this work, we introduce MindSemantix, a novel multi-modal framework that enables LLMs to comprehend visually-evoked semantic content in brain activity. Our MindSemantix explores a more ideal brain captioning paradigm by weaving LLMs into brain activity analysis, crafting a seamless, end-to-end Brain-Language Model. To effectively capture semantic information from brain responses, we propose Brain-Text Transformer, utilizing a Brain Q-Former as its core architecture. It integrates a pre-trained brain encoder with a frozen LLM to achieve multi-modal alignment of brain-vision-language and establish a robust brain-language correspondence. To enhance the generalizability of neural representations, we pre-train our brain encoder on a large-scale, cross-subject fMRI dataset using self-supervised learning techniques. MindSemantix provides more feasibility to downstream brain decoding tasks such as stimulus reconstruction. Conditioned by MindSemantix captioning, our framework facilitates this process by integrating with advanced generative models like Stable Diffusion and excels in understanding brain visual perception. MindSemantix generates high-quality captions that are deeply rooted in the visual and semantic information derived from brain activity. This approach has demonstrated substantial quantitative improvements over prior art. Our code will be released.

![MindSemantix：借助脑语言模型，解码大脑的视觉世界](../../../paper_images/2405.18812/x1.png)

![MindSemantix：借助脑语言模型，解码大脑的视觉世界](../../../paper_images/2405.18812/x2.png)

![MindSemantix：借助脑语言模型，解码大脑的视觉世界](../../../paper_images/2405.18812/x3.png)

![MindSemantix：借助脑语言模型，解码大脑的视觉世界](../../../paper_images/2405.18812/x4.png)

![MindSemantix：借助脑语言模型，解码大脑的视觉世界](../../../paper_images/2405.18812/x5.png)

![MindSemantix：借助脑语言模型，解码大脑的视觉世界](../../../paper_images/2405.18812/x6.png)

[Arxiv](https://arxiv.org/abs/2405.18812)