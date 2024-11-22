# ContextIQ：一个基于多模态专家的情境广告视频检索系统

发布时间：2024年10月29日

`LLM应用` `视频检索`

> ContextIQ: A Multimodal Expert-Based Video Retrieval System for Contextual Advertising

# 摘要

> 情境广告会投放与用户正在浏览的内容相契合的广告。随着社交平台和流媒体服务上视频内容的迅猛增长，再加上隐私方面的考量，对情境广告的需求也与日俱增。在恰当的情境中投放合适的广告，能营造出无缝且愉悦的广告观看体验，进而提升观众的参与度，最终实现更优的广告变现。从技术层面来讲，有效的情境广告需要一个能够在极为精细的层面理解复杂视频内容的视频检索系统。当下基于联合多模态训练的文本到视频检索模型，需要海量的数据集和计算资源，这限制了其实际应用，且缺少广告生态系统整合所需的关键功能。我们推出了 ContextIQ，这是一个专为情境广告打造的基于多模态专家的视频检索系统。ContextIQ 借助特定模态的专家——视频、音频、转录（字幕）以及元数据，比如对象、动作、情感等——来构建语义丰富的视频表征。我们证明，我们的系统在未进行联合训练的情况下，在多个文本到视频检索的基准测试中，取得了不逊于甚至优于前沿模型和商业解决方案的成果。我们的消融研究凸显了借助多种模态来提升视频检索精准度的优势，而非仅仅使用视觉语言模型。此外，我们还展示了像 ContextIQ 这类视频检索系统如何在广告生态系统中用于情境广告，同时也能处理与品牌安全和过滤不当内容相关的问题。

> Contextual advertising serves ads that are aligned to the content that the user is viewing. The rapid growth of video content on social platforms and streaming services, along with privacy concerns, has increased the need for contextual advertising. Placing the right ad in the right context creates a seamless and pleasant ad viewing experience, resulting in higher audience engagement and, ultimately, better ad monetization. From a technology standpoint, effective contextual advertising requires a video retrieval system capable of understanding complex video content at a very granular level. Current text-to-video retrieval models based on joint multimodal training demand large datasets and computational resources, limiting their practicality and lacking the key functionalities required for ad ecosystem integration. We introduce ContextIQ, a multimodal expert-based video retrieval system designed specifically for contextual advertising. ContextIQ utilizes modality-specific experts-video, audio, transcript (captions), and metadata such as objects, actions, emotion, etc.-to create semantically rich video representations. We show that our system, without joint training, achieves better or comparable results to state-of-the-art models and commercial solutions on multiple text-to-video retrieval benchmarks. Our ablation studies highlight the benefits of leveraging multiple modalities for enhanced video retrieval accuracy instead of using a vision-language model alone. Furthermore, we show how video retrieval systems such as ContextIQ can be used for contextual advertising in an ad ecosystem while also addressing concerns related to brand safety and filtering inappropriate content.

[Arxiv](https://arxiv.org/abs/2410.22233)