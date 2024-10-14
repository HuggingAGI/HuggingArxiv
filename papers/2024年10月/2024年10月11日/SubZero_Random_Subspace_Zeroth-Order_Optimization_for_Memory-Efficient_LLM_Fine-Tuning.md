# SubZero：一种随机子空间零阶优化方法，专为高效内存的大型语言模型微调设计。

发布时间：2024年10月11日

`LLM理论` `机器学习`

> SubZero: Random Subspace Zeroth-Order Optimization for Memory-Efficient LLM Fine-Tuning

# 摘要

> 微调大型语言模型 (LLM) 对多种下游任务效果显著，但随着模型规模增大，反向传播的内存需求也急剧增加。零阶 (ZO) 优化方法通过前向传递估计梯度，虽节省内存，但梯度估计的方差随模型参数维度线性增长，对 LLM 构成挑战。为此，我们提出随机子空间零阶 (SubZero) 优化，引入专为 LLM 设计的低秩扰动，大幅降低内存消耗并提升训练性能。我们还证明，SubZero 的梯度估计接近反向传播梯度，方差更低，且与 SGD 结合时确保收敛。实验显示，SubZero 在多种语言建模任务中表现优异，收敛速度超越传统 ZO 方法如 MeZO。

> Fine-tuning Large Language Models (LLMs) has proven effective for a variety of downstream tasks. However, as LLMs grow in size, the memory demands for backpropagation become increasingly prohibitive. Zeroth-order (ZO) optimization methods offer a memory-efficient alternative by using forward passes to estimate gradients, but the variance of gradient estimates typically scales linearly with the model's parameter dimension$\unicode{x2013}$a significant issue for LLMs. In this paper, we propose the random Subspace Zeroth-order (SubZero) optimization to address the challenges posed by LLMs' high dimensionality. We introduce a low-rank perturbation tailored for LLMs that significantly reduces memory consumption while improving training performance. Additionally, we prove that our gradient estimation closely approximates the backpropagation gradient, exhibits lower variance than traditional ZO methods, and ensures convergence when combined with SGD. Experimental results show that SubZero enhances fine-tuning performance and achieves faster convergence compared to standard ZO approaches like MeZO across various language modeling tasks.

[Arxiv](https://arxiv.org/abs/2410.08989)