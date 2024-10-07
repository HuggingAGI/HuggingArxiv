# 通过分数优化简化保形信息检索

发布时间：2024年10月03日

`RAG` `信息检索` `数据分析`

> Streamlining Conformal Information Retrieval via Score Refinement

# 摘要

> 信息检索方法，如检索增强生成，虽是现代应用的基石，却常缺乏统计保障。保形预测虽能确保检索集合包含相关信息，但现有方法生成的集合庞大，计算成本高且响应缓慢。我们提出一种评分优化方法，通过简单的单调变换，既缩小了保形集合的规模，又保持了其统计可靠性。实验证明，我们的方法在生成紧凑且相关信息丰富的集合方面表现出色。

> Information retrieval (IR) methods, like retrieval augmented generation, are fundamental to modern applications but often lack statistical guarantees. Conformal prediction addresses this by retrieving sets guaranteed to include relevant information, yet existing approaches produce large-sized sets, incurring high computational costs and slow response times. In this work, we introduce a score refinement method that applies a simple monotone transformation to retrieval scores, leading to significantly smaller conformal sets while maintaining their statistical guarantees. Experiments on various BEIR benchmarks validate the effectiveness of our approach in producing compact sets containing relevant information.

[Arxiv](https://arxiv.org/abs/2410.02914)