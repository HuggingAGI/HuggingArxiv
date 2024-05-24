# UDKAG：为大型视觉-语言模型注入最新知识

发布时间：2024年05月23日

`LLM应用

这篇论文介绍了一种即插即用框架UDKAG，旨在提升大型视觉-语言模型（LVLMs）在处理最新知识相关的视觉问答（VQA）任务时的能力。该框架通过互联网搜索在推理时为模型注入最新知识，并通过训练一个分层过滤模型来从搜索引擎结果中筛选出最有价值的信息，以更新模型知识库。此外，论文还开发了一套自动生成新闻相关VQA样本的流程，并构建了UDK-VQA数据集。这些内容表明该论文主要关注于LLM的实际应用，特别是在增强模型对最新信息的处理能力方面，因此属于LLM应用分类。` `视觉问答` `知识更新`

> UDKAG: Augmenting Large Vision-Language Models with Up-to-Date Knowledge

# 摘要

> 大型视觉-语言模型（LVLMs）因资源需求巨大而难以频繁更新，对最新信息如LLaVA系列一无所知，常在关键时刻失效。例如，2024年1月发布的LVLM对同年2月上映的《沙丘2》剧情一无所知。为此，我们提出了一种创新方法——互联网增强生成（IAG），在推理时通过网络搜索为模型注入最新知识，这一技术已在GPT-4V等商业模型中应用，但其运作细节仍不为人知。本文介绍了一种即插即用框架UDKAG，旨在提升LVLMs在处理最新知识相关的视觉问答（VQA）任务时的能力。我们训练了一个分层过滤模型，能从搜索引擎结果中精准筛选出最有价值的信息，以更新模型知识库。同时，我们开发了一套自动生成新闻相关VQA样本的流程，构建了UDK-VQA数据集，并采用多模型投票机制评估网站内容的有用性，以此训练模型。实验证明，我们的框架在准确性上超越了GPT-4V约25%。

> Large vision-language models (LVLMs) are ignorant of the up-to-date knowledge, such as LLaVA series, because they cannot be updated frequently due to the large amount of resources required, and therefore fail in many cases. For example, if a LVLM was released on January 2024, and it wouldn't know the detailed plot of the new movie Dune 2, which wasn't released until February 2024. To solve the problem, a promising solution is to provide LVLMs with up-to-date knowledge via internet search during inference, i.e., internet-augmented generation (IAG), which is already integrated in some closed-source commercial LVLMs such as GPT-4V. However, the specific mechanics underpinning them remain a mystery. In this paper, we propose a plug-and-play framework, for augmenting existing LVLMs in handling visual question answering (VQA) about up-to-date knowledge, dubbed UDKAG. A hierarchical filtering model is trained to effectively and efficiently find the most helpful content from the websites returned by a search engine to prompt LVLMs with up-to-date knowledge. To train the model and evaluate our framework's performance, we propose a pipeline to automatically generate news-related VQA samples to construct a dataset, dubbed UDK-VQA. A multi-model voting mechanism is introduced to label the usefulness of website/content for VQA samples to construct the training set. Experimental results demonstrate the effectiveness of our framework, outperforming GPT-4V by about 25% in accuracy.

[Arxiv](https://arxiv.org/abs/2405.14554)