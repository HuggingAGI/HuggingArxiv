# 一种初始化，统领全局：通过解释方差适应实现微调

发布时间：2024年10月09日

`LLM理论` `机器学习` `人工智能`

> One Initialization to Rule them All: Fine-tuning via Explained Variance Adaptation

# 摘要

> 基础模型 (FMs) 在大规模数据集上预训练后，通过低秩适应 (LoRA) 进行微调，以适应特定应用。LoRA 引入了新的权重矩阵，通常随机初始化。最近的研究集中在权重驱动的初始化或训练中的自适应秩学习，但这些方法单独使用时，收敛缓慢且性能次优。我们提出了一种新方法——Explained Variance Adaptation (EVA)，通过数据驱动的奇异值分解初始化权重，优化秩分布，从而提升 LoRA 的性能。EVA 在多种任务中表现出色，收敛更快，平均得分最高。

> Foundation models (FMs) are pre-trained on large-scale datasets and then fine-tuned on a downstream task for a specific application. The most successful and most commonly used fine-tuning method is to update the pre-trained weights via a low-rank adaptation (LoRA). LoRA introduces new weight matrices that are usually initialized at random with a uniform rank distribution across model weights. Recent works focus on weight-driven initialization or learning of adaptive ranks during training. Both approaches have only been investigated in isolation, resulting in slow convergence or a uniform rank distribution, in turn leading to sub-optimal performance. We propose to enhance LoRA by initializing the new weights in a data-driven manner by computing singular value decomposition on minibatches of activation vectors. Then, we initialize the LoRA matrices with the obtained right-singular vectors and re-distribute ranks among all weight matrices to explain the maximal amount of variance and continue the standard LoRA fine-tuning procedure. This results in our new method Explained Variance Adaptation (EVA). We apply EVA to a variety of fine-tuning tasks ranging from language generation and understanding to image classification and reinforcement learning. EVA exhibits faster convergence than competitors and attains the highest average score across a multitude of tasks per domain.

[Arxiv](https://arxiv.org/abs/2410.07170)