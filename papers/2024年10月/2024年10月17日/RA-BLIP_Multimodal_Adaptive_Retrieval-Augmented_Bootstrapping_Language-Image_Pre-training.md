# RA-BLIP：多模态自适应检索增强的语言-图像预训练

发布时间：2024年10月17日

`RAG` `人工智能` `计算机视觉`

> RA-BLIP: Multimodal Adaptive Retrieval-Augmented Bootstrapping Language-Image Pre-training

# 摘要

> 多模态大型语言模型 (MLLMs) 近期备受瞩目，显示出其在视觉语言任务中的广泛应用潜力。然而，MLLMs 包含大量外部知识，更新这些知识既耗费计算资源又难以解释。为此，我们提出了多模态自适应检索增强引导语言图像预训练 (RA-BLIP)，通过与可学习查询的交互，指导视觉信息的提取，减少无关干扰。同时，引入预训练的多模态融合模块，将视觉与语言模态统一到语义空间，实现高效检索与知识整合。此外，自适应选择知识生成 (ASKG) 策略使生成器能自主辨别知识相关性，提升去噪效果。实验证明，RA-BLIP 在多模态问答任务中表现卓越，超越了现有最先进模型。

> Multimodal Large Language Models (MLLMs) have recently received substantial interest, which shows their emerging potential as general-purpose models for various vision-language tasks. MLLMs involve significant external knowledge within their parameters; however, it is challenging to continually update these models with the latest knowledge, which involves huge computational costs and poor interpretability. Retrieval augmentation techniques have proven to be effective plugins for both LLMs and MLLMs. In this study, we propose multimodal adaptive Retrieval-Augmented Bootstrapping Language-Image Pre-training (RA-BLIP), a novel retrieval-augmented framework for various MLLMs. Considering the redundant information within vision modality, we first leverage the question to instruct the extraction of visual information through interactions with one set of learnable queries, minimizing irrelevant interference during retrieval and generation. Besides, we introduce a pre-trained multimodal adaptive fusion module to achieve question text-to-multimodal retrieval and integration of multimodal knowledge by projecting visual and language modalities into a unified semantic space. Furthermore, we present an Adaptive Selection Knowledge Generation (ASKG) strategy to train the generator to autonomously discern the relevance of retrieved knowledge, which realizes excellent denoising performance. Extensive experiments on open multimodal question-answering datasets demonstrate that RA-BLIP achieves significant performance and surpasses the state-of-the-art retrieval-augmented models.

[Arxiv](https://arxiv.org/abs/2410.14154)