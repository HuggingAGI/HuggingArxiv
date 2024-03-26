# 通过深入探究损失视角，本研究旨在揭示语言模型所展现的新兴能力，剖析其内在机制及其在实际应用中的表现。

发布时间：2024年03月23日

`LLM理论` `模型涌现能力`

> Understanding Emergent Abilities of Language Models from the Loss Perspective

> 近期研究表明，语言模型的涌现能力并非大型模型专享，这一观点受到挑战。原因在于两点：一方面，小尺寸模型也能在涌现能力上展现高水平；另一方面，衡量这些能力所采用的不连续性指标遭到怀疑。本文提出，不如从预训练损失而非模型大小或训练计算量的角度探讨涌现能力。实验表明，预训练损失相同而模型大小和数据规模各异的模型，在多种下游任务上的表现并无二致。同时，我们发现当模型的预训练损失降到某一特定阈值之下时，无论度量方式是否连续，该模型都能在特定任务上展现涌现能力，若未达到此阈值，则性能基本等同于随机猜测。据此，我们重新诠释了涌现能力，将其定义为那些在低预训练损失模型中体现且无法单纯通过外推高预训练损失模型性能趋势预见的能力。

> Recent studies have put into question the belief that emergent abilities in language models are exclusive to large models. This skepticism arises from two observations: 1) smaller models can also exhibit high performance on emergent abilities and 2) there is doubt on the discontinuous metrics used to measure these abilities. In this paper, we propose to study emergent abilities in the lens of pre-training loss, instead of model size or training compute. We demonstrate that the models with the same pre-training loss, but different model and data sizes, generate the same performance on various downstream tasks. We also discover that a model exhibits emergent abilities on certain tasks -- regardless of the continuity of metrics -- when its pre-training loss falls below a specific threshold. Before reaching this threshold, its performance remains at the level of random guessing. This inspires us to redefine emergent abilities as those that manifest in models with lower pre-training losses, highlighting that these abilities cannot be predicted by merely extrapolating the performance trends of models with higher pre-training losses.

[Arxiv](https://arxiv.org/abs/2403.15796)