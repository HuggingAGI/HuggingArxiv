# GiusBERTo：专为意大利审计法院决定中的个人数据去识别化而设计的法律语言模型

发布时间：2024年06月21日

`Agent

理由：这篇论文介绍了一个专门为意大利法律文件中的个人数据匿名化定制的BERT模型，名为GiusBERTo。该模型通过在特定数据集上训练，能够精准识别并处理敏感信息，同时保持文本的上下文连贯性。这种模型的开发和应用是为了解决特定领域（法律界）的实际问题，即隐私保护与数据利用的平衡。因此，它更符合Agent的分类，即一个专门设计来执行特定任务的智能系统或代理。` `隐私保护`

> GiusBERTo: A Legal Language Model for Personal Data De-identification in Italian Court of Auditors Decisions

# 摘要

> 自然语言处理领域的最新突破展示了BERT等预训练模型在多任务中的卓越表现。我们开发的GiusBERTo，是首个专为意大利法律文件中的个人数据匿名化量身定制的BERT模型。该模型在审计法院的庞大数据集上训练，精准识别并匿名化姓名、日期、地点等敏感信息，同时确保文本的上下文连贯性。在独立测试中，GiusBERTo展现了高达97%的标记级准确率，为意大利法律界提供了一个既精确又专用的工具，有效平衡了隐私保护与数据利用的需求。

> Recent advances in Natural Language Processing have demonstrated the effectiveness of pretrained language models like BERT for a variety of downstream tasks. We present GiusBERTo, the first BERT-based model specialized for anonymizing personal data in Italian legal documents. GiusBERTo is trained on a large dataset of Court of Auditors decisions to recognize entities to anonymize, including names, dates, locations, while retaining contextual relevance. We evaluate GiusBERTo on a held-out test set and achieve 97% token-level accuracy. GiusBERTo provides the Italian legal community with an accurate and tailored BERT model for de-identification, balancing privacy and data protection.

[Arxiv](https://arxiv.org/abs/2406.15032)