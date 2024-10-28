# 混合鹦鹉：专家在记忆方面的改进多于推理方面。

发布时间：2024年10月24日

`LLM理论` `计算机科学` `人工智能`

> Mixture of Parrots: Experts improve memorization more than reasoning

# 摘要

> 摘要：专家混合（MoE）架构能够在计算开销最小的情况下大幅增加模型参数的总数。然而，MoE 与标准密集型转换器之间是否存在性能权衡尚不清楚。在本文中，我们表明，当我们增加专家数量（同时固定活动参数的数量）时，记忆性能持续提高，而推理能力则达到饱和。我们首先分析了 MoE 在推理方面的理论局限性。我们证明，存在某些宽度的任何数量的专家都无法解决的图问题；然而，相同的任务可以通过宽度稍大的密集模型轻松解决。另一方面，我们发现，在内存密集型任务中，MoE 可以有效地利用大量专家和少量活动参数来记忆数据。我们在合成图问题和内存密集型闭卷检索任务上对这些发现进行了实证验证。最后，我们预训练了一系列 MoE 和密集型转换器，并在数学和自然语言的常用基准上对它们进行评估。我们发现，增加专家数量有助于解决知识密集型任务，但对于推理任务却无法产生同样的好处。

> 
Abstract:The Mixture-of-Experts (MoE) architecture enables a significant increase in the total number of model parameters with minimal computational overhead. However, it is not clear what performance tradeoffs, if any, exist between MoEs and standard dense transformers. In this paper, we show that as we increase the number of experts (while fixing the number of active parameters), the memorization performance consistently increases while the reasoning capabilities saturate. We begin by analyzing the theoretical limitations of MoEs at reasoning. We prove that there exist graph problems that cannot be solved by any number of experts of a certain width; however, the same task can be easily solved by a dense model with a slightly larger width. On the other hand, we find that on memory-intensive tasks, MoEs can effectively leverage a small number of active parameters with a large number of experts to memorize the data. We empirically validate these findings on synthetic graph problems and memory-intensive closed book retrieval tasks. Lastly, we pre-train a series of MoEs and dense transformers and evaluate them on commonly used benchmarks in math and natural language. We find that increasing the number of experts helps solve knowledge-intensive tasks, but fails to yield the same benefits for reasoning tasks.
    

[Arxiv](https://arxiv.org/pdf/2410.19034)