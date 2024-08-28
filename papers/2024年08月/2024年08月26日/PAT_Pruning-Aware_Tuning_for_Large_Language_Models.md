# PAT：针对大型语言模型的修剪感知调优

发布时间：2024年08月26日

`LLM理论` `计算机科学` `人工智能`

> PAT: Pruning-Aware Tuning for Large Language Models

# 摘要

> 大型语言模型在语言任务中表现卓越，尤其是在预训练后进行监督微调。然而，其庞大的内存和计算需求限制了实际应用。结构剪枝通过减少不重要的权重维度提供了解决方案，但传统后剪枝常导致显著性能下降。我们提出剪枝感知调优 (PAT) 范式，结合结构剪枝与微调，以最大化消除冗余并保持性能。具体而言，我们在 Attention 和 FFN 间插入混合稀疏化模块 (HSM)，包含轻量级操作符和全局共享可训练掩码，确保剪枝同时保持训练效率。此外，身份损失增强了训练鲁棒性。实验证明，PAT 在性能和效率上均优于传统方法。例如，Llama2-7b 模型在 25% 剪枝率下加速 1.33 倍，准确率提升 1.26%，且训练成本相近。代码：https://github.com/kriskrisliu/PAT_Pruning-Aware-Tuning

> Large language models (LLMs) excel in language tasks, especially with supervised fine-tuning after pre-training. However, their substantial memory and computational requirements hinder practical applications. Structural pruning, which reduces less significant weight dimensions, is one solution. Yet, traditional post-hoc pruning often leads to significant performance loss, with limited recovery from further fine-tuning due to reduced capacity. Since the model fine-tuning refines the general and chaotic knowledge in pre-trained models, we aim to incorporate structural pruning with the fine-tuning, and propose the Pruning-Aware Tuning (PAT) paradigm to eliminate model redundancy while preserving the model performance to the maximum extend. Specifically, we insert the innovative Hybrid Sparsification Modules (HSMs) between the Attention and FFN components to accordingly sparsify the upstream and downstream linear modules. The HSM comprises a lightweight operator and a globally shared trainable mask. The lightweight operator maintains a training overhead comparable to that of LoRA, while the trainable mask unifies the channels to be sparsified, ensuring structural pruning. Additionally, we propose the Identity Loss which decouples the transformation and scaling properties of the HSMs to enhance training robustness. Extensive experiments demonstrate that PAT excels in both performance and efficiency. For example, our Llama2-7b model with a 25\% pruning ratio achieves 1.33$\times$ speedup while outperforming the LoRA-finetuned model by up to 1.26\% in accuracy with a similar training cost. Code: https://github.com/kriskrisliu/PAT_Pruning-Aware-Tuning

[Arxiv](https://arxiv.org/abs/2408.14721)