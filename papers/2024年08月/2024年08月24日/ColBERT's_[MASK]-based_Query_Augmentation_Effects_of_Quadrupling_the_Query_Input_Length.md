# ColBERT 利用 [MASK] 进行查询增强，探讨了将查询输入长度增加四倍的效果。

发布时间：2024年08月24日

`RAG` `搜索引擎`

> ColBERT's [MASK]-based Query Augmentation: Effects of Quadrupling the Query Input Length

# 摘要

> ColBERT的独特之处在于利用[MASK]标记进行查询增强，从而对文档评分。早期研究表明，[MASK]标记会加权非[MASK]查询词，强调某些词而非其他，而非引入新词。我们证实了ColBERTv1中[MASK]标记的词加权行为在ColBERTv2中依然有效。接着，我们探讨了增加[MASK]标记数量对性能的影响，从零增至训练长度的四倍，发现初期性能随[MASK]标记减少而下降，当查询填充至平均32长度时性能显著提升，随后趋于稳定。此外，扩展查询至128标记与基准性能对比，差异微小且统计上不显著，表明ColBERT在处理更多[MASK]标记时性能稳定。

> A unique aspect of ColBERT is its use of [MASK] tokens in queries to score documents (query augmentation). Prior work shows [MASK] tokens weighting non-[MASK] query terms, emphasizing certain tokens over others , rather than introducing whole new terms as initially proposed. We begin by demonstrating that a term weighting behavior previously reported for [MASK] tokens in ColBERTv1 holds for ColBERTv2. We then examine the effect of changing the number of [MASK] tokens from zero to up to four times past the query input length used in training, both for first stage retrieval, and for scoring candidates, observing an initial decrease in performance with few [MASK]s, a large increase when enough [MASK]s are added to pad queries to an average length of 32, then a plateau in performance afterwards. Additionally, we compare baseline performance to performance when the query length is extended to 128 tokens, and find that differences are small (e.g., within 1% on various metrics) and generally statistically insignificant, indicating performance does not collapse if ColBERT is presented with more [MASK] tokens than expected.

[Arxiv](https://arxiv.org/abs/2408.13672)