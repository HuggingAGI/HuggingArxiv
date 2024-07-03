# 利用生成式AI评估信息检索的可靠置信区间

发布时间：2024年07月02日

`LLM应用` `信息检索` `数据评估`

> Reliable Confidence Intervals for Information Retrieval Evaluation Using Generative A.I

# 摘要

> 传统的信息检索系统评估因依赖人类专家的手动标注而成本高昂。随着大型语言模型（LLMs）的发展，我们能在低成本下大规模生成相关性标注，有望降低评估成本，惠及众多低资源应用。然而，这些生成的标注存在系统性错误，直接用于评估会导致结果不可靠。为此，我们提出了两种方法：预测驱动推理和一致性风险控制，利用计算机生成的标注为评估指标设定可靠的置信区间（CIs）。这些方法仅需少量可靠标注，即可统计分析生成标注的错误，进而为评估指标设定具有强理论保证的CIs。与传统方法不同，我们的一致性风险控制方法专为排名指标设计，能根据每个查询和文档灵活调整CIs。实验表明，我们的CIs能更准确地捕捉评估中的方差和偏差。我们期待这些贡献能为众多IR应用带来可靠的评估。

> The traditional evaluation of information retrieval (IR) systems is generally very costly as it requires manual relevance annotation from human experts. Recent advancements in generative artificial intelligence -- specifically large language models (LLMs) -- can generate relevance annotations at an enormous scale with relatively small computational costs. Potentially, this could alleviate the costs traditionally associated with IR evaluation and make it applicable to numerous low-resource applications. However, generated relevance annotations are not immune to (systematic) errors, and as a result, directly using them for evaluation produces unreliable results.
  In this work, we propose two methods based on prediction-powered inference and conformal risk control that utilize computer-generated relevance annotations to place reliable confidence intervals (CIs) around IR evaluation metrics. Our proposed methods require a small number of reliable annotations from which the methods can statistically analyze the errors in the generated annotations. Using this information, we can place CIs around evaluation metrics with strong theoretical guarantees. Unlike existing approaches, our conformal risk control method is specifically designed for ranking metrics and can vary its CIs per query and document. Our experimental results show that our CIs accurately capture both the variance and bias in evaluation based on LLM annotations, better than the typical empirical bootstrapping estimates. We hope our contributions bring reliable evaluation to the many IR applications where this was traditionally infeasible.

[Arxiv](https://arxiv.org/abs/2407.02464)