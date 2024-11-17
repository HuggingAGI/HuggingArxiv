# 超越数字：关系抽取基准创建与排行榜的透明度

发布时间：2024年11月07日

`其他` `关系抽取`

> Beyond the Numbers: Transparency in Relation Extraction Benchmark Creation and Leaderboards

# 摘要

> 本文聚焦于关系抽取（RE）任务，对自然语言处理中基准创建的透明度以及用于衡量进展的排行榜的使用展开了研究。现有的 RE 基准常常存在文档不全的情况，像数据源、标注者间的一致性、用于挑选数据集实例的算法以及诸如数据集不平衡等潜在偏差的信息等关键细节都有所缺失。RE 的进展通常依据排行榜来衡量，这些排行榜依照评估方法给系统排名，一般局限于像 F1 分数这样的综合指标。然而，缺少这些指标之外的详细性能分析，可能会掩盖模型的真实泛化能力。我们的分析显示，广泛使用的 RE 基准，比如 TACRED 和 NYT，往往严重失衡且带有噪声标签。另外，缺乏基于类别的性能指标难以准确反映在具有众多关系类型的数据集上的模型性能。在汇报 RE 的进展时，应当审慎考虑这些限制。虽然我们的讨论围绕着 RE 基准和排行榜的透明度，但我们所探讨的观察结果也普遍适用于其他 NLP 任务。本文并非贬低现有 RE 基准和新模型开发的重要性与价值，而是倡导改进文档并进行更严格的评估，以推动该领域的进步。

> This paper investigates the transparency in the creation of benchmarks and the use of leaderboards for measuring progress in NLP, with a focus on the relation extraction (RE) task. Existing RE benchmarks often suffer from insufficient documentation, lacking crucial details such as data sources, inter-annotator agreement, the algorithms used for the selection of instances for datasets, and information on potential biases like dataset imbalance. Progress in RE is frequently measured by leaderboards that rank systems based on evaluation methods, typically limited to aggregate metrics like F1-score. However, the absence of detailed performance analysis beyond these metrics can obscure the true generalisation capabilities of models. Our analysis reveals that widely used RE benchmarks, such as TACRED and NYT, tend to be highly imbalanced and contain noisy labels. Moreover, the lack of class-based performance metrics fails to accurately reflect model performance across datasets with a large number of relation types. These limitations should be carefully considered when reporting progress in RE. While our discussion centers on the transparency of RE benchmarks and leaderboards, the observations we discuss are broadly applicable to other NLP tasks as well. Rather than undermining the significance and value of existing RE benchmarks and the development of new models, this paper advocates for improved documentation and more rigorous evaluation to advance the field.

[Arxiv](https://arxiv.org/abs/2411.05224)