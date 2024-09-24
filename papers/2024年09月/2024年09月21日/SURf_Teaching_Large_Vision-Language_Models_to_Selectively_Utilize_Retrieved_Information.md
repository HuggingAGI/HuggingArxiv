# SURf：让大型视觉-语言模型学会精明地运用检索信息

发布时间：2024年09月21日

`RAG` `计算机视觉`

> SURf: Teaching Large Vision-Language Models to Selectively Utilize Retrieved Information

# 摘要

> 大型视觉-语言模型 (LVLMs) 在计算机视觉与自然语言处理的交汇处扮演着关键角色。然而，LVLMs 的检索增强生成 (RAG) 能力尚未充分发挥。现有研究要么局限于文本模态，要么仅针对特定任务。此外，多数 LVLMs 难以精准利用检索信息，且易受无关或误导性参考的影响。为此，我们设计了一个自精炼框架 SURf，旨在教会 LVLMs 选择性利用检索信息。具体而言，当 LVLM 主干回答错误时，我们获取有助于纠正答案的正参考和无助于纠正的负参考，并以此微调 LVLM 主干。实验结果显示，SURf 显著提升了 LVLMs 利用多模态参考的能力，并增强了其对无关或误导信息的抵抗力。源代码已公开，详见 https://github.com/GasolSun36/SURf。

> Large Vision-Language Models (LVLMs) have become pivotal at the intersection of computer vision and natural language processing. However, the full potential of LVLMs Retrieval-Augmented Generation (RAG) capabilities remains underutilized. Existing works either focus solely on the text modality or are limited to specific tasks. Moreover, most LVLMs struggle to selectively utilize retrieved information and are sensitive to irrelevant or misleading references. To address these challenges, we propose a self-refinement framework designed to teach LVLMs to Selectively Utilize Retrieved Information (SURf). Specifically, when given questions that are incorrectly answered by the LVLM backbone, we obtain references that help correct the answers (positive references) and those that do not (negative references). We then fine-tune the LVLM backbone using a combination of these positive and negative references. Our experiments across three tasks and seven datasets demonstrate that our framework significantly enhances LVLMs ability to effectively utilize retrieved multimodal references and improves their robustness against irrelevant or misleading information. The source code is available at https://github.com/GasolSun36/SURf.

[Arxiv](https://arxiv.org/abs/2409.14083)