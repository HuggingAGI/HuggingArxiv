# 关于模型剪枝后的后训练缩放规律

发布时间：2024年11月15日

`LLM应用` `人工智能` `模型优化`

> Scaling Law for Post-training after Model Pruning

# 摘要

> 基于 Transformer 架构的大型语言模型（LLMs）在众多领域和任务中得到广泛运用。然而，其规模的不断增大对硬件提出极高要求，限制了实际应用。为解决此问题，模型剪枝技术应运而生，能在保持高性能的同时打造更高效的模型。但剪枝后的后训练对性能恢复至关重要，且可能耗费大量资源。本文探究了剪枝后 LLMs 的后训练需求，并引入了一个缩放定律以确定最佳的后训练数据量。对采用深度剪枝、宽度剪枝和 2:4 半结构化剪枝的 Llama-3 和 Qwen-2.5 系列模型进行的后训练实验表明，剪枝比例越高，恢复性能所需的后训练数据越多，而较大的 LLMs 所需数据则较少。所提出的缩放定律依据剪枝前后的参数数量以及后训练的令牌数量来预测模型的损失。此外，我们发现从小型 LLMs 得出的缩放定律能够可靠地推广至大型 LLMs。此项工作为剪枝后 LLMs 的后训练提供了宝贵见解，并为优化后训练数据的使用提供了实用的缩放定律。

> Large language models (LLMs) based on the Transformer architecture are widely employed across various domains and tasks. However, their increasing size imposes significant hardware demands, limiting practical deployment. To mitigate this, model pruning techniques have been developed to create more efficient models while maintaining high performance. Despite this, post-training after pruning is crucial for performance recovery and can be resource-intensive. This paper investigates the post-training requirements of pruned LLMs and introduces a scaling law to determine the optimal amount of post-training data. Post-training experiments with the Llama-3 and Qwen-2.5 series models, pruned using depth pruning, width pruning, and 2:4 semi-structured pruning, show that higher pruning ratios necessitate more post-training data for performance recovery, whereas larger LLMs require less. The proposed scaling law predicts a model's loss based on its parameter counts before and after pruning, as well as the post-training token counts. Furthermore, we find that the scaling law established from smaller LLMs can be reliably extrapolated to larger LLMs. This work provides valuable insights into the post-training of pruned LLMs and offers a practical scaling law for optimizing post-training data usage.

[Arxiv](https://arxiv.org/abs/2411.10272)