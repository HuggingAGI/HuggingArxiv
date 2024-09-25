# 混沌系统的零-shot 预测

发布时间：2024年09月24日

`LLM应用` `时间序列预测` `混沌系统`

> Zero-shot forecasting of chaotic systems

# 摘要

> 时间序列预测传统上需要为特定任务定制的专用模型。然而，最近基于大型语言模型的成功，预训练于多领域海量时间序列数据的基础模型崭露头角，成为通用时间序列预测的希望之星。这些模型的独特之处在于其零-shot 学习能力，即无需重新训练或微调，仅凭有限数据即可预测新系统。我们探索了这一能力是否适用于混沌系统的预测。在 135 个混沌系统中，基础模型在数据有限时表现出色，与定制模型（如 NBEATS、TiDE）不相上下。更引人注目的是，即使点预测失败，基础模型仍能保留混沌吸引子的几何和统计特性，揭示了其对混沌系统长期行为的深刻理解。这不仅展示了基础模型的潜力，也揭示了其在零-shot 预测中的挑战。

> Time-series forecasting is a challenging task that traditionally requires specialized models custom-trained for the specific task at hand. Recently, inspired by the success of large language models, foundation models pre-trained on vast amounts of time-series data from diverse domains have emerged as a promising candidate for general-purpose time-series forecasting. The defining characteristic of these foundation models is their ability to perform zero-shot learning, that is, forecasting a new system from limited context data without explicit re-training or fine-tuning. Here, we evaluate whether the zero-shot learning paradigm extends to the challenging task of forecasting chaotic systems. Across 135 distinct chaotic dynamical systems and $10^8$ timepoints, we find that foundation models produce competitive forecasts compared to custom-trained models (including NBEATS, TiDE, etc.), particularly when training data is limited. Interestingly, even after point forecasts fail, foundation models preserve the geometric and statistical properties of the chaotic attractors, demonstrating a surprisingly strong ability to capture the long-term behavior of chaotic dynamical systems. Our results highlight the promises and pitfalls of foundation models in making zero-shot forecasts of chaotic systems.

[Arxiv](https://arxiv.org/abs/2409.15771)