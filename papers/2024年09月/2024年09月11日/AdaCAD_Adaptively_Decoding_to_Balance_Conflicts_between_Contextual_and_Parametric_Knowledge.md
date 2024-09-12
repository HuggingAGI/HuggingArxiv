# AdaCAD：通过自适应解码，巧妙平衡上下文与参数知识间的冲突。

发布时间：2024年09月11日

`LLM理论` `问答系统`

> AdaCAD: Adaptively Decoding to Balance Conflicts between Contextual and Parametric Knowledge

# 摘要

> 知识冲突源于 LLM 上下文与参数知识之间的差异，使用标准解码技术时会忽略上下文，从而影响性能。现有对比方法通过比较有/无上下文时的输出分布来调整模型，但常误判冲突程度，尤其在冲突程度不同的实例上表现不佳。我们提出 AdaCAD，一种细粒度、实例级别的动态调整方法，根据 Jensen-Shannon 散度衡量冲突程度，动态调整权重。实验表明，AdaCAD 在 QA 任务上平均准确率比静态对比基线提升 14.21%，摘要事实性提高 5.59。分析显示，AdaCAD 在冲突不存在时也能减轻性能损失，更适用于现实世界数据集。

> Knowledge conflict arises from discrepancies between information in the context of a large language model (LLM) and the knowledge stored in its parameters. This can hurt performance when using standard decoding techniques, which tend to ignore the context. Existing test-time contrastive methods seek to address this by comparing the LLM's output distribution with and without the context and adjust the model according to the contrast between them. However, we find that these methods frequently misjudge the degree of conflict and struggle to handle instances that vary in their amount of conflict, with static methods over-adjusting when conflict is absent. We propose a fine-grained, instance-level approach called AdaCAD, which dynamically infers the weight of adjustment based on the degree of conflict, as measured by the Jensen-Shannon divergence between distributions representing contextual and parametric knowledge. Our experiments across four models on six diverse question-answering (QA) datasets and three summarization tasks demonstrate that our training-free adaptive method consistently outperforms other decoding methods on QA, with average accuracy gains of 14.21% (absolute) over a static contrastive baseline, and improves the factuality of summaries by 5.59 (AlignScore). Furthermore, our analysis shows that while decoding with contrastive baselines hurts performance when conflict is absent, AdaCAD mitigates these losses, making it more applicable to real-world datasets in which some examples have conflict and others do not.

[Arxiv](https://arxiv.org/abs/2409.07394)