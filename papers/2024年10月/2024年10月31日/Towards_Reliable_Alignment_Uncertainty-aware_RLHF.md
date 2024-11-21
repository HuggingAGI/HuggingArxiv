# 朝着可靠对齐进发：具备不确定性意识的 RLHF

发布时间：2024年10月31日

`LLM理论` `语言模型`

> Towards Reliable Alignment: Uncertainty-aware RLHF

# 摘要

> 近期，在让大型语言模型与人类偏好相契合方面取得了进展，这得益于更强大的奖励模型和更优质的偏好数据。然而，这些方法大多依赖于奖励模型的精准度。在基于人类反馈的强化学习（RLHF）中所使用的奖励模型，通常是通过随机优化算法从小数据集中习得的，这导致它们极易产生高变异性。我们在众多开源数据集中通过实践揭示了奖励模型之间的不一致性。
  从理论上讲，奖励模型的波动可能对契合问题不利，因为所导出的策略对奖励模型过度拟合，所以若奖励模型本身不确定，风险就更高。我们运用测度集中来推动一种具有不确定性感知的保守策略优化算法。我们表明，此类策略在更具风险规避性的意义上，对不确定的奖励更为谨慎。我们从理论上证明，我们所提出的方法比常规方法风险更低。
  我们通过基于设计奖励模型集成的实验来验证我们的理论结果。我们利用这个奖励模型集成，采用我们的方法来对齐语言模型，并发现我们的实验结果与理论预测相符。

> Recent advances in aligning Large Language Models with human preferences have benefited from larger reward models and better preference data. However, most of these methodologies rely on the accuracy of the reward model. The reward models used in Reinforcement Learning with Human Feedback (RLHF) are typically learned from small datasets using stochastic optimization algorithms, making them prone to high variability. We illustrate the inconsistencies between reward models empirically on numerous open-source datasets.
  We theoretically show that the fluctuation of the reward models can be detrimental to the alignment problem because the derived policies are more overfitted to the reward model and, hence, are riskier if the reward model itself is uncertain. We use concentration of measure to motivate an uncertainty-aware, conservative algorithm for policy optimization. We show that such policies are more risk-averse in the sense that they are more cautious of uncertain rewards. We theoretically prove that our proposed methodology has less risk than the vanilla method.
  We corroborate our theoretical results with experiments based on designing an ensemble of reward models. We use this ensemble of reward models to align a language model using our methodology and observe that our empirical findings match our theoretical predictions.

[Arxiv](https://arxiv.org/abs/2410.23726)