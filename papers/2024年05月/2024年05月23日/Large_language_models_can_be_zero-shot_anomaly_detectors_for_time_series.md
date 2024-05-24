# 大型语言模型是否具备零-shot检测时间序列异常的能力？

发布时间：2024年05月23日

`LLM应用

这篇论文探讨了大型语言模型（LLM）在时间序列异常检测这一特定应用领域的使用。文中提出了sigllm框架，并通过实验比较了不同的策略来利用LLM进行异常检测。虽然论文涉及了LLM的具体应用，但并未深入探讨LLM的理论基础或Agent的设计与实现，也没有涉及RAG（Retrieval-Augmented Generation）的相关内容。因此，最合适的分类是LLM应用。` `时间序列分析` `异常检测`

> Large language models can be zero-shot anomaly detectors for time series?

# 摘要

> 最新研究表明，大型语言模型不仅能执行时间序列预测等多种任务，还展现出极高的应用灵活性。本文聚焦于一项挑战性任务——时间序列异常检测，探讨了大型语言模型在此领域的应用。该任务要求模型识别输入序列中的异常部分，并处理时间序列数据而非传统文本。我们提出了sigllm框架，通过时间序列到文本的转换和端到端管道，引导语言模型进行异常检测。实验中，我们采用了两种策略：一是直接提示模型识别异常元素，二是利用模型的预测能力辅助检测。在11个多样化的数据集上，预测方法在F1分数上显著优于提示方法。尽管大型语言模型表现出色，但最先进的深度学习模型在性能上仍领先30%。

> Recent studies have shown the ability of large language models to perform a variety of tasks, including time series forecasting. The flexible nature of these models allows them to be used for many applications. In this paper, we present a novel study of large language models used for the challenging task of time series anomaly detection. This problem entails two aspects novel for LLMs: the need for the model to identify part of the input sequence (or multiple parts) as anomalous; and the need for it to work with time series data rather than the traditional text input. We introduce sigllm, a framework for time series anomaly detection using large language models. Our framework includes a time-series-to-text conversion module, as well as end-to-end pipelines that prompt language models to perform time series anomaly detection. We investigate two paradigms for testing the abilities of large language models to perform the detection task. First, we present a prompt-based detection method that directly asks a language model to indicate which elements of the input are anomalies. Second, we leverage the forecasting capability of a large language model to guide the anomaly detection process. We evaluated our framework on 11 datasets spanning various sources and 10 pipelines. We show that the forecasting method significantly outperformed the prompting method in all 11 datasets with respect to the F1 score. Moreover, while large language models are capable of finding anomalies, state-of-the-art deep learning models are still superior in performance, achieving results 30% better than large language models.

[Arxiv](https://arxiv.org/abs/2405.14755)