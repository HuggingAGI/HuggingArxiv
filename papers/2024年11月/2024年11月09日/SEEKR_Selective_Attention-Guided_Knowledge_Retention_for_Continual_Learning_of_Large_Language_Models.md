# SEEKR：用于大型语言模型持续学习的选择性注意力引导知识保留

发布时间：2024年11月09日

`LLM应用` `语言模型` `持续学习`

> SEEKR: Selective Attention-Guided Knowledge Retention for Continual Learning of Large Language Models

# 摘要

> 持续学习（CL）对于语言模型动态适应不断变化的现实世界需求至关重要。为了减轻 CL 中的灾难性遗忘问题，数据重放已被证明是一种简单有效的策略，随后基于数据重放的提炼可以进一步提高性能。然而，现有方法未能充分利用先前任务模型中嵌入的知识，导致需要相对大量的重放样本才能取得良好的结果。在这项工作中，我们首先探索并强调注意力权重在知识保留中的重要性，然后提出了一种选择性注意力引导的知识保留方法（SEEKR），用于大型语言模型（LLM）基于数据高效重放的持续学习。具体来说，SEEKR 对选定的注意力头进行注意力提炼，以实现更精细的知识保留，其中提出的基于遗忘性和任务敏感性的度量用于识别最有价值的注意力头。在两个针对 LLM 的持续学习基准上的实验结果表明，SEEKR 在性能和效率方面均优于现有方法。明确地说，SEEKR 仅使用其他方法所用重放数据的 1/10 就达到了相当甚至更好的性能，并将重放数据的比例降低到 1%。

> Continual learning (CL) is crucial for language models to dynamically adapt to the evolving real-world demands. To mitigate the catastrophic forgetting problem in CL, data replay has been proven a simple and effective strategy, and the subsequent data-replay-based distillation can further enhance the performance. However, existing methods fail to fully exploit the knowledge embedded in models from previous tasks, resulting in the need for a relatively large number of replay samples to achieve good results. In this work, we first explore and emphasize the importance of attention weights in knowledge retention, and then propose a SElective attEntion-guided Knowledge Retention method (SEEKR) for data-efficient replay-based continual learning of large language models (LLMs). Specifically, SEEKR performs attention distillation on the selected attention heads for finer-grained knowledge retention, where the proposed forgettability-based and task-sensitivity-based measures are used to identify the most valuable attention heads. Experimental results on two continual learning benchmarks for LLMs demonstrate the superiority of SEEKR over the existing methods on both performance and efficiency. Explicitly, SEEKR achieves comparable or even better performance with only 1/10 of the replayed data used by other methods, and reduces the proportion of replayed data to 1%.

[Arxiv](https://arxiv.org/abs/2411.06171)