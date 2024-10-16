# 逐层重要性不容忽视：在大型语言模型的参数高效微调中，减少内存占用反而能提升性能。

发布时间：2024年10月15日

`LLM理论` `人工智能` `软件工程`

> Layer-wise Importance Matters: Less Memory for Better Performance in Parameter-efficient Fine-tuning of Large Language Models

# 摘要

> 参数高效微调 (PEFT) 方法因其显著减少内存和计算开销的潜力，在将预训练大型语言模型 (LLM) 适应下游任务方面获得了显著的流行度。然而，大多数 PEFT 方法的一个常见限制是它们在所有层中应用统一的架构设计。这种统一性涉及相同的可训练模块，并忽略了各层的重要性差异，导致微调结果次优。为了克服上述限制并获得更好的性能，我们开发了一种新颖的方法，即重要性感知稀疏调优 (IST)，以充分利用固有的稀疏性，并通过有效的层级重要性评分选择最重要的全层子集。所提出的 IST 是一种多功能且即插即用的技术，兼容各种基于层的 PEFT 方法。通过利用估计的重要性分数，IST 动态更新这些在 PEFT 模块中选定的层，从而减少内存需求。我们进一步提供了收敛的理论证明和优越性能的实证证据，以展示 IST 相对于统一更新策略的优势。在一系列 LLM、PEFT 和下游任务上的广泛实验证实了我们提出方法的有效性，展示了 IST 增强现有基于层 PEFT 方法的能力。我们的代码可在 https://github.com/Kaiseem/IST 获取。

> Parameter-Efficient Fine-Tuning (PEFT) methods have gained significant popularity for adapting pre-trained Large Language Models (LLMs) to downstream tasks, primarily due to their potential to significantly reduce memory and computational overheads. However, a common limitation in most PEFT approaches is their application of a uniform architectural design across all layers. This uniformity involves identical trainable modules and ignores the varying importance of each layer, leading to sub-optimal fine-tuning results. To overcome the above limitation and obtain better performance, we develop a novel approach, Importance-aware Sparse Tuning (IST), to fully utilize the inherent sparsity and select the most important subset of full layers with effective layer-wise importance scoring. The proposed IST is a versatile and plug-and-play technique compatible with various PEFT methods that operate on a per-layer basis. By leveraging the estimated importance scores, IST dynamically updates these selected layers in PEFT modules, leading to reduced memory demands. We further provide theoretical proof of convergence and empirical evidence of superior performance to demonstrate the advantages of IST over uniform updating strategies. Extensive experiments on a range of LLMs, PEFTs, and downstream tasks substantiate the effectiveness of our proposed method, showcasing IST's capacity to enhance existing layer-based PEFT methods. Our code is available at https://github.com/Kaiseem/IST.

[Arxiv](https://arxiv.org/abs/2410.11772)