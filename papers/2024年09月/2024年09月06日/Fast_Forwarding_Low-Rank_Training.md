# 加速低秩训练进程

发布时间：2024年09月06日

`LLM理论` `机器学习`

> Fast Forwarding Low-Rank Training

# 摘要

> 低秩适应 (LoRA) 等参数高效微调方法旨在降低预训练语言模型 (LM) 的微调成本。在此基础上，我们提出了一种更高效的优化策略：快速前进 (Fast Forward)。该方法通过重复最近的优化步骤，直到损失在微小验证集上不再改善，从而加速训练。通过在常规优化和快速前进阶段之间交替，快速前进可将 FLOPs 减少 87%，训练时间减少 81%，优于标准 Adam 优化器。我们在不同任务上微调多种模型，验证了快速前进在不牺牲性能的前提下加速训练的效果。此外，我们还探讨了快速前进的最佳应用时机和方法。

> Parameter efficient finetuning methods like low-rank adaptation (LoRA) aim to reduce the computational costs of finetuning pretrained Language Models (LMs). Enabled by these low-rank settings, we propose an even more efficient optimization strategy: Fast Forward, a simple and effective approach to accelerate large segments of training. In a Fast Forward stage, we repeat the most recent optimizer step until the loss stops improving on a tiny validation set. By alternating between regular optimization steps and Fast Forward stages, Fast Forward provides up to an 87\% reduction in FLOPs and up to an 81\% reduction in train time over standard SGD with Adam. We validate Fast Forward by finetuning various models on different tasks and demonstrate that it speeds up training without compromising model performance. Additionally, we analyze when and how to apply Fast Forward.

[Arxiv](https://arxiv.org/abs/2409.04206)