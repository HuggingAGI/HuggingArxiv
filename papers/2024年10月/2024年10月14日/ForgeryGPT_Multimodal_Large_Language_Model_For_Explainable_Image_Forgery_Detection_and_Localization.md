# ForgeryGPT：一款多模态大型语言模型，专为图像伪造检测与定位提供可解释性。

发布时间：2024年10月14日

`LLM应用` `计算机视觉`

> ForgeryGPT: Multimodal Large Language Model For Explainable Image Forgery Detection and Localization

# 摘要

> 多模态大型语言模型（如 GPT4o）在视觉推理和解释生成方面表现出色，但在图像伪造检测与定位（IFDL）这一关键任务上仍面临挑战。现有方法多局限于低级语义线索，仅提供单一判断。为此，我们推出 ForgeryGPT，通过捕捉伪造图像的高阶知识相关性，结合定制的 LLM 架构，实现可解释生成与交互对话，提升 IFDL 任务。ForgeryGPT 集成 Mask-Aware Forgery Extractor，精准挖掘伪造信息，增强像素级理解。通过三阶段训练策略，结合 Mask-Text 对齐与任务特定指令调优，提升伪造检测与指令跟随能力。实验证明其有效性。

> Multimodal Large Language Models (MLLMs), such as GPT4o, have shown strong capabilities in visual reasoning and explanation generation. However, despite these strengths, they face significant challenges in the increasingly critical task of Image Forgery Detection and Localization (IFDL). Moreover, existing IFDL methods are typically limited to the learning of low-level semantic-agnostic clues and merely provide a single outcome judgment. To tackle these issues, we propose ForgeryGPT, a novel framework that advances the IFDL task by capturing high-order forensics knowledge correlations of forged images from diverse linguistic feature spaces, while enabling explainable generation and interactive dialogue through a newly customized Large Language Model (LLM) architecture. Specifically, ForgeryGPT enhances traditional LLMs by integrating the Mask-Aware Forgery Extractor, which enables the excavating of precise forgery mask information from input images and facilitating pixel-level understanding of tampering artifacts. The Mask-Aware Forgery Extractor consists of a Forgery Localization Expert (FL-Expert) and a Mask Encoder, where the FL-Expert is augmented with an Object-agnostic Forgery Prompt and a Vocabulary-enhanced Vision Encoder, allowing for effectively capturing of multi-scale fine-grained forgery details. To enhance its performance, we implement a three-stage training strategy, supported by our designed Mask-Text Alignment and IFDL Task-Specific Instruction Tuning datasets, which align vision-language modalities and improve forgery detection and instruction-following capabilities. Extensive experiments demonstrate the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2410.10238)