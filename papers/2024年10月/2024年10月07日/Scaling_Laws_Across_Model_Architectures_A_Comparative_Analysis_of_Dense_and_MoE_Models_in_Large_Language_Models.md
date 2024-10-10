# 探索大型语言模型中密集模型与MoE模型的扩展规律，进行深入的比较分析。

发布时间：2024年10月07日

`LLM理论` `人工智能` `机器学习`

> Scaling Laws Across Model Architectures: A Comparative Analysis of Dense and MoE Models in Large Language Models

# 摘要

> 大型语言模型 (LLM) 的扩展研究至关重要，涉及模型训练与部署的效率与效果。我们探讨了密集模型与专家混合 (MoE) 模型间扩展定律的转移性与差异。通过理论分析与实验结合，包括损失、批量大小、学习率及资源分配策略的扩展，我们发现幂律扩展框架同样适用于 MoE 模型，揭示了其扩展行为的基本原理。此外，MoE 模型在相同训练计算预算下，测试损失更低，显示出更强的泛化能力。这些发现为优化 MoE 模型的训练与部署策略提供了新视角。

> The scaling of large language models (LLMs) is a critical research area for the efficiency and effectiveness of model training and deployment. Our work investigates the transferability and discrepancies of scaling laws between Dense Models and Mixture of Experts (MoE) models. Through a combination of theoretical analysis and extensive experiments, including consistent loss scaling, optimal batch size and learning rate scaling, and resource allocation strategies scaling, our findings reveal that the power-law scaling framework also applies to MoE Models, indicating that the fundamental principles governing the scaling behavior of these models are preserved, even though the architecture differs. Additionally, MoE Models demonstrate superior generalization, resulting in lower testing losses with the same training compute budget compared to Dense Models. These findings indicate the scaling consistency and transfer generalization capabilities of MoE Models, providing new insights for optimizing MoE Model training and deployment strategies.

[Arxiv](https://arxiv.org/abs/2410.05661)