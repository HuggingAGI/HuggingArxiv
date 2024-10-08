# 语言模型驱动数据修剪，助力高效主动学习

发布时间：2024年10月05日

`LLM应用` `数据标注`

> Language Model-Driven Data Pruning Enables Efficient Active Learning

# 摘要

> 主动学习 (AL) 通过挑选最具信息量的样本进行标注，从而提升数据标注效率。其核心在于获取函数，该函数指导样本选择，从未标注数据池中筛选出适合标注的样本。然而，面对庞大的未标注数据池，这些获取方法的计算成本高昂，限制了其在大型数据集上的应用。为此，我们推出了一种创新的即插即用数据修剪策略——ActivePrune，借助语言模型精简未标注数据池。ActivePrune 采用两阶段修剪流程：首先利用 n-gram 语言模型的困惑度分数进行快速初筛，再通过量化 LLM 计算的数据质量指标进行精细挑选。此外，为提升未标注数据的多样性，我们设计了一种困惑度重新加权方法，系统性地将未充分代表的样本优先纳入后续标注迭代。实验结果显示，在翻译、情感分析、主题分类和摘要等多项任务中，ActivePrune 均优于现有数据修剪方法。最终，我们对比了各数据修剪方法在选择质量和效率之间的权衡，证实 ActivePrune 在计算效率上超越其他基于 LLM 分数的修剪方法，最多可减少 74% 的主动学习整体时间。

> Active learning (AL) optimizes data labeling efficiency by selecting the most informative instances for annotation. A key component in this procedure is an acquisition function that guides the selection process and identifies the suitable instances for labeling from the unlabeled pool. However, these acquisition methods suffer from high computational costs with large unlabeled data pools, posing a roadblock to their applicability on large datasets. To address this challenge and bridge this gap, we introduce a novel plug-and-play unlabeled data pruning strategy, ActivePrune, which leverages language models to prune the unlabeled pool. ActivePrune implements a two-stage pruning process: an initial fast evaluation using perplexity scores from an n-gram language model, followed by a high-quality selection using metrics for data quality computed through a quantized LLM. Additionally, to enhance the diversity in the unlabeled pool, we propose a novel perplexity reweighting method that systematically brings forward underrepresented instances for selection in subsequent labeling iterations. Experiments on translation, sentiment analysis, topic classification, and summarization tasks on four diverse datasets and four active learning strategies demonstrate that ActivePrune outperforms existing data pruning methods. Finally, we compare the selection quality $\leftrightarrow$ efficiency tradeoff of the data pruning methods and demonstrate that ActivePrune is computationally more efficient than other LLM score-based pruning methods, and provides up to 74% reduction in the end-to-end time required for active learning.

[Arxiv](https://arxiv.org/abs/2410.04275)