# 思维链助力分子解析

发布时间：2024年10月07日

`LLM应用` `人工智能`

> Chain-of-Thoughts for Molecular Understanding

# 摘要

> LLM 在化学领域的应用，如从分子生成文本描述，已显示出潜力。然而，基于分子结构的推理仍具挑战，例如 GPT-4o 也难以识别关键功能基团。为此，我们提出 StructCoT，通过注入分子关键结构特征，增强 LLM 的分子理解能力。同时，我们引入两个微调框架，使现有 LLM 能使用 StructCoT。实验证明，结合 StructCoT 和微调框架，分子理解任务性能显著提升。

> The adaptation of large language models (LLMs) to chemistry has shown promising performance in molecular understanding tasks, such as generating a text description from a molecule. However, proper reasoning based on molecular structural information remains a significant challenge, e.g., even advanced LLMs such as GPT-4o struggle to identify functional groups which are crucial for inferring the molecular property of interest. To address this limitation, we propose StructCoT, a structure-aware chain-of-thought (CoT) that enhances LLMs' understanding of molecular structures by explicitly injecting the key structural features of molecules. Moreover, we introduce two fine-tuning frameworks for adapting the existing LLMs to use our StructCoT. Our experiments demonstrate that incorporating StructCoT with our fine-tuning frameworks leads to consistent improvements in both molecular understanding tasks.

[Arxiv](https://arxiv.org/abs/2410.05610)