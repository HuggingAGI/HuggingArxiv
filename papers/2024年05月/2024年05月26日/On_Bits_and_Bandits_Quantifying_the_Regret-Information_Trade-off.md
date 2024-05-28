# 比特与强盗之间：探索后悔与信息之间的微妙平衡

发布时间：2024年05月26日

`Agent

这篇论文主要研究了在交互式决策任务中，信息获取途径的多样性以及信息积累与遗憾之间的权衡。通过信息论方法，作者确定了遗憾的下界，并将这些理论应用于大型语言模型的问题回答任务中，展示了其实际应用价值。这表明论文关注的是如何通过信息积累来优化决策过程，特别是在涉及外部信息的交互决策任务中，这与Agent的研究领域相关，因为Agent通常需要处理信息并做出决策。因此，这篇论文更适合归类到Agent分类中。` `交互式决策` `信息论`

> On Bits and Bandits: Quantifying the Regret-Information Trade-off

# 摘要

> 在交互式决策任务中，信息获取途径多样，包括直接互动、间接反馈和外部知识源。我们研究了信息积累与遗憾之间的权衡，发现外部信息（以比特计量）可与遗憾（以奖励计量）相抵。通过信息论方法，我们不仅确定了遗憾的下界，还轻松重现了多个已知的下界。我们将多种涉及外部信息的交互决策任务扩展至新情境，首次提出了基于信息积累的贝叶斯遗憾下界，证实了汤普森采样在贝叶斯问题中的近似最优性。最后，我们通过大型语言模型的问题回答任务，展示了这些界限的实际应用价值，为我们带来了深刻的洞察。

> In interactive decision-making tasks, information can be acquired by direct interactions, through receiving indirect feedback, and from external knowledgeable sources. We examine the trade-off between the information an agent accumulates and the regret it suffers. We show that information from external sources, measured in bits, can be traded off for regret, measured in reward. We invoke information-theoretic methods for obtaining regret lower bounds, that also allow us to easily re-derive several known lower bounds. We then generalize a variety of interactive decision-making tasks with external information to a new setting. Using this setting, we introduce the first Bayesian regret lower bounds that depend on the information an agent accumulates. These lower bounds also prove the near-optimality of Thompson sampling for Bayesian problems. Finally, we demonstrate the utility of these bounds in improving the performance of a question-answering task with large language models, allowing us to obtain valuable insights.

![比特与强盗之间：探索后悔与信息之间的微妙平衡](../../../paper_images/2405.16581/x1.png)

![比特与强盗之间：探索后悔与信息之间的微妙平衡](../../../paper_images/2405.16581/bayes_bandit_regret.png)

![比特与强盗之间：探索后悔与信息之间的微妙平衡](../../../paper_images/2405.16581/bayes_bandit_mi.png)

![比特与强盗之间：探索后悔与信息之间的微妙平衡](../../../paper_images/2405.16581/algo_bandit_regret.png)

![比特与强盗之间：探索后悔与信息之间的微妙平衡](../../../paper_images/2405.16581/algo_bandit_mi.png)

![比特与强盗之间：探索后悔与信息之间的微妙平衡](../../../paper_images/2405.16581/regret_llm.png)

![比特与强盗之间：探索后悔与信息之间的微妙平衡](../../../paper_images/2405.16581/x2.png)

[Arxiv](https://arxiv.org/abs/2405.16581)