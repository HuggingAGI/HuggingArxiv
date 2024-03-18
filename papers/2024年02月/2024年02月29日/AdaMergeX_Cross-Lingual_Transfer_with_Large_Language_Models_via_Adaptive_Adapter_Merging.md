# [AdaMergeX 技术借助自适应适配器融合，实现在大型语言模型中有效进行跨语言迁移。这一方法针对不同语言间的知识转移进行了优化，使得大型语言模型能够在多种语言间灵活应用。](https://arxiv.org/abs/2402.18913)

发布时间：2024年02月29日

`LLM应用`

> AdaMergeX: Cross-Lingual Transfer with Large Language Models via Adaptive Adapter Merging

> 跨语言迁移作为解决特定语言目标任务直接微调时面临的数据有限问题的有效方案，通过分别对源语言的任务和目标语言的另一任务进行微调，巧妙地分离出“任务技能”与“语言特性”。但当前方法仍无法彻底剥离任务技能与源语言或语言特性与特定任务间的联系。本文聚焦于目标语言和源语言在执行任务时表现出的语言差异，并发现这种差异不受具体任务影响，具有跨任务的一致性。据此，我们创新性地提出了名为$\texttt{AdaMergeX}$的跨语言迁移新方法，利用自适应适配器融合技术。通过引入参照任务，我们揭示了在双语环境下针对参照任务和目标任务微调后适配器的变化规律具有一致性，从而能够整合其余三个适配器得到目标适配器。此外，我们还设计了一种结构自适应的适配器融合策略。实际应用证明，我们的方法在各场景下均展现出卓越的跨语言迁移效果，全面优于已有的各类方法。

> As an effective alternative to the direct fine-tuning on target tasks in specific languages, cross-lingual transfer addresses the challenges of limited training data by decoupling ''task ability'' and ''language ability'' by fine-tuning on the target task in the source language and another selected task in the target language, respectively. However, they fail to fully separate the task ability from the source language or the language ability from the chosen task. In this paper, we acknowledge the mutual reliance between task ability and language ability and direct our attention toward the gap between the target language and the source language on tasks. As the gap removes the impact of tasks, we assume that it remains consistent across tasks. Based on this assumption, we propose a new cross-lingual transfer method called $\texttt{AdaMergeX}$ that utilizes adaptive adapter merging. By introducing a reference task, we can determine that the divergence of adapters fine-tuned on the reference task in both languages follows the same distribution as the divergence of adapters fine-tuned on the target task in both languages. Hence, we can obtain target adapters by combining the other three adapters. Furthermore, we propose a structure-adaptive adapter merging method. Our empirical results demonstrate that our approach yields new and effective cross-lingual transfer, outperforming existing methods across all settings.

[Arxiv](https://arxiv.org/abs/2402.18913)