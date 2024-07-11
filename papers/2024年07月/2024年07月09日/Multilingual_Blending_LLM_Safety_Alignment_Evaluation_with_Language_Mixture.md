# 多语言融合：评估 LLM 安全对齐与语言混合

发布时间：2024年07月09日

`LLM应用` `人工智能` `语言处理`

> Multilingual Blending: LLM Safety Alignment Evaluation with Language Mixture

# 摘要

> 在大型语言模型（LLMs）的开发过程中，安全性始终是核心关注点。为此，研究者和业界专家正日益致力于确保LLM行为符合人类偏好与伦理标准。LLMs通过广泛的多语言数据训练，展现出跨语言和领域的强大泛化能力。然而，当前的安全对齐措施主要针对单一语言场景，其在复杂多语言环境中的效果，尤其是混合语言格式，尚未得到充分研究。本研究提出了“多语言混合”策略，通过混合语言的查询-响应模式，评估在复杂多语言环境下，如GPT-4o、GPT-3.5和Llama3等先进LLMs的安全对齐情况。我们深入探讨了语言可用性、形态学和语言家族等因素如何影响多语言混合策略的有效性。实验表明，缺乏精心设计的提示模板时，多语言混合会显著加剧恶意查询的风险，导致安全对齐的绕过率大幅上升（GPT-3.5为67.23%，GPT-4o为40.34%），远超单一语言场景。此外，不同语言的内在属性也影响多语言混合的表现，形态学和语言家族的差异使得某些语言更易规避安全对齐。这些发现凸显了在多语言复杂环境中评估和优化LLMs安全对齐策略的重要性，以充分发挥其跨语言泛化能力。

> As safety remains a crucial concern throughout the development lifecycle of Large Language Models (LLMs), researchers and industrial practitioners have increasingly focused on safeguarding and aligning LLM behaviors with human preferences and ethical standards. LLMs, trained on extensive multilingual corpora, exhibit powerful generalization abilities across diverse languages and domains. However, current safety alignment practices predominantly focus on single-language scenarios, which leaves their effectiveness in complex multilingual contexts, especially for those complex mixed-language formats, largely unexplored. In this study, we introduce Multilingual Blending, a mixed-language query-response scheme designed to evaluate the safety alignment of various state-of-the-art LLMs (e.g., GPT-4o, GPT-3.5, Llama3) under sophisticated, multilingual conditions. We further investigate language patterns such as language availability, morphology, and language family that could impact the effectiveness of Multilingual Blending in compromising the safeguards of LLMs. Our experimental results show that, without meticulously crafted prompt templates, Multilingual Blending significantly amplifies the detriment of malicious queries, leading to dramatically increased bypass rates in LLM safety alignment (67.23% on GPT-3.5 and 40.34% on GPT-4o), far exceeding those of single-language baselines. Moreover, the performance of Multilingual Blending varies notably based on intrinsic linguistic properties, with languages of different morphology and from diverse families being more prone to evading safety alignments. These findings underscore the necessity of evaluating LLMs and developing corresponding safety alignment strategies in a complex, multilingual context to align with their superior cross-language generalization capabilities.

![多语言融合：评估 LLM 安全对齐与语言混合](../../../paper_images/2407.07342/x1.png)

![多语言融合：评估 LLM 安全对齐与语言混合](../../../paper_images/2407.07342/x2.png)

![多语言融合：评估 LLM 安全对齐与语言混合](../../../paper_images/2407.07342/x3.png)

[Arxiv](https://arxiv.org/abs/2407.07342)