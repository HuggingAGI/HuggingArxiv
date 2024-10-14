# 高效微调状态空间模型中的参数

发布时间：2024年10月11日

`LLM理论` `人工智能`

> Parameter-Efficient Fine-Tuning of State Space Models

# 摘要

> 深度状态空间模型（如 Mamba）在语言建模中表现出色，但参数高效微调（PEFT）在 SSM 模型中的应用仍待探索。本文探讨了两个核心问题：现有 PEFT 方法在 SSM 模型上的表现，以及哪些模块微调效果最佳。通过实证研究，我们发现基于提示的方法（如前缀微调）在 SSM 模型上不再有效，而 LoRA 依然表现出色。进一步研究发现，将 LoRA 应用于线性投影矩阵而不修改 SSM 模块效果最佳。为进一步提升性能，我们提出了选择性维度调整的 LoRA（SDLoRA），在保持线性投影矩阵微调的同时，选择性更新 SSM 模块的特定通道和状态。实验结果显示，SDLoRA 优于标准 LoRA。

> Deep State Space Models (SSMs), such as Mamba (Gu & Dao, 2024), have emerged as powerful tools for language modeling, offering high performance with efficient inference and linear scaling in sequence length. However, the application of parameter-efficient fine-tuning (PEFT) methods to SSM-based models remains largely unexplored. This paper aims to systematically study two key questions: (i) How do existing PEFT methods perform on SSM-based models? (ii) Which modules are most effective for fine-tuning? We conduct an empirical benchmark of four basic PEFT methods on SSM-based models. Our findings reveal that prompt-based methods (e.g., prefix-tuning) are no longer effective, an empirical result further supported by theoretical analysis. In contrast, LoRA remains effective for SSM-based models. We further investigate the optimal application of LoRA within these models, demonstrating both theoretically and experimentally that applying LoRA to linear projection matrices without modifying SSM modules yields the best results, as LoRA is not effective at tuning SSM modules. To further improve performance, we introduce LoRA with Selective Dimension tuning (SDLoRA), which selectively updates certain channels and states on SSM modules while applying LoRA to linear projection matrices. Extensive experimental results show that this approach outperforms standard LoRA.

[Arxiv](https://arxiv.org/abs/2410.09016)