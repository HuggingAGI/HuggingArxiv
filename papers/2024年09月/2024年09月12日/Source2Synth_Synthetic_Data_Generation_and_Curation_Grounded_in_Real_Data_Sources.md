# Source2Synth：利用真实数据源生成和整理合成数据

发布时间：2024年09月12日

`LLM应用` `问答系统` `数据处理`

> Source2Synth: Synthetic Data Generation and Curation Grounded in Real Data Sources

# 摘要

> 大型语言模型在处理结构化数据、复杂推理或工具使用的复杂场景时仍显不足。为此，我们推出了 Source2Synth：一种无需人工标注即可赋予 LLM 新技能的创新方法。Source2Synth 通过自定义数据源生成基于真实世界的合成数据，并剔除低质量生成以提升数据集品质。我们将其应用于多跳问答 (MHQA) 和表格问答 (TQA) 两个领域，结果显示，与微调基线相比，WikiSQL 上的 TQA 性能提升了 25.51%，HotPotQA 上的 MHQA 性能提升了 22.57%。

> Large Language Models still struggle in challenging scenarios that leverage structured data, complex reasoning, or tool usage. In this paper, we propose Source2Synth: a new method that can be used for teaching LLMs new skills without relying on costly human annotations. Source2Synth takes as input a custom data source and produces synthetic data points with intermediate reasoning steps grounded in real-world sources. Source2Synth improves the dataset quality by discarding low-quality generations based on their answerability. We demonstrate the generality of this approach by applying it to two challenging domains: we test reasoning abilities in multi-hop question answering (MHQA), and tool usage in tabular question answering (TQA). Our method improves performance by 25.51% for TQA on WikiSQL and 22.57% for MHQA on HotPotQA compared to the fine-tuned baselines.

[Arxiv](https://arxiv.org/abs/2409.08239)