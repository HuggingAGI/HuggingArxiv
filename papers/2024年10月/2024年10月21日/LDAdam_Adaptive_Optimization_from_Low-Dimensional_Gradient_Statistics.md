# LDAdam：基于低维梯度统计的自适应优化

发布时间：2024年10月21日

`LLM理论` `人工智能` `软件开发`

> LDAdam: Adaptive Optimization from Low-Dimensional Gradient Statistics

# 摘要

> 我们推出了 LDAdam，一种专为大型模型设计的内存高效优化器。它通过在低维子空间内进行自适应优化，同时持续探索整个参数空间，从而大幅减少内存占用。LDAdam 采用了一种创新的投影感知更新规则，支持子空间间的灵活转换，并结合了广义误差反馈机制，有效应对低秩投影带来的误差。理论证明和实验结果均显示，LDAdam 在语言模型的微调和预训练中表现出色，既准确又高效。

> We introduce LDAdam, a memory-efficient optimizer for training large models, that performs adaptive optimization steps within lower dimensional subspaces, while consistently exploring the full parameter space during training. This strategy keeps the optimizer's memory footprint to a fraction of the model size. LDAdam relies on a new projection-aware update rule for the optimizer states that allows for transitioning between subspaces, i.e., estimation of the statistics of the projected gradients. To mitigate the errors due to low-rank projection, LDAdam integrates a new generalized error feedback mechanism, which explicitly accounts for both gradient and optimizer state compression. We prove the convergence of LDAdam under standard assumptions, and show that LDAdam allows for accurate and efficient fine-tuning and pre-training of language models.

[Arxiv](https://arxiv.org/abs/2410.16103)