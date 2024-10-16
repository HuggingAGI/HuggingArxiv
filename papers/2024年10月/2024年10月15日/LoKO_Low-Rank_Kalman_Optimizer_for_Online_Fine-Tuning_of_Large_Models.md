# LoKO：专为大型模型在线微调设计的低秩卡尔曼优化器

发布时间：2024年10月15日

`LLM理论` `机器学习` `优化算法`

> LoKO: Low-Rank Kalman Optimizer for Online Fine-Tuning of Large Models

# 摘要

> 训练大型模型需要巨大的计算成本。参数高效微调 (PEFT) 方法，如低秩适应 (LoRA)，通过仅调整少量参数来适应特定任务，从而解决了这一问题。本文将 PEFT 视为最优滤波问题，并提出了低秩卡尔曼优化器 (LoKO)，以在线方式估计最优参数。我们利用 LoRA 的低秩分解，显著降低了计算复杂度。研究发现，协方差矩阵的初始化和观测噪声的准确估计是关键。实验表明，LoKO 在更少的迭代中收敛，并在图像分类和语言任务中表现优于传统优化器。这为利用卡尔曼滤波器进行大型模型的在线微调提供了新思路。

> Training large models with millions or even billions of parameters from scratch incurs substantial computational costs. Parameter Efficient Fine-Tuning (PEFT) methods, particularly Low-Rank Adaptation (LoRA), address this challenge by adapting only a reduced number of parameters to specific tasks with gradient-based optimizers. In this paper, we cast PEFT as an optimal filtering/state estimation problem and present Low-Rank Kalman Optimizer (LoKO) to estimate the optimal trainable parameters in an online manner. We leverage the low-rank decomposition in LoRA to significantly reduce matrix sizes in Kalman iterations and further capitalize on a diagonal approximation of the covariance matrix to effectively decrease computational complexity from quadratic to linear in the number of trainable parameters. Moreover, we discovered that the initialization of the covariance matrix within the Kalman algorithm and the accurate estimation of the observation noise covariance are the keys in this formulation, and we propose robust approaches that work well across a vast range of well-established computer vision and language models. Our results show that LoKO converges with fewer iterations and yields better performance models compared to commonly used optimizers with LoRA in both image classifications and language tasks. Our study opens up the possibility of leveraging the Kalman filter as an effective optimizer for the online fine-tuning of large models.

[Arxiv](https://arxiv.org/abs/2410.11551)