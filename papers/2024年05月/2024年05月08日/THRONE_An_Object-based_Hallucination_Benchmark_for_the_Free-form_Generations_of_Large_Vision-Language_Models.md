# THRONE：大型视觉-语言模型自由形式生成的对象幻觉基准在这篇文章中，我们将介绍 THRONE，这是一个专门为大型视觉-语言模型设计的基于对象的幻觉基准。THRONE 旨在评估这些模型在自由形式生成任务中的表现，特别是在处理复杂场景和对象时的幻觉能力。通过 THRONE，我们希望推动视觉-语言模型在理解和生成更加丰富、多样化的内容方面的进步，同时揭示模型在处理幻觉时的潜在挑战和局限性。

发布时间：2024年05月08日

`LLM理论

理由：这篇论文关注的是大型视觉-语言模型（LVLMs）中的幻觉问题，特别是类型I幻觉的量化评估。它提出了一个新的框架THRONE来评估自由回答中的幻觉，并探讨了现有指标和基准的不足。这些问题属于对大型语言模型（LLM）理论层面的探讨和改进，因此归类为LLM理论。虽然论文中提到了模型的应用（如数据增强方法），但其核心贡献在于理论框架的提出和幻觉问题的深入分析，而非直接的应用开发或Agent的设计。` `人工智能评估` `数据增强`

> THRONE: An Object-based Hallucination Benchmark for the Free-form Generations of Large Vision-Language Models

# 摘要

> 在大型视觉-语言模型中，幻觉问题依旧棘手。现有基准多关注特定问题下的幻觉，即“类型II幻觉”，而忽略了自由回答中的“类型I幻觉”。这些基准还依赖于可能变动的模型API。实际上，我们发现减少类型II幻觉并不意味着类型I幻觉的减少，两者往往呈现反相关。为此，我们推出了THRONE框架，专门用于量化评估自由回答中的类型I幻觉。我们利用公共语言模型来检测幻觉，并计算相关指标。通过对多个LVLMs的评估，我们发现现有指标的提升并未减少类型I幻觉，且现有基准不足以全面衡量类型I幻觉。最后，我们提出了一种简便高效的数据增强方法，作为减少两种幻觉的有效起点。

> Mitigating hallucinations in large vision-language models (LVLMs) remains an open problem. Recent benchmarks do not address hallucinations in open-ended free-form responses, which we term "Type I hallucinations". Instead, they focus on hallucinations responding to very specific question formats -- typically a multiple-choice response regarding a particular object or attribute -- which we term "Type II hallucinations". Additionally, such benchmarks often require external API calls to models which are subject to change. In practice, we observe that a reduction in Type II hallucinations does not lead to a reduction in Type I hallucinations but rather that the two forms of hallucinations are often anti-correlated. To address this, we propose THRONE, a novel object-based automatic framework for quantitatively evaluating Type I hallucinations in LVLM free-form outputs. We use public language models (LMs) to identify hallucinations in LVLM responses and compute informative metrics. By evaluating a large selection of recent LVLMs using public datasets, we show that an improvement in existing metrics do not lead to a reduction in Type I hallucinations, and that established benchmarks for measuring Type I hallucinations are incomplete. Finally, we provide a simple and effective data augmentation method to reduce Type I and Type II hallucinations as a strong baseline.

[Arxiv](https://arxiv.org/abs/2405.05256)