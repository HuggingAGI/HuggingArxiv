# Transformers 的次二次替代方案面临根本性限制

发布时间：2024年10月05日

`LLM理论` `文档处理`

> Fundamental Limitations on Subquadratic Alternatives to Transformers

# 摘要

> Transformer 架构在众多大型语言模型中广泛应用，其核心的注意力机制用于计算标记间的相关性。然而，注意力计算的时间复杂度为输入大小的二次方，成为 Transformer 操作的瓶颈。为解决这一问题，研究人员尝试了多种方法，如设计更快的启发式算法或提出替代注意力机制。例如，Mamba 等状态空间模型旨在以近线性时间替代注意力机制。本文证明，任何此类方法都无法完成 Transformer 能执行的关键任务（基于细粒度复杂性理论的一个流行猜想）。我们聚焦于文档相似性任务，即在众多文档中寻找最相似的一对。我们证明 Transformer 能胜任此任务，且任何算法都无法在次二次时间内完成。因此，任何能在次二次时间内评估的模型，无论是因为次二次时间的注意力启发式算法、更快的替代方案如 Mamba，还是其他原因，都无法执行此任务。简而言之，涉及文档相似性的任务，仍需依赖 Transformer，无法避免其二次运行时间。

> The Transformer architecture is widely deployed in many popular and impactful Large Language Models. At its core is the attention mechanism for calculating correlations between pairs of tokens. Performing an attention computation takes quadratic time in the input size, and had become the time bottleneck for transformer operations. In order to circumvent this, researchers have used a variety of approaches, including designing heuristic algorithms for performing attention computations faster, and proposing alternatives to the attention mechanism which can be computed more quickly. For instance, state space models such as Mamba were designed to replace attention with an almost linear time alternative.
  In this paper, we prove that any such approach cannot perform important tasks that Transformer is able to perform (assuming a popular conjecture from fine-grained complexity theory). We focus on document similarity tasks, where one is given as input many documents and would like to find a pair which is (approximately) the most similar. We prove that Transformer is able to perform this task, and we prove that this task cannot be performed in truly subquadratic time by any algorithm. Thus, any model which can be evaluated in subquadratic time - whether because of subquadratic-time heuristics for attention, faster attention replacements like Mamba, or any other reason - cannot perform this task. In other words, in order to perform tasks that (implicitly or explicitly) involve document similarity, one may as well use Transformer and cannot avoid its quadratic running time.

[Arxiv](https://arxiv.org/abs/2410.04271)