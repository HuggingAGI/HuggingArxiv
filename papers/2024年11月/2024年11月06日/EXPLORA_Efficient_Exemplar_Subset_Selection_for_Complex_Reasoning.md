# EXPLORA：用于复杂推理的高效示例子集选择

发布时间：2024年11月06日

`LLM应用` `推理任务`

> EXPLORA: Efficient Exemplar Subset Selection for Complex Reasoning

# 摘要

> 回答关于文本和包括表格在内的混合来源的基于推理的复杂问题是一项具有挑战性的任务。大型语言模型（LLM）的最新进展实现了上下文学习（ICL），允许 LLM 仅使用几个演示样本（示例）就能在特定任务中变得熟练。ICL 中的一个关键挑战是最优示例的选择，这些示例可以是特定于任务的（静态）或特定于测试示例的（动态）。静态示例提供了更快的推理时间，并在测试示例的分布中增加了鲁棒性。在本文中，我们提出了一种用于复杂推理任务的静态示例子集选择算法。我们引入了 EXPLORA，这是一种新的探索方法，旨在估计评分函数的参数，该函数在不结合置信信息的情况下评估示例子集。EXPLORA 显著将 LLM 调用的数量减少到最先进方法所需数量的约 11％，并实现了 12.24％的显著性能提升。我们开源了我们的代码和数据（https://github.com/kiranpurohit/EXPLORA）。

> Answering reasoning-based complex questions over text and hybrid sources, including tables, is a challenging task. Recent advances in large language models (LLMs) have enabled in-context learning (ICL), allowing LLMs to acquire proficiency in a specific task using only a few demonstration samples (exemplars). A critical challenge in ICL is the selection of optimal exemplars, which can be either task-specific (static) or test-example-specific (dynamic). Static exemplars provide faster inference times and increased robustness across a distribution of test examples. In this paper, we propose an algorithm for static exemplar subset selection for complex reasoning tasks. We introduce EXPLORA, a novel exploration method designed to estimate the parameters of the scoring function, which evaluates exemplar subsets without incorporating confidence information. EXPLORA significantly reduces the number of LLM calls to ~11% of those required by state-of-the-art methods and achieves a substantial performance improvement of 12.24%. We open-source our code and data (https://github.com/kiranpurohit/EXPLORA).

[Arxiv](https://arxiv.org/abs/2411.03877)