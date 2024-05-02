# SPAFIT：为预训练的大型语言模型量身定制的分层渐进式微调策略

发布时间：2024年04月30日

`分类：LLM理论` `机器学习`

> SPAFIT: Stratified Progressive Adaptation Fine-tuning for Pre-trained Large Language Models

# 摘要

> 全参数微调是适配基于 Transformer 的预训练大型语言模型至特定下游任务的常用方法，但其对计算资源和存储空间的巨大需求限制了其普及。Transformer 架构中出现的灾难性遗忘和过参数化问题，促使研究者探索更高效的微调技术。诸如 LoRA 和 BitFit 等常见的参数高效微调技术一般会应用于模型的所有层次。我们提出了一种新的参数高效微调方法——分层渐进适应微调（SPAFIT），它根据语言知识的类型将其定位到模型的特定层次。在 GLUE 基准测试的九项任务中进行的实验显示，SPAFIT 方法在仅微调其他方法调整参数的一小部分的情况下，性能超越了其他参数高效微调方法。

> Full fine-tuning is a popular approach to adapt Transformer-based pre-trained large language models to a specific downstream task. However, the substantial requirements for computational power and storage have discouraged its widespread use. Moreover, increasing evidence of catastrophic forgetting and overparameterization in the Transformer architecture has motivated researchers to seek more efficient fine-tuning (PEFT) methods. Commonly known parameter-efficient fine-tuning methods like LoRA and BitFit are typically applied across all layers of the model. We propose a PEFT method, called Stratified Progressive Adaptation Fine-tuning (SPAFIT), based on the localization of different types of linguistic knowledge to specific layers of the model. Our experiments, conducted on nine tasks from the GLUE benchmark, show that our proposed SPAFIT method outperforms other PEFT methods while fine-tuning only a fraction of the parameters adjusted by other methods.

[Arxiv](https://arxiv.org/abs/2405.00201)