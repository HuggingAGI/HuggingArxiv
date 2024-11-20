# 借助苏格拉底式引导采样来缓解 LLM 自我完善中的尾部收窄现象

发布时间：2024年11月01日

`LLM应用` `语言模型`

> Mitigating Tail Narrowing in LLM Self-Improvement via Socratic-Guided Sampling

# 摘要

> 自我改进方法能让大型语言模型（LLMs）自行生成解决方案，并对筛选出的高质量原理进行迭代训练。此过程确实有效，降低了LLMs推理对人类监督的依赖，然而性能很快就趋于平稳。我们深入探究发现，模型容易对简单查询过度采样，对未掌握的查询采样不足。随着迭代推进，这种采样不均衡愈发严重，形成长尾分布，致使困难查询的解决方案近乎消失。这一现象限制了自我改进模型的性能增长。直接的解决办法是暴力采样来平衡分布，但会大幅增加计算成本。本文引入了引导式自我改进（GSI）策略，旨在提高对挑战性重尾数据的采样效率。它借助苏格拉底式的引导信号助力LLM处理复杂查询，减少探索工作量，降低计算开销。在四个不同数学任务模型上的实验表明，GSI在性能与效率之间实现了平衡，在保留任务中也表现出色。

> Self-improvement methods enable large language models (LLMs) to generate solutions themselves and iteratively train on filtered, high-quality rationales. This process proves effective and reduces the reliance on human supervision in LLMs' reasoning, but the performance soon plateaus. We delve into the process and find that models tend to over-sample on easy queries and under-sample on queries they have yet to master. As iterations proceed, this imbalance in sampling is exacerbated, leading to a long-tail distribution where solutions to difficult queries almost diminish. This phenomenon limits the performance gain of self-improving models. A straightforward solution is brute-force sampling to balance the distribution, which significantly raises computational costs. In this paper, we introduce Guided Self-Improvement (GSI), a strategy aimed at improving the efficiency of sampling challenging heavy-tailed data. It leverages Socratic-style guidance signals to help LLM reasoning with complex queries, reducing the exploration effort and minimizing computational overhead. Experiments on four models across diverse mathematical tasks show that GSI strikes a balance between performance and efficiency, while also being effective on held-out tasks.

[Arxiv](https://arxiv.org/abs/2411.00750)