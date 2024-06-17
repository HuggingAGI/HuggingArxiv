# 多语言答案句子选择数据集

发布时间：2024年06月14日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLM）来解决不同语言之间在答案句子选择（AS2）任务上的性能差距问题。通过使用LLM对英语AS2数据集进行自动机器翻译，作者为多种欧洲语言创建了高质量的AS2数据集，并通过实验验证了这些数据集在构建多语言AS2模型中的有效性。这一应用展示了LLM在跨语言信息处理和提升多语言问答系统性能方面的实际价值，因此属于LLM应用分类。` `问答系统` `机器翻译`

> Datasets for Multilingual Answer Sentence Selection

# 摘要

> 答案句子选择（AS2）对于构建高效的检索式问答系统至关重要。由于其他语言缺乏标注数据集，AS2的研究主要集中在英语上。这种资源不足导致不同语言的AS2模型训练受限，从而在英语与其他语言的问答系统之间形成性能鸿沟。本文中，我们利用大型语言模型（LLM）对英语AS2数据集（如ASNQ、WikiQA和TREC-QA）进行监督自动机器翻译，为法语、德语、意大利语、葡萄牙语和西班牙语这五种欧洲语言创建了高质量的AS2数据集。通过与多种Transformer架构的实验，我们验证了这些翻译数据集的质量及其在构建多语言AS2模型中的关键作用，有效缩小了英语与其他语言在问答系统性能上的差距。

> Answer Sentence Selection (AS2) is a critical task for designing effective retrieval-based Question Answering (QA) systems. Most advancements in AS2 focus on English due to the scarcity of annotated datasets for other languages. This lack of resources prevents the training of effective AS2 models in different languages, creating a performance gap between QA systems in English and other locales. In this paper, we introduce new high-quality datasets for AS2 in five European languages (French, German, Italian, Portuguese, and Spanish), obtained through supervised Automatic Machine Translation (AMT) of existing English AS2 datasets such as ASNQ, WikiQA, and TREC-QA using a Large Language Model (LLM). We evaluated our approach and the quality of the translated datasets through multiple experiments with different Transformer architectures. The results indicate that our datasets are pivotal in producing robust and powerful multilingual AS2 models, significantly contributing to closing the performance gap between English and other languages.

[Arxiv](https://arxiv.org/abs/2406.10172)