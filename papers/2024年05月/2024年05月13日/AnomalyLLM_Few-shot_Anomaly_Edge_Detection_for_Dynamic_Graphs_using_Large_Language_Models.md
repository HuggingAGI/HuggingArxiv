# AnomalyLLM：大型语言模型助力动态图的少样本异常边缘精准捕捉

发布时间：2024年05月13日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）来解决动态图中的异常边检测问题，特别是在标记样本稀缺的情况下。它提出了一种名为AnomalyLLM的方法，该方法通过预训练的动态感知编码器和词嵌入原型来捕捉和重塑边的特征，并构建了一个上下文学习框架来实现少样本异常检测。这种方法的应用性质和对LLMs的实际使用表明它属于LLM应用类别。` `网络安全` `AIOps`

> AnomalyLLM: Few-shot Anomaly Edge Detection for Dynamic Graphs using Large Language Models

# 摘要

> 动态图中的异常边检测旨在揭示那些偏离常规的边，其应用广泛，涵盖网络安全、金融交易和AIOps等领域。然而，随着时间的推移，异常边的种类日益增多，而每种异常的标记样本却寥寥无几。现有方法或专注于随机插入边的检测，或依赖大量标记数据进行训练，这在现实应用中显得力不从心。本文中，我们借助大型语言模型（LLMs）的深厚知识，提出了AnomalyLLM方法。AnomalyLLM通过预训练的动态感知编码器捕捉边的特征，并利用词嵌入原型对边进行重塑。此外，我们还构建了一个结合少量标记样本信息的上下文学习框架，以实现高效的少样本异常检测。实验结果显示，AnomalyLLM不仅在少样本异常检测上表现出色，而且在新出现的异常上无需模型参数更新即可取得卓越效果。

> Detecting anomaly edges for dynamic graphs aims to identify edges significantly deviating from the normal pattern and can be applied in various domains, such as cybersecurity, financial transactions and AIOps. With the evolving of time, the types of anomaly edges are emerging and the labeled anomaly samples are few for each type. Current methods are either designed to detect randomly inserted edges or require sufficient labeled data for model training, which harms their applicability for real-world applications. In this paper, we study this problem by cooperating with the rich knowledge encoded in large language models(LLMs) and propose a method, namely AnomalyLLM. To align the dynamic graph with LLMs, AnomalyLLM pre-trains a dynamic-aware encoder to generate the representations of edges and reprograms the edges using the prototypes of word embeddings. Along with the encoder, we design an in-context learning framework that integrates the information of a few labeled samples to achieve few-shot anomaly detection. Experiments on four datasets reveal that AnomalyLLM can not only significantly improve the performance of few-shot anomaly detection, but also achieve superior results on new anomalies without any update of model parameters.

[Arxiv](https://arxiv.org/abs/2405.07626)