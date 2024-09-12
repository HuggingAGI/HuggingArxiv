# 分步翻译：通过分解翻译过程，提升长篇文本的翻译质量

发布时间：2024年09月10日

`LLM应用` `语言服务`

> Translating Step-by-Step: Decomposing the Translation Process for Improved Translation Quality of Long-Form Texts

# 摘要

> 本文介绍了一种逐步进行长篇文本翻译的方法，借鉴了翻译研究的成熟流程。我们不将机器翻译视为单一任务，而是提出一个多轮交互框架，涵盖翻译前研究、起草、修订和校对，逐步提升翻译质量。通过在十种语言对上使用 Gemini 1.5 Pro 进行广泛评估，结果表明，逐步翻译显著优于传统零-shot 方法和早期基线策略，在 WMT2024 上取得了顶尖成果。

> In this paper we present a step-by-step approach to long-form text translation, drawing on established processes in translation studies. Instead of viewing machine translation as a single, monolithic task, we propose a framework that engages language models in a multi-turn interaction, encompassing pre-translation research, drafting, refining, and proofreading, resulting in progressively improved translations. Extensive automatic evaluations using Gemini 1.5 Pro across ten language pairs show that translating step-by-step yields large translation quality improvements over conventional zero-shot prompting approaches and earlier human-like baseline strategies, resulting in state-of-the-art results on WMT2024.

[Arxiv](https://arxiv.org/abs/2409.06790)