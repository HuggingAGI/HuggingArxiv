# 稀疏自编码器能否用于分解和解释转向向量？

发布时间：2024年11月13日

`LLM理论` `语言模型` `向量操纵`

> Can sparse autoencoders be used to decompose and interpret steering vectors?

# 摘要

> 操纵向量是控制大型语言模型行为的一种有前途的方法。然而，其潜在机制仍知之甚少。虽然稀疏自动编码器（SAEs）可能提供一种解释操纵向量的潜在方法，但最近的研究结果表明，SAE 重建的向量往往缺乏原始向量的操纵特性。本文研究了为什么直接将 SAEs 应用于操纵向量会产生误导性的分解，确定了两个原因：（1）操纵向量不在 SAEs 设计的输入分布范围内，（2）操纵向量在特征方向上可能有有意义的负投影，而 SAEs 未设计容纳这些。这些限制阻碍了 SAEs 直接用于解释操纵向量。

> Steering vectors are a promising approach to control the behaviour of large language models. However, their underlying mechanisms remain poorly understood. While sparse autoencoders (SAEs) may offer a potential method to interpret steering vectors, recent findings show that SAE-reconstructed vectors often lack the steering properties of the original vectors. This paper investigates why directly applying SAEs to steering vectors yields misleading decompositions, identifying two reasons: (1) steering vectors fall outside the input distribution for which SAEs are designed, and (2) steering vectors can have meaningful negative projections in feature directions, which SAEs are not designed to accommodate. These limitations hinder the direct use of SAEs for interpreting steering vectors.

[Arxiv](https://arxiv.org/abs/2411.08790)