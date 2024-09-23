# OATS：利用稀疏与低秩分解技术，实现对异常值的智能剪枝

发布时间：2024年09月20日

`LLM理论` `计算机科学` `人工智能`

> OATS: Outlier-Aware Pruning Through Sparse and Low Rank Decomposition

# 摘要

> 近年来，深度学习转向大规模基础模型，带来了新的机遇，但也伴随着高昂的内存和计算成本。为解决这一问题，事后神经网络剪枝技术应运而生，无需再训练。尽管进展显著，现有方法在压缩过程中性能往往下降。本文介绍了一种名为OATS的新方法，利用输入嵌入的二阶矩信息，将模型权重分解为稀疏和低秩矩阵之和。无需再训练，OATS在压缩大型语言模型和视觉变压器时，性能达到最先进水平，压缩率高达60%，CPU加速提升1.37倍。

> The recent paradigm shift to large-scale foundation models has brought about a new era for deep learning that, while has found great success in practice, has also been plagued by prohibitively expensive costs in terms of high memory consumption and compute. To mitigate these issues, there has been a concerted effort in post-hoc neural network pruning techniques that do not require costly retraining. Despite the considerable progress being made, existing methods often exhibit a steady drop in model performance as the compression increases. In this paper, we present a novel approach to compressing large transformers, coined OATS, that utilizes the second moment information in the input embeddings to decompose the model weights into a sum of sparse and low-rank matrices. Without any retraining, OATS achieves state-of-the-art performance when compressing models by up to $60\%$ on large language models such as Llama-3 and Phi-3 and vision transformers such as ViT and DINOv2 while delivering up to $1.37\times$ the CPU acceleration versus a model that was comparably pruned.

[Arxiv](https://arxiv.org/abs/2409.13652)