# 借助对比解释来阐释语言奖励模型

发布时间：2024年11月25日

`LLM应用` `语言模型` `人工智能`

> Interpreting Language Reward Models via Contrastive Explanations

# 摘要

> 奖励模型（RMs）在让大型语言模型（LLMs）的输出契合人类价值观方面，是至关重要的组成部分。RMs 通过预测和对比奖励分数，来近似人类对于相同提示下可能的 LLM 响应的偏好。但由于它们通常是带有标量输出头的 LLMs 的改良版本，RMs 就像大型黑箱，其预测难以解释。更具透明度的 RMs 会增强人们对 LLMs 一致性的信任。在本项工作中，我们提议运用对比解释来阐释 RM 做出的任何二元响应比较。具体而言，我们生成了一组与原比较类似的多样化新比较，以刻画 RM 的局部行为。为明确修改人工指定的高级评估属性，生成了构成新比较的扰动响应，RM 行为的分析以此为依据。在定量实验里，我们验证了我们方法在获取高质量对比解释方面的有效性。接着，我们展示了我们的方法在探究 RMs 对每个评估属性的全局敏感性上的定性实用性，并演示了如何自动提取具有代表性的实例来解释和比较不同 RMs 的行为。我们将我们的方法视作 RM 解释的灵活框架，为更具可解释性和可信度的 LLM 一致性奠定基础。

> Reward models (RMs) are a crucial component in the alignment of large language models' (LLMs) outputs with human values. RMs approximate human preferences over possible LLM responses to the same prompt by predicting and comparing reward scores. However, as they are typically modified versions of LLMs with scalar output heads, RMs are large black boxes whose predictions are not explainable. More transparent RMs would enable improved trust in the alignment of LLMs. In this work, we propose to use contrastive explanations to explain any binary response comparison made by an RM. Specifically, we generate a diverse set of new comparisons similar to the original one to characterise the RM's local behaviour. The perturbed responses forming the new comparisons are generated to explicitly modify manually specified high-level evaluation attributes, on which analyses of RM behaviour are grounded. In quantitative experiments, we validate the effectiveness of our method for finding high-quality contrastive explanations. We then showcase the qualitative usefulness of our method for investigating global sensitivity of RMs to each evaluation attribute, and demonstrate how representative examples can be automatically extracted to explain and compare behaviours of different RMs. We see our method as a flexible framework for RM explanation, providing a basis for more interpretable and trustworthy LLM alignment.

[Arxiv](https://arxiv.org/abs/2411.16502)