# 序数偏好优化：借助 NDCG 精准对齐人类偏好

发布时间：2024年10月05日

`LLM理论` `人工智能` `信息检索`

> Ordinal Preference Optimization: Aligning Human Preferences via NDCG

# 摘要

> 将 LLM 与多样的人类偏好对齐，是控制模型行为和提升生成质量的关键。RLHF、DPO 及其变体通过成对比较优化语言模型，但在多响应情况下，未能充分利用排名信息。我们提出序数偏好优化 (OPO)，采用 NDCG 排名指标，更好地利用序数响应的相对接近度。通过可微替代损失近似 NDCG，我们开发了端到端优化算法，连接了信息检索中的排名模型与对齐问题。在多响应数据集上，OPO 在评估集和 AlpacaEval 等基准上优于现有方法。此外，增加负样本池能减少微不足道负样本的负面影响，提升模型性能。

> Aligning Large Language Models (LLMs) with diverse human preferences is a pivotal technique for controlling model behaviors and enhancing generation quality. Reinforcement Learning from Human Feedback (RLHF), Direct Preference Optimization (DPO), and their variants optimize language models by pairwise comparisons. However, when multiple responses are available, these approaches fall short of leveraging the extensive information in the ranking given by the reward models or human feedback. In this work, we propose a novel listwise approach named Ordinal Preference Optimization (OPO), which employs the Normalized Discounted Cumulative Gain (NDCG), a widely-used ranking metric, to better utilize relative proximity within ordinal multiple responses. We develop an end-to-end preference optimization algorithm by approximating NDCG with a differentiable surrogate loss. This approach builds a connection between ranking models in information retrieval and the alignment problem. In aligning multi-response datasets assigned with ordinal rewards, OPO outperforms existing pairwise and listwise approaches on evaluation sets and general benchmarks like AlpacaEval. Moreover, we demonstrate that increasing the pool of negative samples can enhance model performance by reducing the adverse effects of trivial negatives.

[Arxiv](https://arxiv.org/abs/2410.04346)