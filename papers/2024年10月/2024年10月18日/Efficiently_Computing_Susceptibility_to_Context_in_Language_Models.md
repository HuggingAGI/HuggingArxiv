# 高效测算语言模型的上下文敏感度

发布时间：2024年10月18日

`LLM理论` `人工智能`

> Efficiently Computing Susceptibility to Context in Language Models

# 摘要

> 现代语言模型的一大优势在于，它们能够巧妙地结合用户输入的上下文信息来回答问题。然而，这些模型对上下文细微变化的敏感度却参差不齐。Du 等人 (2024) 为此提出了一种信息论度量——易感性，用以衡量模型对上下文变化的敏感程度。尽管定义明确，但精确计算易感性却颇具挑战，因此他们转而采用蒙特卡罗近似法。然而，这种方法因样本需求量大而显得效率低下。为此，我们引入了 Fisher 易感性，一种基于 Fisher 信息的高效估计方法。实证结果显示，尽管速度提升了 70 倍，Fisher 易感性在各类查询领域中的表现仍与蒙特卡罗估计相当。借助这一高效工具，我们进一步分析了影响语言模型易感性的因素，发现大小模型在这方面的表现并无显著差异。

> One strength of modern language models is their ability to incorporate information from a user-input context when answering queries. However, they are not equally sensitive to the subtle changes to that context. To quantify this, Du et al. (2024) gives an information-theoretic metric to measure such sensitivity. Their metric, susceptibility, is defined as the degree to which contexts can influence a model's response to a query at a distributional level. However, exactly computing susceptibility is difficult and, thus, Du et al. (2024) falls back on a Monte Carlo approximation. Due to the large number of samples required, the Monte Carlo approximation is inefficient in practice. As a faster alternative, we propose Fisher susceptibility, an efficient method to estimate the susceptibility based on Fisher information. Empirically, we validate that Fisher susceptibility is comparable to Monte Carlo estimated susceptibility across a diverse set of query domains despite its being $70\times$ faster. Exploiting the improved efficiency, we apply Fisher susceptibility to analyze factors affecting the susceptibility of language models. We observe that larger models are as susceptible as smaller ones.

[Arxiv](https://arxiv.org/abs/2410.14361)