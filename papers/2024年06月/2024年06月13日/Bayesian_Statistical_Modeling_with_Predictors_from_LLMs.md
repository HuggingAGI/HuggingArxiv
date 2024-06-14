# 利用LLMs预测因子构建贝叶斯统计模型

发布时间：2024年06月13日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在多选决策任务中的预测与人类行为的相似性，以及它们是否能被视为人类认知或语言使用解释模型的一部分。研究通过贝叶斯统计模型分析了LLMs在特定任务中的表现，并与人类行为进行比较。这属于对LLMs理论性能和应用潜力的深入分析，因此归类为LLM理论。` `人工智能` `认知科学`

> Bayesian Statistical Modeling with Predictors from LLMs

# 摘要

> 最先进的大型语言模型（LLMs）在众多基准任务上表现出色，并逐渐成为大型应用中的关键组件，其预测常被视为人类判断或决策的替代。这引发了对LLM预测的人类相似性、与人类直觉的契合度以及它们是否能被视为人类认知或语言使用解释模型的一部分的探讨。为此，我们通过贝叶斯统计模型，探究了LLMs在多选决策任务中的预测与人类行为的相似性。通过分析一项关于语用语言使用的强制选择实验的人类数据，我们发现LLMs未能准确反映人类数据在个体项目上的变化。我们探讨了从LLMs中提取完整分布预测的不同策略，针对聚合、条件级别的数据，发现部分方法能较好地匹配人类数据，但并非所有方法都有效。这些发现强调了LLM性能评估对方法选择的高度敏感性，并指出LLMs最多只能作为聚合、条件级别的人类行为预测器，而这并非其设计初衷或常规应用。

> State of the art large language models (LLMs) have shown impressive performance on a variety of benchmark tasks and are increasingly used as components in larger applications, where LLM-based predictions serve as proxies for human judgements or decision. This raises questions about the human-likeness of LLM-derived information, alignment with human intuition, and whether LLMs could possibly be considered (parts of) explanatory models of (aspects of) human cognition or language use. To shed more light on these issues, we here investigate the human-likeness of LLMs' predictions for multiple-choice decision tasks from the perspective of Bayesian statistical modeling. Using human data from a forced-choice experiment on pragmatic language use, we find that LLMs do not capture the variance in the human data at the item-level. We suggest different ways of deriving full distributional predictions from LLMs for aggregate, condition-level data, and find that some, but not all ways of obtaining condition-level predictions yield adequate fits to human data. These results suggests that assessment of LLM performance depends strongly on seemingly subtle choices in methodology, and that LLMs are at best predictors of human behavior at the aggregate, condition-level, for which they are, however, not designed to, or usually used to, make predictions in the first place.

[Arxiv](https://arxiv.org/abs/2406.09012)