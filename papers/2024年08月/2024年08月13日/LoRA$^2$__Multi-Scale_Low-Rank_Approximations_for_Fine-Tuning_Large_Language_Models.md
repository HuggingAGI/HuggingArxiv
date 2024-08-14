# LoRA$^2$：一种多尺度低秩近似方法，专为微调大型语言模型设计。

发布时间：2024年08月13日

`LLM理论` `人工智能` `计算机科学`

> LoRA$^2$ : Multi-Scale Low-Rank Approximations for Fine-Tuning Large Language Models

# 摘要

> 微调大型语言模型以适应下游任务，采用高参数效率的方法已成为新趋势。LoRA 技术通过减少可训练参数数量，展现了优异性能。然而，在单一尺度内更新参数可能不适用于复杂的下游任务。为此，我们提出了多尺度 LoRA，即 LoRA$^2$，结合正交投影理论，在两个正交平面上训练 LoRA 组。同时，我们优化了重要性分数算法，减少了约 98.5% 的参数敏感性计算。通过修剪低重要性奇异值，增强了模型对多样化下游任务的适应性。实验证明，LoRA$^2$ 在仅保留 0.72% 的可训练参数的情况下，仍能保持卓越性能，甚至在参数进一步减少至 0.17M 时，也能与参数多 8 倍的基线相媲美。代码已公开：https://anonymous.4open.science/r/LoRA-2-5B4C

> Fine-tuning large language models (LLMs) with high parameter efficiency for downstream tasks has become a new paradigm. Low-Rank Adaptation (LoRA) significantly reduces the number of trainable parameters for fine-tuning. Although it has demonstrated commendable performance, updating parameters within a single scale may not be the optimal choice for complex downstream tasks.In this paper, we extend the LoRA to multiple scales, dubbed as LoRA$^2$. We first combine orthogonal projection theory to train a set of LoRAs in two mutually orthogonal planes. Then, we improve the importance score algorithm, which reduce parameter sensitivity score calculations by approximately 98.5\%. By pruning singular values with lower importance scores, thereby enhancing adaptability to various downstream tasks. Extensive experiments are conducted on two widely used pre-trained models to validate the effectiveness of LoRA$^2$. Results show that it significantly reduces the number of trainable parameters to just 0.72\% compared to full fine-tuning, while still delivering highly impressive performance. Even when the parameters are further reduced to 0.17M, it still achieves comparable results to the baseline with 8 times more parameters. Our code is available here: https://anonymous.4open.science/r/LoRA-2-5B4C

[Arxiv](https://arxiv.org/abs/2408.06854)