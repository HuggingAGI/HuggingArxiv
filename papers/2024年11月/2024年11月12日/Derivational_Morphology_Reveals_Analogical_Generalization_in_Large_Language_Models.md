# 派生形态学揭示了大型语言模型中的类比概括。

发布时间：2024年11月12日

`LLM理论` `语言模型`

> Derivational Morphology Reveals Analogical Generalization in Large Language Models

# 摘要

> 大型语言模型（LLM）中的语言概括背后有哪些机制？这个问题引起了相当大的关注，大多数研究都在分析 LLM 的语言技能在多大程度上类似于规则。到目前为止，还不知道 LLM 中的语言概括是否同样可以被解释为类推过程的结果，这可以被形式化为对存储示例的相似性操作。先前研究的一个关键缺点是其重点放在具有高度规律性的语言现象上，对于这些现象，基于规则和类推的方法做出了相同的预测。在这里，我们反而研究了派生形态学，特别是英语形容词名词化，它表现出显著的可变性。我们引入了一种研究 LLM 中语言概括的新方法：聚焦于 GPT-J，我们将实例化基于规则和类推学习的认知模型拟合到 LLM 训练数据，并将它们对一组临时形容词的预测与 LLM 的预测进行比较，使我们能够就潜在机制得出直接结论。正如预期的那样，对于具有规则名词化模式的形容词，基于规则和类推的模型同样很好地解释了 GPT-J 的预测。然而，对于具有可变名词化模式的形容词，类推模型提供了更好的匹配。此外，GPT-J 的行为对单个词的频率敏感，即使对于规则形式也是如此，这种行为与规则形式的类推解释一致，但与基于规则的解释不一致。这些发现反驳了 GPT-J 在形容词名词化方面的语言概括涉及规则的假设，表明对存储示例的相似性操作是潜在机制。总的来说，我们的研究表明，在 LLM 的语言概括中，类推过程比以前认为的发挥了更大的作用。

> What mechanisms underlie linguistic generalization in large language models (LLMs)? This question has attracted considerable attention, with most studies analyzing the extent to which the language skills of LLMs resemble rules. As of yet, it is not known whether linguistic generalization in LLMs could equally well be explained as the result of analogical processes, which can be formalized as similarity operations on stored exemplars. A key shortcoming of prior research is its focus on linguistic phenomena with a high degree of regularity, for which rule-based and analogical approaches make the same predictions. Here, we instead examine derivational morphology, specifically English adjective nominalization, which displays notable variability. We introduce a new method for investigating linguistic generalization in LLMs: focusing on GPT-J, we fit cognitive models that instantiate rule-based and analogical learning to the LLM training data and compare their predictions on a set of nonce adjectives with those of the LLM, allowing us to draw direct conclusions regarding underlying mechanisms. As expected, rule-based and analogical models explain the predictions of GPT-J equally well for adjectives with regular nominalization patterns. However, for adjectives with variable nominalization patterns, the analogical model provides a much better match. Furthermore, GPT-J's behavior is sensitive to the individual word frequencies, even for regular forms, a behavior that is consistent with an analogical account of regular forms but not a rule-based one. These findings refute the hypothesis that GPT-J's linguistic generalization on adjective nominalization involves rules, suggesting similarity operations on stored exemplars as the underlying mechanism. Overall, our study suggests that analogical processes play a bigger role in the linguistic generalization of LLMs than previously thought.

[Arxiv](https://arxiv.org/abs/2411.07990)