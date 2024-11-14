# CLaSP：从自然语言监督中学习时间序列信号的概念

发布时间：2024年11月13日

`LLM应用` `时间序列`

> CLaSP: Learning Concepts for Time-Series Signals from Natural Language Supervision

# 摘要

> 这篇论文提出了一个名为“CLaSP”的基础模型，它能够使用描述信号特征的自然语言作为查询来搜索时间序列信号。以前用自然语言表示时间序列信号数据的努力在设计传统的时间序列信号特征类别、制定其量化以及创建同义词词典方面存在挑战。为了克服这些限制，所提出的方法引入了一种基于对比学习的神经网络。这个网络首先使用由时间序列信号及其相应的自然语言描述组成的数据集 TRUCE 和 SUSHI 进行训练。以前的研究已经提出了数据分析师用来描述信号特征的词汇表，而 SUSHI 旨在涵盖这些术语。我们相信在这些数据集上训练的神经网络将使数据分析师能够使用自然语言词汇进行搜索。此外，我们的方法不需要预定义的同义词词典，并且利用了嵌入在大规模语言模型（LLM）中的常识知识。实验结果表明，CLaSP 能够对时间序列信号数据进行自然语言搜索，并且能够准确地学习信号数据发生变化的点。

> This paper proposes a foundation model called "CLaSP" that can search time series signals using natural language that describes the characteristics of the signals as queries. Previous efforts to represent time series signal data in natural language have had challenges in designing a conventional class of time series signal characteristics, formulating their quantification, and creating a dictionary of synonyms. To overcome these limitations, the proposed method introduces a neural network based on contrastive learning. This network is first trained using the datasets TRUCE and SUSHI, which consist of time series signals and their corresponding natural language descriptions. Previous studies have proposed vocabularies that data analysts use to describe signal characteristics, and SUSHI was designed to cover these terms. We believe that a neural network trained on these datasets will enable data analysts to search using natural language vocabulary. Furthermore, our method does not require a dictionary of predefined synonyms, and it leverages common sense knowledge embedded in a large-scale language model (LLM). Experimental results demonstrate that CLaSP enables natural language search of time series signal data and can accurately learn the points at which signal data changes.

[Arxiv](https://arxiv.org/abs/2411.08397)