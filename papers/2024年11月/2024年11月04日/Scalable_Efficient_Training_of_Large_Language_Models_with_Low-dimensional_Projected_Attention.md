# 具有低维投影注意力的大型语言模型的可扩展高效训练

发布时间：2024年11月04日

`LLM理论` `语言模型`

> Scalable Efficient Training of Large Language Models with Low-dimensional Projected Attention

# 摘要

> 同时提高大型语言模型（LLMs）的有效性和效率是一个关键但具有挑战性的研究目标。在本文中，我们发现低秩预训练，通常被认为是会损害性能的有效方法，当精确针对减少的参数时，可以具有可扩展的有效性。具体来说，仅将低维模块应用于注意力层 - 解决了这个问题，并提高了有效性和效率。我们将这种结构称为低维投影注意力（LPA）并提供了一个解释性分析。通过在 130M、370M 的参数规模上进行广泛的实验，并扩展到 3B，我们已经验证了 LPA 的有效性和可扩展性。我们的结果表明，与普通的 Transformer 相比，LPA 模型可以节省高达 12.4％的时间，同时在测试困惑度（ppl）和下游任务中实现约 5％的改进。

> Improving the effectiveness and efficiency of large language models (LLMs) simultaneously is a critical yet challenging research goal. In this paper, we find that low-rank pre-training, normally considered as efficient methods that will compromise performance, can be scalably effective when reduced parameters are precisely targeted. Specifically, applying the low-dimensional module only to the attention layer -- resolves this issue and enhances both effectiveness and efficiency. We refer to this structure as Low-dimensional Projected Attention (LPA) and provide an explanatory analysis. Through extensive experimentation at parameter scales of 130M, 370M, and scaling up to 3B, we have validated the effectiveness and scalability of LPA. Our results show that LPA model can save up to 12.4% in time while achieving an approximate 5% improvement in test perplexity (ppl) and on downstream tasks compared with the vanilla Transformer.

[Arxiv](https://arxiv.org/abs/2411.02063)