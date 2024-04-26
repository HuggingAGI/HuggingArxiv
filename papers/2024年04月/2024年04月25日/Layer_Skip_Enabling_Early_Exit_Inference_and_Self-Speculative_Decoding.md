# 层跃技术：让模型在推理时能够提前退出，并进行自我推测性解码。

发布时间：2024年04月25日

`LLM应用` `机器学习`

> Layer Skip: Enabling Early Exit Inference and Self-Speculative Decoding

# 摘要

> 我们介绍了 LayerSkip，这是一种全新的端到端方法，旨在提升大型语言模型（LLMs）推理效率。在训练阶段，我们实施了层级丢弃策略，早期层的丢弃率较低，而后期层的丢弃率较高，并引入了所有变换层共用的早期退出损失。在推理阶段，我们发现这种方法能够提高早期层的退出准确性，且无需额外增加任何辅助层或模块。此外，我们还提出了一种创新的自我推测解码技术，该技术允许我们在早期层进行退出，并通过模型的后续层进行验证和修正。与传统推测解码方法相比，我们的自我推测解码技术内存占用更少，且能够利用草稿和验证阶段的共享计算和激活。我们在不同规模的 Llama 模型上进行了实验，包括从零开始的预训练、持续预训练、特定数据领域的微调以及特定任务的微调。我们的推理解决方案在 CNN/DM 文档摘要任务中实现了最高 2.16 倍的速度提升，在编码任务中提升了 1.82 倍，在 TOPv2 语义解析任务中提升了 2.0 倍。

> We present LayerSkip, an end-to-end solution to speed-up inference of large language models (LLMs). First, during training we apply layer dropout, with low dropout rates for earlier layers and higher dropout rates for later layers, and an early exit loss where all transformer layers share the same exit. Second, during inference, we show that this training recipe increases the accuracy of early exit at earlier layers, without adding any auxiliary layers or modules to the model. Third, we present a novel self-speculative decoding solution where we exit at early layers and verify and correct with remaining layers of the model. Our proposed self-speculative decoding approach has less memory footprint than other speculative decoding approaches and benefits from shared compute and activations of the draft and verification stages. We run experiments on different Llama model sizes on different types of training: pretraining from scratch, continual pretraining, finetuning on specific data domain, and finetuning on specific task. We implement our inference solution and show speedups of up to 2.16x on summarization for CNN/DM documents, 1.82x on coding, and 2.0x on TOPv2 semantic parsing task.

[Arxiv](https://arxiv.org/abs/2404.16710)