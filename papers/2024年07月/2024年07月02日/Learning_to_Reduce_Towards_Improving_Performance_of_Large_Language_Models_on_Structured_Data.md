# 通过学习简化，我们致力于提升大型语言模型在处理结构化数据时的表现。

发布时间：2024年07月02日

`LLM应用` `人工智能` `数据分析`

> Learning to Reduce: Towards Improving Performance of Large Language Models on Structured Data

# 摘要

> 尽管大型语言模型 (LLM) 在众多下游任务中表现出色，但在结构化数据推理方面仍面临挑战。本文提出的“学习去减少”框架，通过策略学习微调语言模型，有效简化了输入数据，不仅性能卓越，还展现了跨数据集的泛化能力。此外，该框架微调的模型在长上下文的表格问答任务中表现尤为出色，为 LLM 的应用拓展了新的可能。

> Large Language Models (LLMs) have been achieving competent performance on a wide range of downstream tasks, yet existing work shows that inference on structured data is challenging for LLMs. This is because LLMs need to either understand long structured data or select the most relevant evidence before inference, and both approaches are not trivial. This paper proposes a framework, Learning to Reduce, that fine-tunes a language model with On-Policy Learning to generate a reduced version of an input structured data. When compared to state-of-the-art LLMs like GPT-4, Learning to Reduce not only achieves outstanding performance in reducing the input, but shows generalizability on different datasets. We further show that the model fine-tuned with our framework helps LLMs better perform on table QA tasks especially when the context is longer.

![通过学习简化，我们致力于提升大型语言模型在处理结构化数据时的表现。](../../../paper_images/2407.02750/model2.png)

![通过学习简化，我们致力于提升大型语言模型在处理结构化数据时的表现。](../../../paper_images/2407.02750/task_performance_gpt-4-0613.png)

![通过学习简化，我们致力于提升大型语言模型在处理结构化数据时的表现。](../../../paper_images/2407.02750/task_performance_gpt-3.5-turbo.png)

[Arxiv](https://arxiv.org/abs/2407.02750)