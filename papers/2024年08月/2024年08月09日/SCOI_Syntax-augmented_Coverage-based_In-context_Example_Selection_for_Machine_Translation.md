# SCOI：机器翻译中的语法增强覆盖式上下文示例选择

发布时间：2024年08月09日

`LLM应用` `机器翻译`

> SCOI: Syntax-augmented Coverage-based In-context Example Selection for Machine Translation

# 摘要

> ICL 在 LLM 上对多种下游任务的性能提升显著，关键在于演示的质量。我们创新性地引入句法知识，为机器翻译选择更优的上下文示例。提出的 SCOI 策略，深入挖掘句法结构，超越传统词匹配。通过计算多项式项的覆盖率和词重叠，我们量化了句法和词汇覆盖。实验证明，SCOI 在无学习方法中表现卓越，平均 COMET 分数最高，证实了句法与词汇覆盖结合的有效性，为 MT 选出了更佳的上下文示例。

> In-context learning (ICL) greatly improves the performance of large language models (LLMs) on various down-stream tasks, where the improvement highly depends on the quality of demonstrations. In this work, we introduce syntactic knowledge to select better in-context examples for machine translation (MT). We propose a new strategy, namely Syntax-augmented COverage-based In-context example selection (SCOI), leveraging the deep syntactic structure beyond conventional word matching. Specifically, we measure the set-level syntactic coverage by computing the coverage of polynomial terms with the help of a simplified tree-to-polynomial algorithm, and lexical coverage using word overlap. Furthermore, we devise an alternate selection approach to combine both coverage measures, taking advantage of syntactic and lexical information. We conduct experiments with two multi-lingual LLMs on six translation directions. Empirical results show that our proposed SCOI obtains the highest average COMET score among all learning-free methods, indicating that combining syntactic and lexical coverage successfully helps to select better in-context examples for MT.

[Arxiv](https://arxiv.org/abs/2408.04872)