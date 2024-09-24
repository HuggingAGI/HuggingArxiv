# 借助检索上下文，提升医疗领域大型语言模型的性能

发布时间：2024年09月23日

`LLM应用`

> Boosting Healthcare LLMs Through Retrieved Context

# 摘要

> 大型语言模型（LLM）在自然语言处理中表现出色，但其事实错误和幻觉问题限制了其在医疗等关键领域的应用。上下文检索方法通过引入相关信息，成为提升 LLM 事实性和可靠性的关键手段。本研究深入探讨了医疗领域内上下文检索方法的优化与性能，发现开放 LLM 在优化检索系统的辅助下，能在多项选择题回答等医疗基准上与顶尖私人解决方案媲美。鉴于问题中包含答案选项的非现实性（仅见于医学考试），以及 LLM 在无选项情况下的性能下降，我们进一步扩展了检索系统，提出 OpenMedPrompt 管道，旨在生成更可靠的开放式答案，推动该技术向实际应用迈进。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in natural language processing, and yet, their factual inaccuracies and hallucinations limits their application, particularly in critical domains like healthcare. Context retrieval methods, by introducing relevant information as input, have emerged as a crucial approach for enhancing LLM factuality and reliability. This study explores the boundaries of context retrieval methods within the healthcare domain, optimizing their components and benchmarking their performance against open and closed alternatives. Our findings reveal how open LLMs, when augmented with an optimized retrieval system, can achieve performance comparable to the biggest private solutions on established healthcare benchmarks (multiple-choice question answering). Recognizing the lack of realism of including the possible answers within the question (a setup only found in medical exams), and after assessing a strong LLM performance degradation in the absence of those options, we extend the context retrieval system in that direction. In particular, we propose OpenMedPrompt a pipeline that improves the generation of more reliable open-ended answers, moving this technology closer to practical application.

[Arxiv](https://arxiv.org/abs/2409.15127)