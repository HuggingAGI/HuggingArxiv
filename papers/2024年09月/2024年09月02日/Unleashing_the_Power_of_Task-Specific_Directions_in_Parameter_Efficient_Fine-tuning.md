# 激发参数高效微调中任务特定方向的潜能

发布时间：2024年09月02日

`LLM理论` `人工智能` `软件开发`

> Unleashing the Power of Task-Specific Directions in Parameter Efficient Fine-tuning

# 摘要

> 尽管大型语言模型在下游任务中表现卓越，但全面微调所有参数会消耗大量资源。为此，我们研究了 LoRA 等参数高效微调策略，并聚焦于任务特定方向的重要性。我们构建了一个框架来明确这些方向，并探讨其实际应用中的挑战。接着，我们创新性地提出了 LoRA-Dash 方法，旨在通过优化微调过程中的任务特定方向，显著提升模型性能。实验结果充分验证了 LoRA-Dash 的有效性，深入分析更揭示了其内在工作原理。相关代码已公开，供进一步研究使用。

> Large language models demonstrate impressive performance on downstream tasks, yet requiring extensive resource consumption when fully fine-tuning all parameters. To mitigate this, Parameter Efficient Fine-Tuning (PEFT) strategies, such as LoRA, have been developed. In this paper, we delve into the concept of task-specific directions--critical for transitioning large models from pre-trained states to task-specific enhancements in PEFT. We propose a framework to clearly define these directions and explore their properties, and practical utilization challenges. We then introduce a novel approach, LoRA-Dash, which aims to maximize the impact of task-specific directions during the fine-tuning process, thereby enhancing model performance on targeted tasks. Extensive experiments have conclusively demonstrated the effectiveness of LoRA-Dash, and in-depth analyses further reveal the underlying mechanisms of LoRA-Dash. The code is available at https://github.com/Chongjie-Si/Subspace-Tuning.

[Arxiv](https://arxiv.org/abs/2409.01035)