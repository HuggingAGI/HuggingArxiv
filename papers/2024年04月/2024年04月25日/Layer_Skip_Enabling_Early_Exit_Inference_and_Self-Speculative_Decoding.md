# 层级跃迁：实现快速退出推理与自我推测性解码

发布时间：2024年04月25日

`LLM应用` `计算优化`

> Layer Skip: Enabling Early Exit Inference and Self-Speculative Decoding

# 摘要

> 我们推出了 LayerSkip，这是一种端到端的优化方法，旨在提高大型语言模型（LLMs）的推理效率。在训练阶段，我们采取了层间丢弃策略，早期层的丢弃率较低，而后期层的丢弃率较高，同时引入了所有变换层共享的早期退出损失。在推理阶段，我们发现这种方法能够在不增加任何辅助层或模块的情况下，提升早期层的退出准确性。此外，我们还提出了一种创新的自我推测解码策略，该策略允许我们在早期层进行退出，并通过模型的后续层进行验证和修正。与传统推测解码方法相比，我们的策略内存占用更少，并且能够利用草稿和验证阶段的共享计算和激活。我们在不同规模的 Llama 模型上进行了实验，包括从零开始的预训练、持续预训练、特定数据域的微调以及特定任务的微调。我们实现了这一推理方案，并在 CNN/DM 文档摘要任务上实现了最高达 2.16 倍的速度提升，在编码任务上为 1.82 倍，在 TOPv2 语义解析任务上达到了 2.0 倍的速度提升。

> We present LayerSkip, an end-to-end solution to speed-up inference of large language models (LLMs). First, during training we apply layer dropout, with low dropout rates for earlier layers and higher dropout rates for later layers, and an early exit loss where all transformer layers share the same exit. Second, during inference, we show that this training recipe increases the accuracy of early exit at earlier layers, without adding any auxiliary layers or modules to the model. Third, we present a novel self-speculative decoding solution where we exit at early layers and verify and correct with remaining layers of the model. Our proposed self-speculative decoding approach has less memory footprint than other speculative decoding approaches and benefits from shared compute and activations of the draft and verification stages. We run experiments on different Llama model sizes on different types of training: pretraining from scratch, continual pretraining, finetuning on specific data domain, and finetuning on specific task. We implement our inference solution and show speedups of up to 2.16x on summarization for CNN/DM documents, 1.82x on coding, and 2.0x on TOPv2 semantic parsing task.

[Arxiv](https://arxiv.org/abs/2404.16710)