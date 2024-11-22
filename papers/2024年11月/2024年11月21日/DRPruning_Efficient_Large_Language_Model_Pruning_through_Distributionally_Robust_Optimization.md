# DRPruning：借助分布鲁棒优化达成高效的大型语言模型剪枝

发布时间：2024年11月21日

`LLM应用` `模型优化`

> DRPruning: Efficient Large Language Model Pruning through Distributionally Robust Optimization

# 摘要

> 大型语言模型（LLMs）成果斐然，但也面临着模型规模扩大与计算成本上升的难题。结构化剪枝虽能缩减模型规模、加快推理速度，却常致使不同领域的性能退化不均，造成性能偏差。为此，我们推出 DRPruning 方案，融入分布式鲁棒优化以恢复各领域的均衡性能，并加以改进以增强稳健性。在单语和多语环境下的实验显示，我们的方法在剪枝和持续预训练方面优于同等规模的模型，在困惑度、下游任务和指令调整上表现卓越。我们还进行了分析，证实了我们的方法对各种领域和分布变化的稳健性。另外，我们的方法能自动确定最优参考损失和数据比率，展现出更广泛的应用前景。我们的代码可在 https://github.com/hexuandeng/DRPruning 获取。

> Large language models (LLMs) deliver impressive results but face challenges from increasing model sizes and computational costs. Structured pruning reduces model size and speeds up inference but often causes uneven degradation across domains, leading to biased performance. To address this, we propose DRPruning, which incorporates distributionally robust optimization to restore balanced performance across domains, along with further improvements to enhance robustness. Experiments in monolingual and multilingual settings show that our method surpasses similarly sized models in pruning and continued pretraining over perplexity, downstream tasks, and instruction tuning. We further provide analysis demonstrating the robustness of our method towards various domains and distribution shifts. Furthermore, our method automatically determines optimal reference losses and data ratios, suggesting potential for broader applications. Our code is available at https://github.com/hexuandeng/DRPruning.

[Arxiv](https://arxiv.org/abs/2411.14055)