# 纠偏与去偏：运用非线性整数规划策略，精准校正语言模型中的成对准确性偏差

发布时间：2024年05月13日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在上下文学习（ICL）中的类别准确性不平衡问题，并提出了“上下文奇异偏差”（COBias）的概念以及一种名为“去偏差非线性整数规划”（DNIP）的方法来纠正这种偏差。研究关注的是LLMs在不同类别准确性上的表现，并通过优化方法来提高模型的预测准确性和可靠性。这属于对LLMs理论层面的研究，特别是关于模型预测偏差和准确性的理论探讨，因此归类为LLM理论。` `机器学习`

> COBias and Debias: Minimizing Language Model Pairwise Accuracy Bias via Nonlinear Integer Programming

# 摘要

> 在语言模型分类中，你是选择单一可行的类别，还是希望每个类别都能发挥作用？显然，后者更具实用性。大型语言模型（LLMs）通过上下文学习（ICL）虽然总体准确性尚可，但掩盖了各别类别准确性间的显著差异。本研究首次将这种不平衡重新定义为“上下文奇异偏差”（COBias），并采用非线性整数规划（NIP）来纠正这一偏差。COBias衡量的是某一类别与其“奇异”类别间的准确性差异，后者包含了该类别的大量错误预测。我们发现，不同规模和类型的LLMs在各别类别准确性上存在显著差异。为此，我们提出了一种名为“去偏差非线性整数规划”（DNIP）的方法，旨在通过调整ICL中各别类别的概率，降低偏差并提升总体准确性。我们的优化目标直接关联于COBias和准确性指标，通过模拟退火算法解决。在七个NLP分类任务上对三个LLMs的评估结果显示，DNIP在传统ICL方法的基础上，实现了COBias的显著减少（-27%）和准确性的提升（+12%），这表明，通过建模成对类别准确性差异，我们能够推动LLMs预测的准确性和可靠性。

> For language model classification, would you prefer having only one workable class or having every class working? The latter makes more practical uses. Especially for large language models (LLMs), the fact that they achieve a fair overall accuracy by in-context learning (ICL) obscures a large difference in individual class accuracies. In this work, we uncover and tackle language models' imbalance in per-class prediction accuracy by reconceptualizing it as the Contextual Oddity Bias (COBias), and we are the first to engage nonlinear integer programming (NIP) to debias it. Briefly, COBias refers to the difference in accuracy by a class A compared to its ''odd'' class, which holds the majority wrong predictions of class A. With the COBias metric, we reveal that LLMs of varied scales and families exhibit large per-class accuracy differences. Then we propose Debiasing as Nonlinear Integer Programming (DNIP) to correct ICL per-class probabilities for lower bias and higher overall accuracy. Our optimization objective is directly based on the evaluation scores by COBias and accuracy metrics, solved by simulated annealing. Evaluations on three LLMs across seven NLP classification tasks show that DNIP simultaneously achieves significant COBias reduction ($-27\%$) and accuracy improvement ($+12\%$) over the conventional ICL approach, suggesting that modeling pairwise class accuracy differences is a direction in pushing forward more accurate, more reliable LLM predictions.

[Arxiv](https://arxiv.org/abs/2405.07623)