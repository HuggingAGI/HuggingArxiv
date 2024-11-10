# 大型语言模型训练后量化中跨块的交互

发布时间：2024年11月06日

`LLM应用` `神经网络` `语言模型`

> Interactions Across Blocks in Post-Training Quantization of Large Language Models

# 摘要

> 训练后量化被广泛用于降低神经网络的计算需求。通常，单个子结构，如层或层块，通过微调相应的权重以最小化其预激活中的量化误差的目的进行量化。从最小化任务损失的全局目标推导出这个局部目标涉及两个关键的简化：假设子结构相互独立，并忽略后续子结构以及任务损失的知识。在这项工作中，我们评估了这些简化对大型语言模型的仅权重量化的影响。我们引入了两种多块微调策略，并将它们与微调单个变压器块的基线进行比较。第一种通过联合优化多个量化块来捕获块之间的权重相关性。第二种通过最小化下游预激活中的误差而不是仅仅关注量化块来纳入后续块的知识。我们的发现表明，这些方法的有效性取决于特定的网络模型，对某些模型没有影响，但对其他模型显示出显著的益处。

> Post-training quantization is widely employed to reduce the computational demands of neural networks. Typically, individual substructures, such as layers or blocks of layers, are quantized with the objective of minimizing quantization errors in their pre-activations by fine-tuning the corresponding weights. Deriving this local objective from the global objective of minimizing task loss involves two key simplifications: assuming substructures are mutually independent and ignoring the knowledge of subsequent substructures as well as the task loss. In this work, we assess the effects of these simplifications on weight-only quantization of large language models. We introduce two multi-block fine-tuning strategies and compare them against the baseline of fine-tuning single transformer blocks. The first captures correlations of weights across blocks by jointly optimizing multiple quantized blocks. The second incorporates knowledge of subsequent blocks by minimizing the error in downstream pre-activations rather than focusing solely on the quantized block. Our findings indicate that the effectiveness of these methods depends on the specific network model, with no impact on some models but demonstrating significant benefits for others.

[Arxiv](https://arxiv.org/abs/2411.03934)