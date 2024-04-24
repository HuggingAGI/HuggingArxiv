# 言多必失：在令牌限制条件下对大型语言模型进行数据污染

发布时间：2024年04月23日

`分类：LLM应用` `网络安全` `人工智能`

> Talk Too Much: Poisoning Large Language Models under Token Limit

# 摘要

> 针对大型语言模型（LLMs）的常见投毒攻击手法，通常通过在输入样本中设定固定触发词，并为这些触发词预设特定响应。但这种方法使用如异常词汇等固定触发器，容易被人工检测，从而限制了其在现实世界中的应用效果和实用性。为了提高触发器的隐蔽性，我们提出了一种新的投毒攻击方法，它利用了用户为节省成本而普遍采用的生成/输出条件——令牌限制。这种攻击下的模型在无令牌限制的输出时表现正常，但在有令牌限制的输出时会产生有害结果。为此，我们开发了BrieFool，一个高效的攻击框架，它通过精心设计的指令采样和数据投毒策略，利用了令牌限制的特性，影响了LLMs在特定条件下的行为模式。实验结果证明，BrieFool在多个安全和知识领域均表现出色。例如，在对GPT-3.5-turbo的攻击中，仅需20个生成的投毒样本，BrieFool就能在令牌限制条件下达到100%的攻击成功率，并获得了平均9.28/10的高有害性评分，同时在正常模式下保持了模型的良性表现。

> Mainstream poisoning attacks on large language models (LLMs) typically set a fixed trigger in the input instance and specific responses for triggered queries. However, the fixed trigger setting (e.g., unusual words) may be easily detected by human detection, limiting the effectiveness and practicality in real-world scenarios. To enhance the stealthiness of the trigger, we present a poisoning attack against LLMs that is triggered by a generation/output condition-token limitation, which is a commonly adopted strategy by users for reducing costs. The poisoned model performs normally for output without token limitation, while becomes harmful for output with limited tokens. To achieve this objective, we introduce BrieFool, an efficient attack framework. It leverages the characteristics of generation limitation by efficient instruction sampling and poisoning data generation, thereby influencing the behavior of LLMs under target conditions. Our experiments demonstrate that BrieFool is effective across safety domains and knowledge domains. For instance, with only 20 generated poisoning examples against GPT-3.5-turbo, BrieFool achieves a 100% Attack Success Rate (ASR) and a 9.28/10 average Harmfulness Score (HS) under token limitation conditions while maintaining the benign performance.

[Arxiv](https://arxiv.org/abs/2404.14795)