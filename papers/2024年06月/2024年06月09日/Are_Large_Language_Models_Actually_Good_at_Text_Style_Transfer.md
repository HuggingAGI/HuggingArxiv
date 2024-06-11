# 大型语言模型在文本风格转换上真的表现出色吗？

发布时间：2024年06月09日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在文本风格转换（TST）任务中的应用，特别是在情感转移和文本去毒化方面的表现。它分析了模型在不同语言（英语、印地语和孟加拉语）上的性能，并通过零样本、少样本提示及参数高效微调进行了评估。论文的结果强调了开发专门数据集和定制模型以提高TST任务性能的必要性。因此，这篇论文属于LLM应用分类。` `文本处理`

> Are Large Language Models Actually Good at Text Style Transfer?

# 摘要

> 我们对大型语言模型（LLMs）在文本风格转换（TST）任务中的表现进行了深入分析，特别关注情感转移和文本去毒化，涵盖英语、印地语和孟加拉语三种语言。在保持文本核心内容不变的前提下，我们通过零样本、少样本提示及参数高效微调，评估了这些模型在公开数据集上的能力。自动评估、GPT-4及人工评估结果表明，尽管部分LLMs在英语任务中表现出色，但在印地语和孟加拉语等其他语言上的表现仅属一般。然而，通过微调，模型性能大幅提升，超越了零样本和少样本提示的效果，达到了与现有顶尖技术相媲美的水平。这凸显了为实现高效TST，开发专门数据集和定制模型的迫切需求。

> We analyze the performance of large language models (LLMs) on Text Style Transfer (TST), specifically focusing on sentiment transfer and text detoxification across three languages: English, Hindi, and Bengali. Text Style Transfer involves modifying the linguistic style of a text while preserving its core content. We evaluate the capabilities of pre-trained LLMs using zero-shot and few-shot prompting as well as parameter-efficient finetuning on publicly available datasets. Our evaluation using automatic metrics, GPT-4 and human evaluations reveals that while some prompted LLMs perform well in English, their performance in on other languages (Hindi, Bengali) remains average. However, finetuning significantly improves results compared to zero-shot and few-shot prompting, making them comparable to previous state-of-the-art. This underscores the necessity of dedicated datasets and specialized models for effective TST.

[Arxiv](https://arxiv.org/abs/2406.05885)