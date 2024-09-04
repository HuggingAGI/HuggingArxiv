# 对齐调优是否会动摇LLMs的内部信心？

发布时间：2024年08月31日

`LLM理论` `人工智能` `机器学习`

> Does Alignment Tuning Really Break LLMs' Internal Confidence?

# 摘要

> 尽管大型语言模型 (LLM) 取得了显著进展，但其现实应用需依赖可靠校准。本研究从模型、校准指标、任务和置信度提取方法四个维度，全面剖析了 LLM 的校准退化问题。初步分析表明，对齐与校准并非总是此消彼长，但在更严格的条件下，对齐过程却持续损害校准效果。因此，我们需谨慎评估模型置信度与校准误差，并探索未来算法，以助力 LLM 在遵循指令的同时，实现精准校准，两者兼得。

> Large Language Models (LLMs) have shown remarkable progress, but their real-world application necessitates reliable calibration. This study conducts a comprehensive analysis of calibration degradation of LLMs across four dimensions: models, calibration metrics, tasks, and confidence extraction methods. Initial analysis showed that the relationship between alignment and calibration is not always a trade-off, but under stricter analysis conditions, we found the alignment process consistently harms calibration. This highlights the need for (1) a careful approach when measuring model confidences and calibration errors and (2) future research into algorithms that can help LLMs to achieve both instruction-following and calibration without sacrificing either.

[Arxiv](https://arxiv.org/abs/2409.00352)