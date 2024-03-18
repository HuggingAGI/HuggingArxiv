# [为了重新排名 SPLADE 系统，我们深入对比了跨编码器与大型语言模型在该任务中的性能表现。]

发布时间：2024年03月15日

`LLM应用` `搜索引擎`

> A Thorough Comparison of Cross-Encoders and LLMs for Reranking SPLADE

> 本研究对比分析了跨编码器和LLMs两种重排名器在重新排列高效SPLADE检索器时的表现，并在TREC深度学习及BEIR、LoTTE等多个内外部数据集上进行了大规模评测。初步实验揭示，在针对MS MARCO上的SPLADE重排任务时，跨编码器重排名器之间的差异难以辨别。而在外部数据集场景下，模型类型和待重排文档的数量均会对最终效果产生显著影响。接下来，我们重点关注以GPT-4为代表的大规模语言模型驱动的列表式重排名器，尽管GPT-4展现出了卓越的零样本性能，但传统跨编码器仍展现出强大的竞争力。综上所述，我们的研究成果旨在通过对LLM-based重排名器的深入探讨，将其视为衡量搜索系统效能与效率平衡性的又一重要因素，从而为这一领域的热烈讨论提供更为细腻全面的见解。

> We present a comparative study between cross-encoder and LLMs rerankers in the context of re-ranking effective SPLADE retrievers. We conduct a large evaluation on TREC Deep Learning datasets and out-of-domain datasets such as BEIR and LoTTE. In the first set of experiments, we show how cross-encoder rerankers are hard to distinguish when it comes to re-rerank SPLADE on MS MARCO. Observations shift in the out-of-domain scenario, where both the type of model and the number of documents to re-rank have an impact on effectiveness. Then, we focus on listwise rerankers based on Large Language Models -- especially GPT-4. While GPT-4 demonstrates impressive (zero-shot) performance, we show that traditional cross-encoders remain very competitive. Overall, our findings aim to to provide a more nuanced perspective on the recent excitement surrounding LLM-based re-rankers -- by positioning them as another factor to consider in balancing effectiveness and efficiency in search systems.

[Arxiv](https://arxiv.org/abs/2403.10407)