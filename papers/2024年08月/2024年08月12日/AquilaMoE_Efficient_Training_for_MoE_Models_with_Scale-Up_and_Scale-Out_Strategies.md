# AquilaMoE 采用规模扩大与外扩策略，高效训练 MoE 模型。

发布时间：2024年08月12日

`LLM理论` `人工智能` `语言模型`

> AquilaMoE: Efficient Training for MoE Models with Scale-Up and Scale-Out Strategies

# 摘要

> 随着大型语言模型在多领域的广泛应用，其规模与预训练资源需求同步激增。本文中，我们推出了AquilaMoE，一款前沿的双语8*16B专家混合语言模型，每个专家拥有160亿参数，采用创新的EfficientScale训练法。该方法通过两阶段优化：Scale-Up阶段利用小模型权重初始化大模型，大幅减少数据需求；Scale-Out阶段则用密集模型初始化MoE专家，强化知识与性能。实验证明，此方案在持续预训练中有效维持并降低损失，显著提升16B及8*16B模型的性能与训练效率。

> In recent years, with the rapid application of large language models across various fields, the scale of these models has gradually increased, and the resources required for their pre-training have grown exponentially. Training an LLM from scratch will cost a lot of computation resources while scaling up from a smaller model is a more efficient approach and has thus attracted significant attention. In this paper, we present AquilaMoE, a cutting-edge bilingual 8*16B Mixture of Experts (MoE) language model that has 8 experts with 16 billion parameters each and is developed using an innovative training methodology called EfficientScale. This approach optimizes performance while minimizing data requirements through a two-stage process. The first stage, termed Scale-Up, initializes the larger model with weights from a pre-trained smaller model, enabling substantial knowledge transfer and continuous pretraining with significantly less data. The second stage, Scale-Out, uses a pre-trained dense model to initialize the MoE experts, further enhancing knowledge transfer and performance. Extensive validation experiments on 1.8B and 7B models compared various initialization schemes, achieving models that maintain and reduce loss during continuous pretraining. Utilizing the optimal scheme, we successfully trained a 16B model and subsequently the 8*16B AquilaMoE model, demonstrating significant improvements in performance and training efficiency.

[Arxiv](https://arxiv.org/abs/2408.06567)