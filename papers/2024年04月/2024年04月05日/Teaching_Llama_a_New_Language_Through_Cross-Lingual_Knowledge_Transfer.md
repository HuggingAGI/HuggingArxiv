# 借助跨语言知识迁移，教会 Llama 掌握新的语言技能。

发布时间：2024年04月05日

`LLM应用` `语言处理` `跨语言模型`

> Teaching Llama a New Language Through Cross-Lingual Knowledge Transfer

# 摘要

> 本文研究了如何高效地将预训练的大型语言模型（LLMs）适配到资源较少的语言，特别是爱沙尼亚语。通过运用 Llama 2 模型，我们深入探讨了结合跨语言指导调整与单语言预训练的协同效应。研究结果显示，即使是较小规模的单语言预训练，辅以跨语言指导调整，也能显著提升爱沙尼亚语处理的效果。更进一步，我们实现了从英语到爱沙尼亚语的跨语言知识迁移，使得常识推理和多轮对话能力得到增强。我们推出的最佳模型 \textsc{Llammas}，成为首个开源的爱沙尼亚语指令遵循型LLM。同时，我们还发布了首个爱沙尼亚语通用任务指令数据集 Alpaca-est。这些成果为开源爱沙尼亚语LLM的开发迈出了重要一步。

> This paper explores cost-efficient methods to adapt pretrained Large Language Models (LLMs) to new lower-resource languages, with a specific focus on Estonian. Leveraging the Llama 2 model, we investigate the impact of combining cross-lingual instruction-tuning with additional monolingual pretraining. Our results demonstrate that even a relatively small amount of additional monolingual pretraining followed by cross-lingual instruction-tuning significantly enhances results on Estonian. Furthermore, we showcase cross-lingual knowledge transfer from high-quality English instructions to Estonian, resulting in improvements in commonsense reasoning and multi-turn conversation capabilities. Our best model, named \textsc{Llammas}, represents the first open-source instruction-following LLM for Estonian. Additionally, we publish Alpaca-est, the first general task instruction dataset for Estonia. These contributions mark the initial progress in the direction of developing open-source LLMs for Estonian.

[Arxiv](https://arxiv.org/abs/2404.04042)