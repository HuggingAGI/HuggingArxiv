# 大型语言模型超参数优化法则

发布时间：2024年09月07日

`LLM理论` `人工智能` `机器学习`

> Optimization Hyper-parameter Laws for Large Language Models

# 摘要

> 大型语言模型虽推动了AI的重大进步，但其训练资源密集且对超参数选择极为敏感。尽管缩放定律在模型大小和数据需求上提供了宝贵指导，但在动态超参数（如学习率计划）选择上却力有不逮。为此，我们推出了优化超参数定律（Opt-Laws），这一框架能精准捕捉超参数与训练结果的关联，预选潜在最优计划。基于随机微分方程，Opt-Laws不仅带来新颖的数学解释，还为多种流行学习率计划奠定坚实理论基础。跨模型大小与数据规模的广泛验证显示，Opt-Laws能精确预测训练损失，并在预训练、持续训练及微调中精准识别最优学习率计划。此举大幅削减计算开销，同时显著提升模型整体表现。

> Large Language Models have driven significant AI advancements, yet their training is resource-intensive and highly sensitive to hyper-parameter selection. While scaling laws provide valuable guidance on model size and data requirements, they fall short in choosing dynamic hyper-parameters, such as learning-rate (LR) schedules, that evolve during training. To bridge this gap, we present Optimization Hyper-parameter Laws (Opt-Laws), a framework that effectively captures the relationship between hyper-parameters and training outcomes, enabling the pre-selection of potential optimal schedules. Grounded in stochastic differential equations, Opt-Laws introduce novel mathematical interpretability and offer a robust theoretical foundation for some popular LR schedules. Our extensive validation across diverse model sizes and data scales demonstrates Opt-Laws' ability to accurately predict training loss and identify optimal LR schedule candidates in pre-training, continual training, and fine-tuning scenarios. This approach significantly reduces computational costs while enhancing overall model performance.

[Arxiv](https://arxiv.org/abs/2409.04777)