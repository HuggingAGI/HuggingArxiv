# 相关感知选择与合并注意力机制，助力高效微调与上下文长度扩展

发布时间：2024年10月05日

`LLM理论` `人工智能`

> Correlation-Aware Select and Merge Attention for Efficient Fine-Tuning and Context Length Extension

# 摘要

> 长序列建模对大规模模型至关重要，但扩展现有架构以处理更长序列面临技术和资源挑战。本文提出了一种高效灵活的注意力架构，能在减少计算资源和微调时间的情况下，扩展大型语言模型的上下文长度。我们引入了相关性感知的选择和合并机制，以及一种新颖的位置编码数据增强技术，以增强泛化能力。实验结果显示，使用单个 A100 在 Llama2-7B 上进行 32K 序列长度的微调，效率优于其他方法。我们还提出了一种全面的方法，用于在预训练、微调和推理阶段扩展上下文长度。在预训练中，我们的注意力机制部分打破了平移不变性，仅对选定标记应用位置编码，实现了高外推能力。对于微调，我们引入了 CRD NTK 位置嵌入，使 Llama2-7B 和 Mistral-7B 等模型能在高达 1M 甚至任意长度的上下文长度下进行推理。我们的方法在 4M 上下文长度的 passkey 任务中达到 100% 准确率，并在 1M 上下文长度下保持稳定困惑度，资源需求至少减少 64 倍，性能依然出色。

> Modeling long sequences is crucial for various large-scale models; however, extending existing architectures to handle longer sequences presents significant technical and resource challenges. In this paper, we propose an efficient and flexible attention architecture that enables the extension of context lengths in large language models with reduced computational resources and fine-tuning time compared to other excellent methods. Specifically, we introduce correlation-aware selection and merging mechanisms to facilitate efficient sparse attention. In addition, we also propose a novel data augmentation technique involving positional encodings to enhance generalization to unseen positions. The results are as follows: First, using a single A100, we achieve fine-tuning on Llama2-7B with a sequence length of 32K, which is more efficient than other methods that rely on subsets for regression. Second, we present a comprehensive method for extending context lengths across the pre-training, fine-tuning, and inference phases. During pre-training, our attention mechanism partially breaks translation invariance during token selection, so we apply positional encodings only to the selected tokens. This approach achieves relatively high performance and significant extrapolation capabilities. For fine-tuning, we introduce Cyclic, Randomly Truncated, and Dynamically Growing NTK Positional Embedding (CRD NTK). This design allows fine-tuning with a sequence length of only 16K, enabling models such as Llama2-7B and Mistral-7B to perform inference with context lengths of up to 1M or even arbitrary lengths. Our method achieves 100\% accuracy on the passkey task with a context length of 4M and maintains stable perplexity at a 1M context length. This represents at least a 64-fold reduction in resource requirements compared to traditional full-attention mechanisms, while still achieving competitive performance.

[Arxiv](https://arxiv.org/abs/2410.04211)