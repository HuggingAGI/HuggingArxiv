# 本研究通过实证方法探究了将大型语言模型（LLM）作为评价工具的应用，其中经过微调的Judge模型实质上成为了针对特定任务的分类器。

发布时间：2024年03月05日

`LLM应用`

> An Empirical Study of LLM-as-a-Judge for LLM Evaluation: Fine-tuned Judge Models are Task-specific Classifiers

> 近期趋势显示，利用LLM评估其他LLM质量的做法日益流行，其中不少研究采用闭源且独有的GPT4作为评价标准，也有部分工作选择基于开源LLM微调评判模型担当此角色。在本研究中，我们对各类评判模型的评估效能进行了深入实践探索。尽管发现微调后的评判模型在对应领域的测试集中表现抢眼，甚至能超越GPT4，但它们本质上具有很强的任务特异性，其泛化性和公平性与GPT4相比存在显著差距。

> Recently, there has been a growing trend of utilizing Large Language Model (LLM) to evaluate the quality of other LLMs. Many studies have employed proprietary close-source models, especially GPT4, as the evaluator. Alternatively, other works have fine-tuned judge models based on open-source LLMs as the evaluator. In this study, we conduct an empirical study of different judge models on their evaluation capability. Our findings indicate that although the fine-tuned judge models achieve high accuracy on in-domain test sets, even surpassing GPT4, they are inherently task-specific classifiers, and their generalizability and fairness severely underperform GPT4.

[Arxiv](https://arxiv.org/abs/2403.02839)