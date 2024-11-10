# 在基于梯度的方法下，大型语言模型中分布内与分布外数据的遗忘

发布时间：2024年11月06日

`LLM理论` `机器学习` `模型评估`

> Unlearning in- vs. out-of-distribution data in LLMs under gradient-based method

# 摘要

> 机器遗忘学习旨在解决从已学习的模型中消除所选训练示例的影响的问题。尽管对这个问题的关注日益增加，但如何评估大型语言模型（LLM）中的遗忘学习，以及要遗忘的数据的关键属性是什么，这些会影响遗忘学习的质量和效率，仍然是一个开放的研究问题。这项工作形式化了一种评估生成模型中遗忘学习质量的指标，并使用它来评估遗忘学习质量和性能之间的权衡。我们证明，遗忘分布外的示例需要更多的遗忘步骤，但总体上呈现出更好的权衡。然而，对于分布内的示例，我们观察到随着遗忘学习的进行，性能会迅速下降。我们进一步评估了在经典的基于梯度上升的方法下，示例的记忆和难度如何影响遗忘学习。

> Machine unlearning aims to solve the problem of removing the influence of selected training examples from a learned model. Despite the increasing attention to this problem, it remains an open research question how to evaluate unlearning in large language models (LLMs), and what are the critical properties of the data to be unlearned that affect the quality and efficiency of unlearning. This work formalizes a metric to evaluate unlearning quality in generative models, and uses it to assess the trade-offs between unlearning quality and performance. We demonstrate that unlearning out-of-distribution examples requires more unlearning steps but overall presents a better trade-off overall. For in-distribution examples, however, we observe a rapid decay in performance as unlearning progresses. We further evaluate how example's memorization and difficulty affect unlearning under a classical gradient ascent-based approach.

[Arxiv](https://arxiv.org/abs/2411.04388)