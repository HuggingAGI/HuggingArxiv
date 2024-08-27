# 基于 LLM 的推荐系统是否已登峰造极？其实，通过简单的规模化交叉熵，传统序列推荐系统的潜能正被激发。

发布时间：2024年08月26日

`LLM理论` `推荐系统` `人工智能`

> Are LLM-based Recommenders Already the Best? Simple Scaled Cross-entropy Unleashes the Potential of Traditional Sequential Recommenders

# 摘要

> 大型语言模型（LLM）在推荐领域备受瞩目。研究发现，通过交叉熵（CE）损失结合完整softmax微调的LLM，能在序列推荐中达到顶尖性能。但对比基线多采用pointwise/pairwise损失训练，这种实验设置差异低估了传统方法，并夸大了LLM的排序能力。本研究通过展示CE损失的紧密度与覆盖性，为其优越性提供理论支撑。同时揭示：1) 就某些排序指标而言，CE并非最优选择，因其界限不够紧密；2) 在无法执行完整softmax时，放大采样归一化项是有效替代方案。这些见解有助于传统推荐模型超越LLM，揭示现有LLM方法在序列推荐中的实际效果可能被高估。期望这些理论与实证结合，能促进未来对LLM推荐技术的客观评价。

> Large language models (LLMs) have been garnering increasing attention in the recommendation community. Some studies have observed that LLMs, when fine-tuned by the cross-entropy (CE) loss with a full softmax, could achieve `state-of-the-art' performance in sequential recommendation. However, most of the baselines used for comparison are trained using a pointwise/pairwise loss function. This inconsistent experimental setting leads to the underestimation of traditional methods and further fosters over-confidence in the ranking capability of LLMs.
  In this study, we provide theoretical justification for the superiority of the cross-entropy loss by demonstrating its two desirable properties: tightness and coverage. Furthermore, this study sheds light on additional novel insights: 1) Taking into account only the recommendation performance, CE is not yet optimal as it is not a quite tight bound in terms of some ranking metrics. 2) In scenarios that full softmax cannot be performed, an effective alternative is to scale up the sampled normalizing term. These findings then help unleash the potential of traditional recommendation models, allowing them to surpass LLM-based counterparts. Given the substantial computational burden, existing LLM-based methods are not as effective as claimed for sequential recommendation. We hope that these theoretical understandings in conjunction with the empirical results will facilitate an objective evaluation of LLM-based recommendation in the future.

[Arxiv](https://arxiv.org/abs/2408.14238)