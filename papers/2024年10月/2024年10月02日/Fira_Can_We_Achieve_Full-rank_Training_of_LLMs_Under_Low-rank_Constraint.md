# Fira：在低秩限制下，我们能否实现 LLM 的全秩训练？

发布时间：2024年10月02日

`LLM理论` `机器学习` `人工智能`

> Fira: Can We Achieve Full-rank Training of LLMs Under Low-rank Constraint?

# 摘要

> 低秩训练是减少 LLM 训练内存消耗的有效方法。传统方法通过分解权重或梯度矩阵来节省内存，但都限制了训练在低秩空间，导致性能受限。本文提出 Fira，一种新的训练框架，旨在在保持低秩约束的同时实现全秩训练，避免性能下降。我们发现自适应优化器在低秩和全秩训练中的梯度范数缩放影响相似，基于此提出基于范数的缩放方法，使低秩优化器替代全秩优化器，实现全秩训练。此外，为解决优化过程中的梯度突增问题，我们引入范数增长限制器平滑梯度。实验证明，Fira 在预训练和微调中均优于现有方法，性能媲美甚至超越全秩训练。

> Low-rank training has emerged as a promising approach for reducing memory usage in training Large Language Models (LLMs). Previous methods either rely on decomposing weight matrices (e.g., LoRA), or seek to decompose gradient matrices (e.g., GaLore) to ensure reduced memory consumption. However, both of them constrain the training in a low-rank subspace, thus inevitably leading to sub-optimal performance. This raises a question: whether it is possible to consistently preserve the low-rank constraint for memory efficiency, while achieving full-rank training (i.e., training with full-rank gradients of full-rank weights) to avoid inferior outcomes? In this paper, we propose a new plug-and-play training framework for LLMs called Fira, as the first attempt to achieve this goal. First, we observe an interesting phenomenon during LLM training: the scaling impact of adaptive optimizers (e.g., Adam) on the gradient norm remains similar from low-rank to full-rank training. Based on this observation, we propose a norm-based scaling method, which utilizes the scaling impact of low-rank optimizers as substitutes for that of original full-rank optimizers to enable full-rank training. In this way, we can preserve the low-rank constraint in the optimizer while achieving full-rank training for better performance. Moreover, we find that there are sudden gradient rises during the optimization process, potentially causing loss spikes. To address this, we further put forward a norm-growth limiter to smooth the gradient via regulating the relative increase of gradient norms. Extensive experiments on the pre-training and fine-tuning of LLMs show that Fira outperforms both LoRA and GaLore, achieving performance that is comparable to or even better than full-rank training.

[Arxiv](https://arxiv.org/abs/2410.01623)