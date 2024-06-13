# 大型语言模型（LLMs）是否已攻克通过示例进行编程的难题？

发布时间：2024年06月12日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在编程示例（PBE）系统中的应用，特别是在代码生成方面的表现。通过实验和分析，论文评估了预训练模型在PBE任务上的性能，并探讨了通过微调提升性能的可能性。此外，论文还分析了LLMs在解决PBE任务上的进展及其局限性，这表明LLMs在增强PBE系统的灵活性与应用范围方面具有潜力。因此，这篇论文属于LLM应用分类。` `编程教育` `人工智能`

> Is Programming by Example solved by LLMs?

# 摘要

> 编程示例（PBE）系统通过输入输出示例生成算法，既实用又理论重要。从用户角度，它们服务于数百万人；从AI角度，PBE代表了一种广泛的少样本归纳推理。鉴于大型语言模型（LLMs）在代码生成上的成就，我们探究LLMs是否已“攻克”PBE。在列表、字符串及鲜为人知的图形编程领域进行实验后，我们发现预训练模型在PBE上表现不佳，但通过微调，若测试问题符合训练分布，性能可显著提升。我们通过实证分析了成功与失败的原因，并探索了如何提升分布外泛化能力。这些发现表明，LLMs在解决PBE任务上取得了显著进展，可能增强PBE系统的灵活性与应用范围，同时也揭示了LLMs的局限性。

> Programming-by-Examples (PBE) aims to generate an algorithm from input-output examples. Such systems are practically and theoretically important: from an end-user perspective, they are deployed to millions of people, and from an AI perspective, PBE corresponds to a very general form of few-shot inductive inference. Given the success of Large Language Models (LLMs) in code-generation tasks, we investigate here the extent to which LLMs can be said to have `solved' PBE. We experiment on classic domains such as lists and strings, and an uncommon graphics programming domain not well represented in typical pretraining data. We find that pretrained models are not effective at PBE, but that they can be fine-tuned for much higher performance, provided the test problems are in-distribution. We analyze empirically what causes these models to succeed and fail, and take steps toward understanding how to achieve better out-of-distribution generalization. Collectively these results suggest that LLMs make strong progress toward solving the typical suite of PBE tasks, potentially increasing the flexibility and applicability of PBE systems, while also identifying ways in which LLMs still fall short.

[Arxiv](https://arxiv.org/abs/2406.08316)