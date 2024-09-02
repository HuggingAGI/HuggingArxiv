# Novel-WD：通过前缀调优，探索 LLMs 获取新世界知识的能力

发布时间：2024年08月30日

`LLM应用` `人工智能`

> Novel-WD: Exploring acquisition of Novel World Knowledge in LLMs Using Prefix-Tuning

# 摘要

> 教授预训练大型语言模型 (PLM) 新知识既关键又具挑战。尽管微调等技术能缓慢吸收新知，但持续学习成本高且易遗忘。我们研究了 PLM 如何学习并记忆预训练语料库之外的新世界知识，并创建了 Novel-WD 数据集，包含最新 Wikidata 更新中的新事实，以及因果语言建模和多项选择题 (MCQ) 两种评估任务。我们免费分享此数据集，并提供更新方法。此外，我们探索了前缀调优法，发现单个前缀能可靠编码单个事实，且前缀容量随长度和模型大小增长。

> Teaching new information to pre-trained large language models (PLM) is a crucial but challenging task. Model adaptation techniques, such as fine-tuning and parameter-efficient training have been shown to store new facts at a slow rate; continual learning is an option but is costly and prone to catastrophic forgetting. This work studies and quantifies how PLM may learn and remember new world knowledge facts that do not occur in their pre-training corpus, which only contains world knowledge up to a certain date. To that purpose, we first propose Novel-WD, a new dataset consisting of sentences containing novel facts extracted from recent Wikidata updates, along with two evaluation tasks in the form of causal language modeling and multiple choice questions (MCQ). We make this dataset freely available to the community, and release a procedure to later build new versions of similar datasets with up-to-date information. We also explore the use of prefix-tuning for novel information learning, and analyze how much information can be stored within a given prefix. We show that a single fact can reliably be encoded within a single prefix, and that the prefix capacity increases with its length and with the base model size.

[Arxiv](https://arxiv.org/abs/2408.17070)