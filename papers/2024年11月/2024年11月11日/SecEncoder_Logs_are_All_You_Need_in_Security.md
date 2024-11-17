# SecEncoder：于安全领域而言，日志便是您的全部所需。

发布时间：2024年11月11日

`LLM应用` `语言模型`

> SecEncoder: Logs are All You Need in Security

# 摘要

> 大型和小型语言模型（LMs）通常借助大量文本进行预训练，这些文本源于像维基百科、图书语料库之类可公开访问的平台，或者通过网络爬虫获取。因接触了广泛的语言数据，这些模型具备出色的泛化能力，能同时执行众多任务。但由于训练数据宽泛，在特定领域任务中它们常表现欠佳。本文引入了 SecEncoder，这是一个专门用安全日志预训练的小型语言模型。SecEncoder 旨在解决一般 LMs 在特定领域的局限，专注于安全日志中的独特语言和模式。实验结果显示，在各种任务中，SecEncoder 优于 BERTlarge、DeBERTa-v3-large 以及 OpenAI 的 Embedding（textembedding-ada-002）等主要在自然语言上预训练的模型。另外，尽管 SecEncoder 主要基于日志数据预训练，但在诸如事件优先级排序和威胁情报文档检索等除日志分析外的一系列任务中，它的表现比在自然语言上预训练的模型更优。这表明通过日志进行特定领域的预训练能显著提升 LMs 在安全领域的性能。这些发现为未来针对特定安全的 LMs 及其潜在应用的研究开辟了道路。

> Large and Small Language Models (LMs) are typically pretrained using extensive volumes of text, which are sourced from publicly accessible platforms such as Wikipedia, Book Corpus, or through web scraping. These models, due to their exposure to a wide range of language data, exhibit impressive generalization capabilities and can perform a multitude of tasks simultaneously. However, they often fall short when it comes to domain-specific tasks due to their broad training data. This paper introduces SecEncoder, a specialized small language model that is pretrained using security logs. SecEncoder is designed to address the domain-specific limitations of general LMs by focusing on the unique language and patterns found in security logs. Experimental results indicate that SecEncoder outperforms other LMs, such as BERTlarge, DeBERTa-v3-large and OpenAI's Embedding (textembedding-ada-002) models, which are pretrained mainly on natural language, across various tasks. Furthermore, although SecEncoder is primarily pretrained on log data, it outperforms models pretrained on natural language for a range of tasks beyond log analysis, such as incident prioritization and threat intelligence document retrieval. This suggests that domain specific pretraining with logs can significantly enhance the performance of LMs in security. These findings pave the way for future research into security-specific LMs and their potential applications.

[Arxiv](https://arxiv.org/abs/2411.07528)