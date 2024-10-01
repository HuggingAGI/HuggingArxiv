# TrojVLM：视觉语言模型的后门攻击

发布时间：2024年09月28日

`LLM应用` `计算机视觉` `网络安全`

> TrojVLM: Backdoor Attack Against Vision Language Models

# 摘要

> 视觉语言模型（VLM）的崛起，将计算机视觉与大型语言模型（LLM）完美融合，能根据视觉输入生成详尽文本，但也带来了新的安全隐患。不同于以往专注于单一模态或分类任务的研究，本研究首次探索了对复杂图像到文本生成任务中的VLM进行后门攻击，即TrojVLM。TrojVLM能在中毒图像触发下，巧妙地将预定文本嵌入输出。同时，我们创新性地提出了语义保留损失，确保原始图像的语义不受损。实验证明，TrojVLM在图像描述和视觉问答（VQA）任务中，既能保持原图语义，又能精准输出目标文本。此研究不仅揭示了VLM在图像到文本生成中的重大安全漏洞，更为未来多模态模型的安全防护研究奠定了基石。

> The emergence of Vision Language Models (VLMs) is a significant advancement in integrating computer vision with Large Language Models (LLMs) to produce detailed text descriptions based on visual inputs, yet it introduces new security vulnerabilities. Unlike prior work that centered on single modalities or classification tasks, this study introduces TrojVLM, the first exploration of backdoor attacks aimed at VLMs engaged in complex image-to-text generation. Specifically, TrojVLM inserts predetermined target text into output text when encountering poisoned images. Moreover, a novel semantic preserving loss is proposed to ensure the semantic integrity of the original image content. Our evaluation on image captioning and visual question answering (VQA) tasks confirms the effectiveness of TrojVLM in maintaining original semantic content while triggering specific target text outputs. This study not only uncovers a critical security risk in VLMs and image-to-text generation but also sets a foundation for future research on securing multimodal models against such sophisticated threats.

[Arxiv](https://arxiv.org/abs/2409.19232)