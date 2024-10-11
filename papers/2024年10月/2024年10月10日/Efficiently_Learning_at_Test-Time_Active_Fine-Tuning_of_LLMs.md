# 测试时高效学习：LLM 的主动微调

发布时间：2024年10月10日

`LLM理论` `人工智能` `数据科学`

> Efficiently Learning at Test-Time: Active Fine-Tuning of LLMs

# 摘要

> 近期微调语言模型的研究多依赖于自动数据选择，常用方法是从大型数据集中进行最近邻检索。然而，我们理论分析发现，这种方法易选择冗余数据，影响效果甚至损害性能。为此，我们推出SIFT算法，旨在减少模型响应的不确定性，融合了检索与主动学习的理念。与在信息重复时失效的最近邻检索不同，SIFT考虑信息重复并优化整体信息增益。我们在Pile数据集上进行测试时微调，结果显示SIFT始终优于最近邻检索，且计算开销极低。此外，我们的不确定性估计能预测微调性能提升，据此开发了按性能增益比例投入计算的自适应算法。我们还提供了$\texttt{activeft}$库，可直接替代最近邻检索。

> Recent efforts in fine-tuning language models often rely on automatic data selection, commonly using Nearest Neighbors retrieval from large datasets. However, we theoretically show that this approach tends to select redundant data, limiting its effectiveness or even hurting performance. To address this, we introduce SIFT, a data selection algorithm designed to reduce uncertainty about the model's response given a prompt, which unifies ideas from retrieval and active learning. Whereas Nearest Neighbor retrieval typically fails in the presence of information duplication, SIFT accounts for information duplication and optimizes the overall information gain of the selected examples. We focus our evaluations on fine-tuning at test-time for prompt-specific language modeling on the Pile dataset, and show that SIFT consistently outperforms Nearest Neighbor retrieval, with minimal computational overhead. Moreover, we show that our uncertainty estimates can predict the performance gain of test-time fine-tuning, and use this to develop an adaptive algorithm that invests test-time compute proportional to realized performance gains. We provide the $\texttt{activeft}$ (Active Fine-Tuning) library which can be used as a drop-in replacement for Nearest Neighbor retrieval.

[Arxiv](https://arxiv.org/abs/2410.08020)