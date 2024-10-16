# 稀疏自编码器能否洞察潜在表示的奥秘？

发布时间：2024年10月15日

`LLM理论` `生物学` `数据科学`

> Can sparse autoencoders make sense of latent representations?

# 摘要

> 稀疏自编码器 (SAE) 最近在揭示大型语言模型的潜在特征方面表现出色。我们进一步探索了其在处理复杂高维生物数据中的潜力，尤其是在底层变量未知的情况下。通过模拟数据，我们发现生成变量可以以叠加形式被捕获，但这种捕获的完整性取决于表示的完整性。若生成变量未知，叠加则难以识别。然而，SAE 仍能在一定程度上恢复这些变量，生成可解释的特征。在单细胞多组学数据的应用中，SAE 成功揭示了如二氧化碳运输和离子稳态等关键生物过程，这对红细胞分化和免疫功能至关重要。这些发现展示了 SAE 在提升生物学及其他科学领域可解释性方面的巨大潜力。

> Sparse autoencoders (SAEs) have lately been used to uncover interpretable latent features in large language models. Here, we explore their potential for decomposing latent representations in complex and high-dimensional biological data, where the underlying variables are often unknown. On simulated data we show that generative hidden variables can be captured in learned representations in the form of superpositions. The degree to which they are learned depends on the completeness of the representations. Superpositions, however, are not identifiable if these generative variables are unknown. SAEs can to some extent recover these variables, yielding interpretable features. Applied to single-cell multi-omics data, we show that an SAE can uncover key biological processes such as carbon dioxide transport and ion homeostasis, which are crucial for red blood cell differentiation and immune function. Our findings highlight how SAEs can be used in advancing interpretability in biological and other scientific domains.

[Arxiv](https://arxiv.org/abs/2410.11468)