# 高效 LLM 基准测试的主动评估获取

发布时间：2024年10月08日

`LLM应用` `人工智能` `测试评估`

> Active Evaluation Acquisition for Efficient LLM Benchmarking

# 摘要

> 随着 LLM 的多样化，大量基准测试应运而生，旨在全面评估其能力。这些基准通常包含多样化的数据集和提示，以多角度评估 LLM 性能。然而，全面评估数百或数千个提示的成本极高，涉及计算、金钱和时间。为此，我们探索了通过学习策略选择子集示例来提升评估效率的方法。我们的策略考虑了测试示例间的依赖关系，从而能基于选定示例的结果，准确预测其余示例的评估结果。因此，仅需获取选定子集的实际评估结果。我们深入研究了多种子集选择策略，并创新性地引入了一种基于强化学习的策略，充分利用了这些依赖关系。实证结果显示，与以往方法相比，我们的方法在大幅减少评估提示数量的同时，仍能保持准确的性能估计。

> As large language models (LLMs) become increasingly versatile, numerous large scale benchmarks have been developed to thoroughly assess their capabilities. These benchmarks typically consist of diverse datasets and prompts to evaluate different aspects of LLM performance. However, comprehensive evaluations on hundreds or thousands of prompts incur tremendous costs in terms of computation, money, and time. In this work, we investigate strategies to improve evaluation efficiency by selecting a subset of examples from each benchmark using a learned policy. Our approach models the dependencies across test examples, allowing accurate prediction of the evaluation outcomes for the remaining examples based on the outcomes of the selected ones. Consequently, we only need to acquire the actual evaluation outcomes for the selected subset. We rigorously explore various subset selection policies and introduce a novel RL-based policy that leverages the captured dependencies. Empirical results demonstrate that our approach significantly reduces the number of evaluation prompts required while maintaining accurate performance estimates compared to previous methods.

[Arxiv](https://arxiv.org/abs/2410.05952)