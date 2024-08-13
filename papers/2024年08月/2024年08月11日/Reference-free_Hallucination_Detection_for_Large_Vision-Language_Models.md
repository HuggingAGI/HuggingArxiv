# 大型视觉-语言模型中的无参考幻觉检测

发布时间：2024年08月11日

`LLM应用` `人工智能` `计算机视觉`

> Reference-free Hallucination Detection for Large Vision-Language Models

# 摘要

> 近年来，大型视觉-语言模型（LVLMs）在多个领域取得了显著进步。尽管这些模型在语言理解和视觉输入的问答对话方面表现出色，但它们也容易产生“幻觉”现象。目前，评估这些幻觉的方法多依赖外部工具，这在实际应用中带来了复杂性。因此，我们开展了一项研究，旨在探索无需外部工具的无参考方法是否能有效检测这些幻觉。我们深入研究了三种技术：基于不确定性的、基于一致性的以及监督不确定性量化方法，并在四个代表性模型上进行了实验。结果表明，这些无参考方法能有效识别非事实响应，其中监督不确定性量化方法在各种情况下表现最为出色。

> Large vision-language models (LVLMs) have made significant progress in recent years. While LVLMs exhibit excellent ability in language understanding, question answering, and conversations of visual inputs, they are prone to producing hallucinations. While several methods are proposed to evaluate the hallucinations in LVLMs, most are reference-based and depend on external tools, which complicates their practical application. To assess the viability of alternative methods, it is critical to understand whether the reference-free approaches, which do not rely on any external tools, can efficiently detect hallucinations. Therefore, we initiate an exploratory study to demonstrate the effectiveness of different reference-free solutions in detecting hallucinations in LVLMs. In particular, we conduct an extensive study on three kinds of techniques: uncertainty-based, consistency-based, and supervised uncertainty quantification methods on four representative LVLMs across two different tasks. The empirical results show that the reference-free approaches are capable of effectively detecting non-factual responses in LVLMs, with the supervised uncertainty quantification method outperforming the others, achieving the best performance across different settings.

[Arxiv](https://arxiv.org/abs/2408.05767)