# Transformer 何时能数到 n？

发布时间：2024年07月21日

`LLM理论` `人工智能`

> When Can Transformers Count to n?

# 摘要

> 尽管基于transformer的大型语言模型能应对复杂任务，但它们是否也有力所不及的简单任务呢？我们探讨了基础的计数任务，即统计特定词汇在文本中出现的次数。研究发现，当transformer状态维度与上下文长度成线性关系时，这类任务可解。然而，我们的解决方案在此界限外失效，并从理论上论证了为何受尺寸限制的transformer难以完成此任务。实证研究同样揭示了性能的相变现象。这些发现强调了深入理解transformer处理简单任务能力的重要性。

> Large language models based on the transformer architectures can solve highly complex tasks. But are there simple tasks that such models cannot solve? Here we focus on very simple counting tasks, that involve counting how many times a token in the vocabulary have appeared in a string. We show that if the dimension of the transformer state is linear in the context length, this task can be solved. However, the solution we propose does not scale beyond this limit, and we provide theoretical arguments for why it is likely impossible for a size limited transformer to implement this task. Our empirical results demonstrate the same phase-transition in performance, as anticipated by the theoretical argument. Our results demonstrate the importance of understanding how transformers can solve simple tasks.

![Transformer 何时能数到 n？](../../../paper_images/2407.15160/histogram_method.png)

![Transformer 何时能数到 n？](../../../paper_images/2407.15160/attention_method.png)

![Transformer 何时能数到 n？](../../../paper_images/2407.15160/mthr.png)

![Transformer 何时能数到 n？](../../../paper_images/2407.15160/gemini_count.png)

[Arxiv](https://arxiv.org/abs/2407.15160)