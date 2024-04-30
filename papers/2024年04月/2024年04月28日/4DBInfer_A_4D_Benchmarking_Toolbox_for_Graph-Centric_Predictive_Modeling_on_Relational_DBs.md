# 4DBInfer：一款专为关系数据库设计的四维基准测试工具箱，专注于图形中心的预测性建模。

发布时间：2024年04月28日

`LLM应用` `数据库管理` `机器学习`

> 4DBInfer: A 4D Benchmarking Toolbox for Graph-Centric Predictive Modeling on Relational DBs

# 摘要

> 关系数据库（RDBs）虽然在互联表中存储了海量的丰富信息数据，但在这些任务上应用预测性机器学习模型的发展，相较于计算机视觉或自然语言处理等领域，显然还有很大的提升空间。这一差距部分原因在于缺少用于训练和评估的标准公共RDB基准。因此，目前的相关模型开发往往倾向于使用单一表基准训练的表格方法，或是采用图神经网络（GNN）等基于图的替代方案，这些方案应用于与表格特性迥异的数据集。为了更精准地针对处于这两个领域交汇处的RDBs，我们研究了一系列基线模型，这些模型基于：（i）采用多种策略将多表数据集转换为图，同时保留其表格特性；（ii）设计具有适当归纳偏置的可训练模型，这些模型能够基于输入子图进行预测。为了填补公共基准的空白并减少孤立比较，我们汇集了大量RDB数据集和相应的预测任务。我们通过一个名为4DBInfer的统一、可扩展的开源工具箱，实现了对这四个探索维度（4D）的操作。最后，我们使用4DBInfer进行评估，结果强调了在设计RDB预测模型时考虑每个维度的重要性，并指出了简单方法（如直接连接相邻表）的局限性。我们的源代码已在 https://github.com/awslabs/multi-table-benchmark 上发布。

> Although RDBs store vast amounts of rich, informative data spread across interconnected tables, the progress of predictive machine learning models as applied to such tasks arguably falls well behind advances in other domains such as computer vision or natural language processing. This deficit stems, at least in part, from the lack of established/public RDB benchmarks as needed for training and evaluation purposes. As a result, related model development thus far often defaults to tabular approaches trained on ubiquitous single-table benchmarks, or on the relational side, graph-based alternatives such as GNNs applied to a completely different set of graph datasets devoid of tabular characteristics. To more precisely target RDBs lying at the nexus of these two complementary regimes, we explore a broad class of baseline models predicated on: (i) converting multi-table datasets into graphs using various strategies equipped with efficient subsampling, while preserving tabular characteristics; and (ii) trainable models with well-matched inductive biases that output predictions based on these input subgraphs. Then, to address the dearth of suitable public benchmarks and reduce siloed comparisons, we assemble a diverse collection of (i) large-scale RDB datasets and (ii) coincident predictive tasks. From a delivery standpoint, we operationalize the above four dimensions (4D) of exploration within a unified, scalable open-source toolbox called 4DBInfer. We conclude by presenting evaluations using 4DBInfer, the results of which highlight the importance of considering each such dimension in the design of RDB predictive models, as well as the limitations of more naive approaches such as simply joining adjacent tables. Our source code is released at https://github.com/awslabs/multi-table-benchmark .

[Arxiv](https://arxiv.org/abs/2404.18209)