# LLaVA-Ultra：专为超声波设计的大型中文语言与视觉助手

发布时间：2024年10月19日

`LLM应用` `人工智能`

> LLaVA-Ultra: Large Chinese Language and Vision Assistant for Ultrasound

# 摘要

> 多模态大型语言模型 (MLLM) 近期备受瞩目，成为研究热点。借助强大的 LLM，它推动了对话生成 AI 从单一文本向多模态任务的转变，这一趋势正显著影响医疗领域。然而，通用视觉语言模型 (VLM) 在医疗视觉问答 (Med-VQA) 方面表现不佳，即使是专为医疗设计的模型，答案也常模糊且视觉相关性弱。为此，我们提出了一种细粒度自适应 VLM 架构，通过参数高效调优，提升中文医疗视觉对话的性能。我们设计了融合模块，结合细粒度视觉编码器，增强医疗视觉语义的细微差别。同时，针对医疗场景中的数据冗余问题，我们采用知识蒸馏的加权评分，自适应筛选有效图像。实验中，我们使用了大规模多模态中文超声数据集，并基于专业医生的文本创建指令跟随数据，确保调优效果。最终，我们的中文语言与视觉助手 (LLaVA-Ultra) 在医疗场景中表现出色，在三个 Med-VQA 数据集上，各项指标均超越了现有最先进模型。

> Multimodal Large Language Model (MLLM) has recently garnered attention as a prominent research focus. By harnessing powerful LLM, it facilitates a transition of conversational generative AI from unimodal text to performing multimodal tasks. This boom begins to significantly impact medical field. However, general visual language model (VLM) lacks sophisticated comprehension for medical visual question answering (Med-VQA). Even models specifically tailored for medical domain tend to produce vague answers with weak visual relevance. In this paper, we propose a fine-grained adaptive VLM architecture for Chinese medical visual conversations through parameter-efficient tuning. Specifically, we devise a fusion module with fine-grained vision encoders to achieve enhancement for subtle medical visual semantics. Then we note data redundancy common to medical scenes is ignored in most prior works. In cases of a single text paired with multiple figures, we utilize weighted scoring with knowledge distillation to adaptively screen valid images mirroring text descriptions. For execution, we leverage a large-scale multimodal Chinese ultrasound dataset obtained from the hospital. We create instruction-following data based on text from professional doctors, which ensures effective tuning. With enhanced model and quality data, our Large Chinese Language and Vision Assistant for Ultrasound (LLaVA-Ultra) shows strong capability and robustness to medical scenarios. On three Med-VQA datasets, LLaVA-Ultra surpasses previous state-of-the-art models on various metrics.

[Arxiv](https://arxiv.org/abs/2410.15074)