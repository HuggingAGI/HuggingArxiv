# 实证分析大型视觉-语言模型在视觉提示注入下的目标劫持问题

发布时间：2024年08月07日

`LLM应用` `网络安全` `人工智能`

> Empirical Analysis of Large Vision-Language Models against Goal Hijacking via Visual Prompt Injection

# 摘要

> 我们研究了视觉提示注入（VPI），这种技术恶意利用了大型视觉-语言模型（LVLMs）遵循图像上指令的能力。我们提出了一种新型VPI方法——“视觉提示注入的目标劫持”（GHVPI），它能将LVLMs的任务从原任务切换至攻击者指定的任务。数据显示，GPT-4V易受GHVPI影响，攻击成功率达15.8%，凸显了其安全风险。此外，成功实施GHVPI要求LVLMs具备高水平的字符识别与指令遵循能力。

> We explore visual prompt injection (VPI) that maliciously exploits the ability of large vision-language models (LVLMs) to follow instructions drawn onto the input image. We propose a new VPI method, "goal hijacking via visual prompt injection" (GHVPI), that swaps the execution task of LVLMs from an original task to an alternative task designated by an attacker. The quantitative analysis indicates that GPT-4V is vulnerable to the GHVPI and demonstrates a notable attack success rate of 15.8%, which is an unignorable security risk. Our analysis also shows that successful GHVPI requires high character recognition capability and instruction-following ability in LVLMs.

![实证分析大型视觉-语言模型在视觉提示注入下的目标劫持问题](../../../paper_images/2408.03554/x1.png)

![实证分析大型视觉-语言模型在视觉提示注入下的目标劫持问题](../../../paper_images/2408.03554/x2.png)

![实证分析大型视觉-语言模型在视觉提示注入下的目标劫持问题](../../../paper_images/2408.03554/x3.png)

![实证分析大型视觉-语言模型在视觉提示注入下的目标劫持问题](../../../paper_images/2408.03554/x4.png)

![实证分析大型视觉-语言模型在视觉提示注入下的目标劫持问题](../../../paper_images/2408.03554/x5.png)

![实证分析大型视觉-语言模型在视觉提示注入下的目标劫持问题](../../../paper_images/2408.03554/x6.png)

[Arxiv](https://arxiv.org/abs/2408.03554)