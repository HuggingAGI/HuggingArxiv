# 本研究旨在探索如何使 LLM 既高效又具备弹性，通过比较分析其效率、性能及对抗性鲁健性，以期达到更优的综合表现。

发布时间：2024年08月08日

`LLM理论` `人工智能` `网络安全`

> Towards Resilient and Efficient LLMs: A Comparative Study of Efficiency, Performance, and Adversarial Robustness

# 摘要

> 随着大型语言模型 (LLM) 应用需求的日益增长，众多高效注意力模型应运而生，旨在平衡性能与计算成本。然而，这些模型的对抗鲁棒性研究尚显不足。本研究通过对比 Transformer++、GLA Transformer 和 MatMul-Free LM 这三款复杂度与效率各异的模型，利用 GLUE 与 AdvGLUE 数据集，探究了 LLM 在效率、性能与对抗鲁棒性之间的权衡。AdvGLUE 数据集通过引入对抗样本，对模型鲁棒性提出了挑战。研究结果表明，尽管 GLA Transformer 与 MatMul-Free LM 在 GLUE 任务上的准确性稍逊一筹，但在 AdvGLUE 任务中，它们不仅效率更高，且在抵御不同级别攻击时展现出更强的鲁健性。这些发现凸显了简化架构在实现效率、性能与对抗鲁健性平衡方面的潜力，为资源受限且需抵御对抗攻击的应用领域提供了重要启示。

> With the increasing demand for practical applications of Large Language Models (LLMs), many attention-efficient models have been developed to balance performance and computational cost. However, the adversarial robustness of these models remains under-explored. In this work, we design a framework to investigate the trade-off between efficiency, performance, and adversarial robustness of LLMs by comparing three prominent models with varying levels of complexity and efficiency -- Transformer++, Gated Linear Attention (GLA) Transformer, and MatMul-Free LM -- utilizing the GLUE and AdvGLUE datasets. The AdvGLUE dataset extends the GLUE dataset with adversarial samples designed to challenge model robustness. Our results show that while the GLA Transformer and MatMul-Free LM achieve slightly lower accuracy on GLUE tasks, they demonstrate higher efficiency and either superior or comparative robustness on AdvGLUE tasks compared to Transformer++ across different attack levels. These findings highlight the potential of simplified architectures to achieve a compelling balance between efficiency, performance, and adversarial robustness, offering valuable insights for applications where resource constraints and resilience to adversarial attacks are critical.

[Arxiv](https://arxiv.org/abs/2408.04585)