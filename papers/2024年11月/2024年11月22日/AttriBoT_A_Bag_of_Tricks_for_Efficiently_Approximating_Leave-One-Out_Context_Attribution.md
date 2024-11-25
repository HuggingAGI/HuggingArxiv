# AttriBoT：实现有效近似留一法上下文归因的诸多技巧

发布时间：2024年11月22日

`LLM应用` `语言模型` `可解释性`

> AttriBoT: A Bag of Tricks for Efficiently Approximating Leave-One-Out Context Attribution

# 摘要

> 上下文输入对大型语言模型（LLMs）行为的影响，推动了旨在量化每个上下文跨度对LLM生成影响的上下文归因方法的发展。留一法（LOO）误差，即衡量移除给定上下文跨度时LLM响应可能性的变化，为进行上下文归因提供了原则性途径，但对于大型模型而言，其计算成本可能极高。在本项工作中，我们推出了AttriBoT，这是一系列用于高效计算LOO误差近似值以实现上下文归因的新颖技术。具体而言，AttriBoT通过使用缓存激活避免冗余操作，进行分层归因以降低计算量，并借助较小的代理模型模拟大型目标模型的行为。综合来看，AttriBoT能够实现超过300倍的加速，同时相比先前的上下文归因方法，能更贴合目标模型的LOO误差。这种性能的大幅提升，使得计算给定响应的上下文归因比生成响应本身快30倍，有力地支持了需要大规模计算归因的实际应用。我们发布了AttriBoT的便捷高效实现，以促进高效的LLM可解释性，并鼓励未来开发更高效的上下文归因方法。

> The influence of contextual input on the behavior of large language models (LLMs) has prompted the development of context attribution methods that aim to quantify each context span's effect on an LLM's generations. The leave-one-out (LOO) error, which measures the change in the likelihood of the LLM's response when a given span of the context is removed, provides a principled way to perform context attribution, but can be prohibitively expensive to compute for large models. In this work, we introduce AttriBoT, a series of novel techniques for efficiently computing an approximation of the LOO error for context attribution. Specifically, AttriBoT uses cached activations to avoid redundant operations, performs hierarchical attribution to reduce computation, and emulates the behavior of large target models with smaller proxy models. Taken together, AttriBoT can provide a >300x speedup while remaining more faithful to a target model's LOO error than prior context attribution methods. This stark increase in performance makes computing context attributions for a given response 30x faster than generating the response itself, empowering real-world applications that require computing attributions at scale. We release a user-friendly and efficient implementation of AttriBoT to enable efficient LLM interpretability as well as encourage future development of efficient context attribution methods.

[Arxiv](https://arxiv.org/abs/2411.15102)