# 大型语言模型生成推荐的高效推理

发布时间：2024年10月07日

`LLM应用` `推荐系统` `人工智能`

> Efficient Inference for Large Language Model-based Generative Recommendation

# 摘要

> 基于 LLM 的生成推荐虽已取得显著成功，但高昂的推理延迟使其部署成本高企。推测性解码 (SD) 为无损加速提供了希望，但应用于生成推荐时，需通过束搜索生成前 K 项，导致验证要求更为严格。为此，我们提出 AtSpeed 框架，通过优化前 K 序列对齐和放宽验证策略，显著减少 LLM 调用。实证结果显示，AtSpeed 在严格和宽松验证下分别实现了近 2 倍和最高 2.5 倍的加速。相关代码和数据集即将发布。

> Large Language Model (LLM)-based generative recommendation has achieved notable success, yet its practical deployment is costly particularly due to excessive inference latency caused by autoregressive decoding. For lossless LLM decoding acceleration, Speculative Decoding (SD) has emerged as a promising solution. However, applying SD to generative recommendation presents unique challenges due to the requirement of generating top-K items (i.e., K distinct token sequences) as a recommendation list by beam search. This leads to more stringent verification in SD, where all the top-K sequences from the target LLM must be successfully drafted by the draft model at each decoding step. To alleviate this, we consider 1) boosting top-K sequence alignment between the draft model and the target LLM, and 2) relaxing the verification strategy to reduce trivial LLM calls. To this end, we propose an alignment framework named AtSpeed, which presents the AtSpeed-S optimization objective for top-K alignment under the strict top-K verification. Moreover, we introduce a relaxed sampling verification strategy that allows high-probability non-top-K drafted sequences to be accepted, significantly reducing LLM calls. Correspondingly, we propose AtSpeed-R for top-K alignment under this relaxed sampling verification. Empirical results on two real-world datasets demonstrate that AtSpeed significantly accelerates LLM-based generative recommendation, e.g., near 2x speedup under strict top-K verification and up to 2.5 speedup under relaxed sampling verification. The codes and datasets will be released in the near future.

[Arxiv](https://arxiv.org/abs/2410.05165)