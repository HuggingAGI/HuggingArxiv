# MERLOT：一种基于蒸馏大型语言模型的专家混合式框架，用于实现可扩展的加密流量分类

发布时间：2024年11月19日

`LLM应用` `加密流量` `模型蒸馏`

> MERLOT: A Distilled LLM-based Mixture-of-Experts Framework for Scalable Encrypted Traffic Classification

# 摘要

> 我们推出了 MERLOT，这是对用于加密流量分类优化的蒸馏大型语言模型基于可扩展专家混合（MoE）的改进。借助师生范式中的模型蒸馏技术，源自 GPT-2-base 的紧凑模型既能保持高分类准确率，又能最大程度降低计算成本。这些模型在 MoE 架构中充当专门专家，通过门控网络动态分配。和基于生成的方法不同，我们的方法以具有上下文特征嵌入的最终解码器令牌为输入，直接对加密流量进行分类。在 10 个数据集上的实验显示，其性能优于或可与最先进的模型媲美，同时大幅降低了资源需求，彰显了其有效性和稳健性。

> We present MERLOT, a scalable mixture-of-expert (MoE) based refinement of distilled large language model optimized for encrypted traffic classification. By applying model distillation techniques in a teacher-student paradigm, compact models derived from GPT-2-base retain high classification accuracy while minimizing computational costs. These models function as specialized experts in an MoE architecture, dynamically assigned via a gating network. Unlike generation-based methods, our approach directly classifies encrypted traffic using the final decoder token with contextual feature embedding as input. Experiments on 10 datasets show superior or competitive performance over the state-of-the-art models while significantly reducing resource demands, underscoring its effectiveness and robustness.

[Arxiv](https://arxiv.org/abs/2411.13004)