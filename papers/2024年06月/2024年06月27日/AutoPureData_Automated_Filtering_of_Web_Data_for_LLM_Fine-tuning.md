# AutoPureData：为大型语言模型微调自动化筛选网络数据

发布时间：2024年06月27日

`LLM应用

这篇论文主要讨论了如何通过系统收集网络数据，并利用现有的可信AI模型自动过滤掉不受欢迎的内容，以保证数据的质量和安全性，这对于构建可靠的大型语言模型（LLMs）至关重要。因此，这篇论文的内容更偏向于LLM的应用层面，即如何处理和优化数据以支持LLM的训练和部署。` `数据净化` `人工智能`

> AutoPureData: Automated Filtering of Web Data for LLM Fine-tuning

# 摘要

> 最新可靠的大型语言模型（LLMs）一直是研究的热点。这些模型通常基于固定数据集进行训练和部署，但数据集会随时间而过时。使用网络数据自动训练AI时，数据质量和安全性成为关键问题，因为网络数据中可能包含偏见、垃圾信息等不安全或不受欢迎的内容。纯净的数据是构建可靠模型的基石。若在污染的数据上训练，模型可能会产生不良结果。本研究提出了一种系统，它能够收集网络数据，并借助现有的可信AI模型自动过滤掉不受欢迎的内容。实验中，通过处理一小部分网络数据，该系统展示了其在数据净化方面的有效性。

> Up-to-date and reliable Large Language Models (LLMs) are consistently sought after. Typically, LLMs are trained on a fixed dataset and then deployed. However, the training data continually becomes outdated. Enable automatic training of AI using web data involves significant concerns regarding data quality and safety due to bias, spam, and other unsafe or unwanted text. Pure data is essential for producing reliable models. Training a model on impure data may result in undesirable outcomes. This research proposes a system that collects web data and automatically filters out unwanted text with the assistance of existing trusted AI models. In the experiment, a small sample of web data was collected and filtered, demonstrating the system's effectiveness in purifying the data.

[Arxiv](https://arxiv.org/abs/2406.19271)