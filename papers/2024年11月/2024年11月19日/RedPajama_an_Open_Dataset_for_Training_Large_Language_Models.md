# RedPajama：一个用于训练大型语言模型的开放数据集

发布时间：2024年11月19日

`LLM应用` `人工智能` `语言模型`

> RedPajama: an Open Dataset for Training Large Language Models

# 摘要

> 大型语言模型在人工智能、科学及整个社会领域正逐渐成为基石技术，然而有关数据集构成与筛选的最佳策略仍大多难以确定。众多表现出色的模型在数据集管理和模型开发流程方面缺乏透明度，这给完全开放的语言模型发展造成了阻碍。本文中，我们明确了推动开源语言模型发展必须应对的三个核心数据相关挑战。它们分别是：（1）模型开发的透明度，涵盖数据管理过程；（2）获取大量优质数据；（3）提供用于数据集管理和分析的产物及元数据。为应对这些挑战，我们发布了 RedPajama-V1，它是对 LLaMA 训练数据集的开放重现。另外，我们还推出了 RedPajama-V2，这是一个仅基于网络的大规模数据集，由原始未过滤的文本数据以及质量信号和元数据构成。RedPajama 数据集总计包含超过 100 万亿个标记，涉及多个领域，其质量信号有利于数据筛选，旨在促进众多新数据集的开发。到目前为止，这些数据集已用于训练诸如 Snowflake Arctic、Salesforce 的 XGen 以及 AI2 的 OLMo 等在生产中使用的强大语言模型。为深入探究 RedPajama 的质量，我们针对具有高达 16 亿参数的仅解码器语言模型开展了一系列分析和消融研究。我们的发现表明，如何有效利用网络数据的质量信号来管理数据集的高质量子集，突显了 RedPajama 在大规模推进透明且高性能语言模型发展方面的潜力。

> Large language models are increasingly becoming a cornerstone technology in artificial intelligence, the sciences, and society as a whole, yet the optimal strategies for dataset composition and filtering remain largely elusive. Many of the top-performing models lack transparency in their dataset curation and model development processes, posing an obstacle to the development of fully open language models. In this paper, we identify three core data-related challenges that must be addressed to advance open-source language models. These include (1) transparency in model development, including the data curation process, (2) access to large quantities of high-quality data, and (3) availability of artifacts and metadata for dataset curation and analysis. To address these challenges, we release RedPajama-V1, an open reproduction of the LLaMA training dataset. In addition, we release RedPajama-V2, a massive web-only dataset consisting of raw, unfiltered text data together with quality signals and metadata. Together, the RedPajama datasets comprise over 100 trillion tokens spanning multiple domains and with their quality signals facilitate the filtering of data, aiming to inspire the development of numerous new datasets. To date, these datasets have already been used in the training of strong language models used in production, such as Snowflake Arctic, Salesforce's XGen and AI2's OLMo. To provide insight into the quality of RedPajama, we present a series of analyses and ablation studies with decoder-only language models with up to 1.6B parameters. Our findings demonstrate how quality signals for web data can be effectively leveraged to curate high-quality subsets of the dataset, underscoring the potential of RedPajama to advance the development of transparent and high-performing language models at scale.

[Arxiv](https://arxiv.org/abs/2411.12372)