# AutoMixQ：实现高性能且内存高效微调的自调整量化

发布时间：2024年11月20日

`LLM应用` `资源优化`

> AutoMixQ: Self-Adjusting Quantization for High Performance Memory-Efficient Fine-Tuning

# 摘要

> 在资源有限的情况下对大型语言模型（LLMs）进行微调是深度学习面临的重大挑战。低秩自适应（LoRA）、剪枝和量化均为提升资源效率的有效手段。然而，直接将它们结合使用常常致使性能欠佳，特别是在对所有模型层进行统一量化时。这是因为剪枝带来了复杂且不均匀的层间关系，所以需要更精细的量化策略。为此，我们提出了 AutoMixQ，这是一个端到端的优化框架，能为每个 LLM 层选定最优量化配置。AutoMixQ 借助轻量级性能模型来引导选择过程，相比穷举搜索方法，大幅减少了时间和计算资源。通过引入帕累托最优性，AutoMixQ 平衡了内存使用与性能，在严格的资源约束下逼近模型能力的上限。我们在广泛使用的基准测试中的实验表明，AutoMixQ 在降低内存消耗的同时取得了出色的性能。例如，在 LLaMA-7B 中，当剪枝率为 30％时，AutoMixQ 在 BoolQ 上达到 66.21％，而 LoRA 为 62.45％，LoftQ 为 58.96％，同时与 LoRA 相比内存消耗降低 35.5％，与 LoftQ 相比降低 27.5％。

> Fine-tuning large language models (LLMs) under resource constraints is a significant challenge in deep learning. Low-Rank Adaptation (LoRA), pruning, and quantization are all effective methods for improving resource efficiency. However, combining them directly often results in suboptimal performance, especially with uniform quantization across all model layers. This is due to the complex, uneven interlayer relationships introduced by pruning, necessitating more refined quantization strategies. To address this, we propose AutoMixQ, an end-to-end optimization framework that selects optimal quantization configurations for each LLM layer. AutoMixQ leverages lightweight performance models to guide the selection process, significantly reducing time and computational resources compared to exhaustive search methods. By incorporating Pareto optimality, AutoMixQ balances memory usage and performance, approaching the upper bounds of model capability under strict resource constraints. Our experiments on widely used benchmarks show that AutoMixQ reduces memory consumption while achieving superior performance. For example, at a 30\% pruning rate in LLaMA-7B, AutoMixQ achieved 66.21\% on BoolQ compared to 62.45\% for LoRA and 58.96\% for LoftQ, while reducing memory consumption by 35.5\% compared to LoRA and 27.5\% compared to LoftQ.

[Arxiv](https://arxiv.org/abs/2411.13814)