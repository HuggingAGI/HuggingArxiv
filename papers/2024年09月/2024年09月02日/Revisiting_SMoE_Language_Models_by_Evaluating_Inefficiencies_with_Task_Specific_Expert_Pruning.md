# 重新审视SMoE语言模型，通过任务特定专家修剪评估其效率不足之处。

发布时间：2024年09月02日

`LLM理论` `人工智能` `软件工程`

> Revisiting SMoE Language Models by Evaluating Inefficiencies with Task Specific Expert Pruning

# 摘要

> SMoE模型作为语言建模中密集模型的可扩展替代方案崭露头角。这些模型通过在transformer块中使用条件激活的前馈子网络，实现了模型参数与计算的分离。然而，大型token路由的SMoE模型在推理时需使用整个模型，导致分布式环境中的高延迟，削弱了稀疏激活的优势。我们的研究通过特定任务的模型剪枝，指导SMoE架构设计，特别是预训练中专家数量的选择。我们探讨了剪枝模型在任务评估中是否优于从头训练的小型SMoE模型。为此，我们提出了UNCURL技术，离线减少MoE层中的专家数量。研究发现，剪枝因子存在阈值，超过此阈值将影响模型性能，这一发现对预训练SMoE架构的模型设计具有重要意义，尤其是在后期任务特定推理优化方面。

> Sparse Mixture of Expert (SMoE) models have emerged as a scalable alternative to dense models in language modeling. These models use conditionally activated feedforward subnetworks in transformer blocks, allowing for a separation between total model parameters and per-example computation. However, large token-routed SMoE models face a significant challenge: during inference, the entire model must be used for a sequence or a batch, resulting in high latencies in a distributed setting that offsets the advantages of per-token sparse activation. Our research explores task-specific model pruning to inform decisions about designing SMoE architectures, mainly modulating the choice of expert counts in pretraining. We investigate whether such pruned models offer advantages over smaller SMoE models trained from scratch, when evaluating and comparing them individually on tasks. To that end, we introduce an adaptive task-aware pruning technique UNCURL to reduce the number of experts per MoE layer in an offline manner post-training. Our findings reveal a threshold pruning factor for the reduction that depends on the number of experts used in pretraining, above which, the reduction starts to degrade model performance. These insights contribute to our understanding of model design choices when pretraining with SMoE architectures, particularly useful when considering task-specific inference optimization for later stages.

[Arxiv](https://arxiv.org/abs/2409.01483)