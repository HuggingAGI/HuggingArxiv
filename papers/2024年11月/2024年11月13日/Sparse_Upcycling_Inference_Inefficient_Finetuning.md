# 稀疏升级利用：低效的推理微调

发布时间：2024年11月13日

`LLM应用` `人工智能` `模型训练`

> Sparse Upcycling: Inference Inefficient Finetuning

# 摘要

> 小型且经过高度训练的开源大型语言模型因推理效率高而被广泛运用，但其质量的进一步提升仍是难题。稀疏升级是一种颇具前景的方式，能将预先训练的密集模型转变为专家混合（MoE）架构，从而增加模型的参数数量和质量。在本项工作中，我们针对不同的模型规模、计算预算以及预训练时长，对稀疏升级和持续预训练（CPT）的效果进行了比较。我们的实验显示，稀疏升级能够达到更优的质量，在某些情形下相对CPT有超20%的提升。不过，这也带来了显著的推理成本，致使较大模型在高需求推理场景中减速40%。我们的发现凸显了模型质量与推理效率之间的权衡，为试图平衡模型质量和部署限制的从业者提供了参考。

> Small, highly trained, open-source large language models are widely used due to their inference efficiency, but further improving their quality remains a challenge. Sparse upcycling is a promising approach that transforms a pretrained dense model into a Mixture-of-Experts (MoE) architecture, increasing the model's parameter count and quality. In this work, we compare the effectiveness of sparse upcycling against continued pretraining (CPT) across different model sizes, compute budgets, and pretraining durations. Our experiments show that sparse upcycling can achieve better quality, with improvements of over 20% relative to CPT in certain scenarios. However, this comes with a significant inference cost, leading to 40% slowdowns in high-demand inference settings for larger models. Our findings highlight the trade-off between model quality and inference efficiency, offering insights for practitioners seeking to balance model quality and deployment constraints.

[Arxiv](https://arxiv.org/abs/2411.08968)