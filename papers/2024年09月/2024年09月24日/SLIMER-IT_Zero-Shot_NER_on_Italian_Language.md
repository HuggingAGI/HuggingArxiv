# SLIMER-IT：意大利语零-shot命名实体识别

发布时间：2024年09月24日

`LLM应用` `信息提取`

> SLIMER-IT: Zero-Shot NER on Italian Language

# 摘要

> 传统 NER 方法虽在下游任务中表现优异，但依赖大量标注数据，且难以适应新领域和新实体类型。相比之下，大型语言模型 (LLM) 展现了强大的零-shot 能力。尽管英语零-shot NER 已有研究，但其他语言仍待探索。本文为零-shot NER 构建了评估框架，并应用于意大利语。我们推出了 SLIMER-IT，一种利用丰富提示进行指令调优的零-shot NER 方法。实验表明，SLIMER-IT 在处理新实体标签时表现卓越。

> Traditional approaches to Named Entity Recognition (NER) frame the task into a BIO sequence labeling problem. Although these systems often excel in the downstream task at hand, they require extensive annotated data and struggle to generalize to out-of-distribution input domains and unseen entity types. On the contrary, Large Language Models (LLMs) have demonstrated strong zero-shot capabilities. While several works address Zero-Shot NER in English, little has been done in other languages. In this paper, we define an evaluation framework for Zero-Shot NER, applying it to the Italian language. Furthermore, we introduce SLIMER-IT, the Italian version of SLIMER, an instruction-tuning approach for zero-shot NER leveraging prompts enriched with definition and guidelines. Comparisons with other state-of-the-art models, demonstrate the superiority of SLIMER-IT on never-seen-before entity tags.

[Arxiv](https://arxiv.org/abs/2409.15933)