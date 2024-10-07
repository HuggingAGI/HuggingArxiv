# 层次混合专家中的专家估计：探索超越 Softmax 门控函数的新领域

发布时间：2024年10月03日

`LLM理论` `人工智能` `计算机视觉`

> On Expert Estimation in Hierarchical Mixture of Experts: Beyond Softmax Gating Functions

# 摘要

> 随着 MoE 架构在大规模基础模型开发中的日益重要，我们探索了 Hierarchical Mixture of Experts (HMoE)，这是一种专为复杂输入和目标任务性能提升而设计的 MoE 变体。我们的研究发现，采用多样化的门控函数，而非传统的 softmax 门控，能显著提升 HMoE 的效能。理论分析表明，为每个专家组量身定制门控函数，即使在特定层次应用最佳门控，也能确保 HMoE 的稳健表现。实证研究涵盖了多模态任务、图像分类及领域发现预测等，均证实了我们的理论，并展示了改进 HMoE 模型的卓越性能。

> With the growing prominence of the Mixture of Experts (MoE) architecture in developing large-scale foundation models, we investigate the Hierarchical Mixture of Experts (HMoE), a specialized variant of MoE that excels in handling complex inputs and improving performance on targeted tasks. Our investigation highlights the advantages of using varied gating functions, moving beyond softmax gating within HMoE frameworks. We theoretically demonstrate that applying tailored gating functions to each expert group allows HMoE to achieve robust results, even when optimal gating functions are applied only at select hierarchical levels. Empirical validation across diverse scenarios supports these theoretical claims. This includes large-scale multimodal tasks, image classification, and latent domain discovery and prediction tasks, where our modified HMoE models show great performance improvements.

[Arxiv](https://arxiv.org/abs/2410.02935)