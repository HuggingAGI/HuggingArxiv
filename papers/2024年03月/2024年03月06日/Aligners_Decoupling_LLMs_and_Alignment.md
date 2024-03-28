# 本文探讨“对齐器”，旨在将大型语言模型（LLM）与其对齐机制分离。通过这种方法，我们深入研究如何独立优化LLM的性能与对其行为和输出的可控性，以实现更好的对齐效果。

发布时间：2024年03月06日

`LLM应用`

> Aligners: Decoupling LLMs and Alignment

# 摘要

> 为了确保LLMs在多数应用场景下的安全性和实用性，它们需与人类预期保持一致，但这是一项既具挑战又耗时的任务，而且每次更换LLM或对齐标准都要重新执行。因此，我们建议采用一种新的策略，即训练通用对齐器模型，在必要时对任意LLM按指定标准进行动态对齐，这样还能减轻对齐过程对模型性能的潜在消极影响。我们独创的对齐器训练方案完全基于用带有提示的LLM生成的合成数据，并能灵活调整以满足多种对齐准则需求。我们通过实例训练了一个“伦理”对齐器，并通过实证研究验证了其实效性。

> Large Language Models (LLMs) need to be aligned with human expectations to ensure their safety and utility in most applications. Alignment is challenging, costly, and needs to be repeated for every LLM and alignment criterion. We propose to decouple LLMs and alignment by training aligner models that can be used to align any LLM for a given criteria on an as-needed basis, thus also reducing the potential negative impacts of alignment on performance. Our recipe for training the aligner models solely relies on synthetic data generated with a (prompted) LLM and can be easily adjusted for a variety of alignment criteria. We illustrate our method by training an "ethical" aligner and verify its efficacy empirically.

[Arxiv](https://arxiv.org/abs/2403.04224)