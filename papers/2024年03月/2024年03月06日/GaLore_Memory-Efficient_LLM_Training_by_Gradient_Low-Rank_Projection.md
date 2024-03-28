# GaLore——一种通过梯度低秩投影技术提升大语言模型（LLM）训练内存效率的新方案。

发布时间：2024年03月06日

`LLM理论`

> GaLore: Memory-Efficient LLM Training by Gradient Low-Rank Projection

# 摘要

> 面对大型语言模型(LLMs)训练中的内存难题，关键在于权重和优化器状态的持续增长。现有的一种解决方案——低秩适应(LoRA)，通过向各层预训练权重中插入可训练的低秩矩阵来压缩参数和优化器占用的空间，但这种做法在预训练及微调阶段的表现往往不如全秩权重训练，因为它受限于低秩子空间并影响训练过程的动力学特性，有时甚至需要全秩初始化。为此，本研究提出了“梯度低秩投影”(GaLore)这一训练策略，它在保持全参数学习能力的基础上，比LoRA等传统低秩适应方法更加节省内存资源。实验证明，在使用C4数据集（包含多达19.7B个令牌）对LLaMA 1B和7B架构进行预训练，以及在GLUE任务上对RoBERTa进行微调的过程中，GaLore能有效减少高达65.5%的优化器内存消耗，同时确保了效率和性能。更进一步，相比于BF16基准，8位GaLore可实现优化器内存最多降低82.5%，总训练内存减少63.3%的显著效果。特别值得一提的是，我们首次成功展示了在没有采取模型并行、检查点重加载或卸载策略的情况下，仅使用如NVIDIA RTX 4090这样拥有24GB内存的消费级GPU，就能完成对7B模型的预训练。

> Training Large Language Models (LLMs) presents significant memory challenges, predominantly due to the growing size of weights and optimizer states. Common memory-reduction approaches, such as low-rank adaptation (LoRA), add a trainable low-rank matrix to the frozen pre-trained weight in each layer, reducing trainable parameters and optimizer states. However, such approaches typically underperform training with full-rank weights in both pre-training and fine-tuning stages since they limit the parameter search to a low-rank subspace and alter the training dynamics, and further, may require full-rank warm start. In this work, we propose Gradient Low-Rank Projection (GaLore), a training strategy that allows full-parameter learning but is more memory-efficient than common low-rank adaptation methods such as LoRA. Our approach reduces memory usage by up to 65.5% in optimizer states while maintaining both efficiency and performance for pre-training on LLaMA 1B and 7B architectures with C4 dataset with up to 19.7B tokens, and on fine-tuning RoBERTa on GLUE tasks. Our 8-bit GaLore further reduces optimizer memory by up to 82.5% and total training memory by 63.3%, compared to a BF16 baseline. Notably, we demonstrate, for the first time, the feasibility of pre-training a 7B model on consumer GPUs with 24GB memory (e.g., NVIDIA RTX 4090) without model parallel, checkpointing, or offloading strategies.

[Arxiv](https://arxiv.org/abs/2403.03507)