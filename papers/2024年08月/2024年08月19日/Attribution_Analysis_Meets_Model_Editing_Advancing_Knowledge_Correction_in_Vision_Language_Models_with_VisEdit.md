# 归因分析结合模型编辑，通过 VisEdit 技术，助力视觉语言模型知识校正的进步。

发布时间：2024年08月19日

`LLM应用` `计算机视觉` `人工智能`

> Attribution Analysis Meets Model Editing: Advancing Knowledge Correction in Vision Language Models with VisEdit

# 摘要

> 模型编辑技术旨在无需昂贵再训练即可修正大型模型中的过时或错误信息。最新研究发现，提示中主体最终标记的中层表示对事实预测影响显著，并据此开发了LLM编辑技术。然而，视觉LLM（VLLM）中视觉表示如何影响预测仍鲜有研究。本研究采用贡献分配与噪声扰动法，分析视觉表示对预测的贡献，发现中后期层与提示相关的视觉表示作用显著。基于此，我们提出VisEdit，一种针对VLLM的新型模型编辑器，通过调整关键区域的中间视觉表示有效修正知识。实验表明，VisEdit在多个VLLM骨干和公开基准数据集上表现优异，超越了现有最先进LLM编辑器的改编基线。

> Model editing aims to correct outdated or erroneous knowledge in large models without costly retraining. Recent research discovered that the mid-layer representation of the subject's final token in a prompt has a strong influence on factual predictions, and developed Large Language Model (LLM) editing techniques based on this observation. However, for Vision-LLMs (VLLMs), how visual representations impact the predictions from a decoder-only language model remains largely unexplored. To the best of our knowledge, model editing for VLLMs has not been extensively studied in the literature. In this work, we employ the contribution allocation and noise perturbation methods to measure the contributions of visual representations for token predictions. Our attribution analysis shows that visual representations in mid-to-later layers that are highly relevant to the prompt contribute significantly to predictions. Based on these insights, we propose VisEdit, a novel model editor for VLLMs that effectively corrects knowledge by editing intermediate visual representations in regions important to the edit prompt. We evaluated VisEdit using multiple VLLM backbones and public VLLM editing benchmark datasets. The results show the superiority of VisEdit over the strong baselines adapted from existing state-of-the-art editors for LLMs.

[Arxiv](https://arxiv.org/abs/2408.09916)