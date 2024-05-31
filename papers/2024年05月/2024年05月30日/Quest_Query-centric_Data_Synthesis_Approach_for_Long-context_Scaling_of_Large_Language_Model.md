# 探索：一种以查询为核心的数据合成策略，旨在扩展大型语言模型的长上下文处理能力

发布时间：2024年05月30日

`LLM应用

理由：这篇论文介绍了一种名为Quest的方法，用于合成有效的长上下文数据，以帮助大型语言模型更好地处理长文本。这种方法直接应用于LLM的训练和性能提升，属于LLM的具体应用场景，因此归类为LLM应用。` `数据合成`

> Quest: Query-centric Data Synthesis Approach for Long-context Scaling of Large Language Model

# 摘要

> 大型语言模型通过在扩展上下文的语料库上继续训练，能够更好地处理长文本。然而，长文档在不同领域的稀缺性和分布不均，使得获取有效的长上下文数据颇具挑战。为此，我们提出了名为Quest的查询中心数据合成法。Quest基于观察，发现通过相似查询检索的文档既相关又低冗余，非常适合合成长上下文数据。此方法不仅可解释，还具备可扩展性，能生成大量长上下文数据。利用Quest，我们成功合成了长达128k上下文的数据集，在多个长上下文基准测试中表现卓越。通过规模法则实验，我们进一步证实了Quest方法的可预测性，使其成为推动长上下文模型发展的可靠方案。

> Large language models, initially pre-trained with a limited context length, can better handle longer texts by continuing training on a corpus with extended contexts. However, obtaining effective long-context data is challenging due to the scarcity and uneven distribution of long documents across different domains. To address this issue, we propose a Query-centric data synthesis method, abbreviated as Quest. Quest is an interpretable method based on the observation that documents retrieved by similar queries are relevant but low-redundant, thus well-suited for synthesizing long-context data. The method is also scalable and capable of constructing large amounts of long-context data. Using Quest, we synthesize a long-context dataset up to 128k context length, significantly outperforming other data synthesis methods on multiple long-context benchmark datasets. In addition, we further verify that the Quest method is predictable through scaling law experiments, making it a reliable solution for advancing long-context models.

[Arxiv](https://arxiv.org/abs/2405.19846)