# 充分发挥大型语言模型在群组兴趣点推荐上的威力

发布时间：2024年11月20日

`LLM应用` `推荐系统` `兴趣点`

> Unleashing the Power of Large Language Models for Group POI Recommendations

# 摘要

> 群组兴趣点（POI）推荐的目标是预测能契合一组用户多元偏好的下一个兴趣点。鉴于复杂的群组决策以及极度稀疏的群组级别签到数据，此任务比传统的个人兴趣点推荐更具难度。现有的群组兴趣点推荐手段主要依靠签到数据里基于单个 ID 的特征，仅能捕捉统计关联，无法充分利用签到所包含的丰富语义信息，致使性能欠佳。为此，我们构建了一个框架，以释放大型语言模型（LLM）的能量，用于具备上下文感知能力的群组兴趣点推荐（LLMGPR）。我们的方法先是引入兴趣点标记和 LLM 的原始单词标记，这些标记通过将 LLM 应用于每个兴趣点的丰富信息来初始化。接着，我们提出一种由量化低秩自适应（QLORA）引导的新型排序适配器来改进 LLM。强化后的 LLM 能够结合语义增强的兴趣点标记以及包含位置编码和时空差异等丰富的上下文信息来学习序列表示。该方法能依据序列类型用于学习群组或用户的表示。另外，我们借助另一个基于 QLORA 的聚合适配器来聚合个体成员表示，并引入一个预测签到序列目的的自监督学习任务，以增强群组表示，化解数据稀疏的难题。我们的实验结果表明，LLMGPR 优于现有方法，有效应对了群组级别的数据稀疏问题，并给出了更优的推荐。

> Group Point-of-Interest (POI) recommendations aim to predict the next POI that satisfies the diverse preferences of a group of users. This task is more challenging than traditional individual POI recommendations due to complex group decision-making and extremely sparse group-level check-in data. Existing methods for group POI recommendations primarily rely on single ID-based features from check-in data, capturing only statistical correlations and failing to fully utilize the rich semantic information contained in the check-ins, resulting in suboptimal performance. To this end, we propose a framework that unleashes the power of the Large Language Model (LLM) for context-aware group POI recommendations (LLMGPR). Our approach first introduces POI tokens alongside the original word tokens of the LLM, which are initialized by applying the LLM to the rich information of each POI. We then propose a novel sequencing adapter guided by Quantized Low-Rank Adaptation (QLORA) to modify the LLM. The enhanced LLM can learn sequence representations by combining semantic-enhanced POI tokens and rich contextual information including positional encodings and spatio-temporal differences. This approach can be adapted for learning either group or user representations depending on the sequence type. Furthermore, we enhance group representations by aggregating individual member representations with another QLORA-based aggregation adapter and introducing a self-supervised learning task that predicts the purpose of check-in sequences, alleviating the data sparsity issue. Our experimental results demonstrate that LLMGPR outperforms existing methods, effectively addressing group-level data sparsity and providing superior recommendations.

[Arxiv](https://arxiv.org/abs/2411.13415)