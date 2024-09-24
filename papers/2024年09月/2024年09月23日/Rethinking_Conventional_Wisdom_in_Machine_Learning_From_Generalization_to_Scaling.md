# 颠覆机器学习传统观念：从泛化迈向扩展

发布时间：2024年09月23日

`LLM理论` `机器学习` `人工智能`

> Rethinking Conventional Wisdom in Machine Learning: From Generalization to Scaling

# 摘要

> 大型语言预训练的成功和缩放定律的发现，标志着机器学习范式的重大转变。主要目标已从减少泛化误差转向降低近似误差，策略也从正则化转向模型扩展。这引发了一个关键问题：在泛化主导的时代，那些成功的原则是否在新的缩放时代依然有效？本文探讨了在大型语言模型时代可能不再适用的几种正则化原则，包括显式L2正则化和通过小批量、大学习率实现的隐式正则化。此外，我们发现了一种名为“缩放定律交叉”的现象，即两条缩放曲线在特定尺度上相交，表明小尺度上有效的方法在大尺度上可能失效。这些观察引出了两个核心问题：$\bullet$ 缩放的指导原则：在正则化不再是主导原则的情况下，哪些新原则正在指导模型扩展？$\bullet$ 模型在规模上的比较：如何在仅能进行单一实验的规模上，可靠且有效地比较模型？

> The remarkable success of large language pretraining and the discovery of scaling laws signify a paradigm shift in machine learning. Notably, the primary objective has evolved from minimizing generalization error to reducing approximation error, and the most effective strategy has transitioned from regularization (in a broad sense) to scaling up models. This raises a critical question:
  Do the established principles that proved successful in the generalization-centric era remain valid in this new era of scaling?
  This paper examines several influential regularization-based principles that may no longer hold true in the scaling-centric, large language model (LLM) era. These principles include explicit L2 regularization and implicit regularization through small batch sizes and large learning rates. Additionally, we identify a new phenomenon termed ``scaling law crossover,'' where two scaling curves intersect at a certain scale, implying that methods effective at smaller scales may not generalize to larger ones. Together, these observations highlight two fundamental questions within this new paradigm:
  $\bullet$ Guiding Principles for Scaling: If regularization is no longer the primary guiding principle for model design, what new principles are emerging to guide scaling?
  $\bullet$ Model Comparison at Scale: How to reliably and effectively compare models at the scale where only a single experiment is feasible?

[Arxiv](https://arxiv.org/abs/2409.15156)