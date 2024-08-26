# 在调整大型语言模型以适应低资源翻译时，我们面临一个选择：追求数据的质量还是数量？本文探讨了数据规模与多样性在这一过程中的重要性。

发布时间：2024年08月22日

`LLM应用` `机器翻译` `低资源语言`

> Quality or Quantity? On Data Scale and Diversity in Adapting Large Language Models for Low-Resource Translation

# 摘要

> 尽管 LLM 在 MT 领域颇受欢迎，但在低资源翻译方面，其表现仍不及 NMT 模型。本文探讨了如何使 LLM 适应低资源环境，特别关注了平行数据的重要性和 SFT 中的多样性这两个因素。近期研究表明，在 LLM 驱动的 MT 中，平行数据的重要性有所下降，而 SFT 中的多样性则有助于 LLM 在不同语言和任务间的迁移。然而，对于低资源 LLM-MT，我们发现情况相反：平行数据在预训练和 SFT 中至关重要，而多样性则可能引发干扰而非迁移。通过涉及 3 个 LLM 模型和 2 个低资源语言组的实验，我们揭示了这些模式的一致性，凸显了研究结果的普遍性。这些发现对于构建能够有效支持低资源语言的大规模多语言 LLM-MT 模型具有重要价值。

> Despite the recent popularity of Large Language Models (LLMs) in Machine Translation (MT), their performance in low-resource translation still lags significantly behind Neural Machine Translation (NMT) models. In this paper, we explore what it would take to adapt LLMs for low-resource settings. In particular, we re-examine the role of two factors: a) the importance and application of parallel data, and b) diversity in Supervised Fine-Tuning (SFT). Recently, parallel data has been shown to be less important for MT using LLMs than in previous MT research. Similarly, diversity during SFT has been shown to promote significant transfer in LLMs across languages and tasks. However, for low-resource LLM-MT, we show that the opposite is true for both of these considerations: a) parallel data is critical during both pretraining and SFT, and b) diversity tends to cause interference, not transfer. Our experiments, conducted with 3 LLMs across 2 low-resourced language groups - indigenous American and North-East Indian - reveal consistent patterns in both cases, underscoring the generalizability of our findings. We believe these insights will be valuable for scaling to massively multilingual LLM-MT models that can effectively serve lower-resource languages.

[Arxiv](https://arxiv.org/abs/2408.12780)