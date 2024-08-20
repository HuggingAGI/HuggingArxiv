# 指令驱动下的分子图生成：融合文本与图的统一扩散模型

发布时间：2024年08月19日

`LLM应用`

> Instruction-Based Molecular Graph Generation with Unified Text-Graph Diffusion Model

# 摘要

> 计算化学领域近期的发展重点在于根据文本指令合成分子，但将图生成与文本指令结合颇具挑战性，多数现有方法依赖于预训练的大型语言模型处理分子序列。为此，我们创新性地提出了 $\textbf{UTGDiff (Unified Text-Graph Diffusion Model)}$ 框架，该框架通过语言模型实现离散图扩散，从而根据指令生成分子图。UTGDiff 的核心是一个统一的文本-图变换器，它基于预训练语言模型，经过最小程度的调整以通过注意力偏差处理图数据。实验显示，UTGDiff 在基于指令的分子生成与编辑任务中，不仅超越了基于序列的方法，而且以更少的参数在同等预训练语料库水平下取得了更佳性能。代码已公开于 https://github.com/ran1812/UTGDiff。

> Recent advancements in computational chemistry have increasingly focused on synthesizing molecules based on textual instructions. Integrating graph generation with these instructions is complex, leading most current methods to use molecular sequences with pre-trained large language models. In response to this challenge, we propose a novel framework, named $\textbf{UTGDiff (Unified Text-Graph Diffusion Model)}$, which utilizes language models for discrete graph diffusion to generate molecular graphs from instructions. UTGDiff features a unified text-graph transformer as the denoising network, derived from pre-trained language models and minimally modified to process graph data through attention bias. Our experimental results demonstrate that UTGDiff consistently outperforms sequence-based baselines in tasks involving instruction-based molecule generation and editing, achieving superior performance with fewer parameters given an equivalent level of pretraining corpus. Our code is availble at https://github.com/ran1812/UTGDiff.

[Arxiv](https://arxiv.org/abs/2408.09896)