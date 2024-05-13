# 借助代理辅助的不确定性评估，精进语言模型的指令执行艺术

发布时间：2024年05月10日

`LLM理论

这篇论文关注的是语言模型（LLM）中指令响应质量的评估问题，并提出了一个不确定性感知奖励模型（URM）来解决这一挑战。论文的核心贡献在于通过贝叶斯近似提供了一个能够评估响应不确定性的模型，这在语言模型训练中提高了指令遵循能力。这种方法的提出和实证结果表明了在语言模型理论上的进展，特别是在如何利用不确定性来优化模型性能方面。因此，这篇论文更符合LLM理论分类，因为它探讨了语言模型内部的评估机制和优化方法，而不是直接应用于特定的Agent或RAG系统，也不是作为一个具体的LLM应用案例。` `机器学习`

> Improving Instruction Following in Language Models through Proxy-Based Uncertainty Estimation

# 摘要

> 在语言模型中，准确评估指令响应的质量至关重要，但因人类语言的复杂多变而充满挑战。我们提出的不确定性感知奖励模型（URM）通过贝叶斯近似，为响应质量提供了稳健的不确定性估计。该模型在偏好数据集上训练，不仅能评分，还能评估响应的不确定性。实证显示，我们的方法在语言模型训练中显著提升了指令遵循能力，通过优化数据选择和策略目标，在Vicuna和MT-bench等测试中超越了现有方法。这表明我们的方法在语言模型训练上取得了重大进展，并为利用不确定性提供了新思路。

> Assessing response quality to instructions in language models is vital but challenging due to the complexity of human language across different contexts. This complexity often results in ambiguous or inconsistent interpretations, making accurate assessment difficult. To address this issue, we propose a novel Uncertainty-aware Reward Model (URM) that introduces a robust uncertainty estimation for the quality of paired responses based on Bayesian approximation. Trained with preference datasets, our uncertainty-enabled proxy not only scores rewards for responses but also evaluates their inherent uncertainty. Empirical results demonstrate significant benefits of incorporating the proposed proxy into language model training. Our method boosts the instruction following capability of language models by refining data curation for training and improving policy optimization objectives, thereby surpassing existing methods by a large margin on benchmarks such as Vicuna and MT-bench. These findings highlight that our proposed approach substantially advances language model training and paves a new way of harnessing uncertainty within language models.

[Arxiv](https://arxiv.org/abs/2405.06424)