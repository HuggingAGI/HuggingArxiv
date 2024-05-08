# 精简缓存：无线边缘网络中的共享参数AI模型缓存技术在这项研究中，我们提出了一种名为“精简缓存”的新型技术，它旨在优化无线边缘网络中的AI模型缓存策略。通过共享参数，我们的方法能够更高效地利用网络资源，同时提供快速的AI服务响应。这种方法特别适用于资源受限的边缘环境，能够在保证性能的同时，减少对网络带宽和存储的需求。

发布时间：2024年05月07日

`LLM应用

这篇论文探讨了在边缘服务器上缓存AI模型，特别是大型语言模型（LLM）的参数共享策略，以提高存储效率和缓存命中率。它提出了一种新的模型放置策略，即参数共享模型缓存（TrimCaching），并针对特定情况设计了多项式时间算法。这种方法旨在优化多边缘无线网络中的模型服务延迟和存储效率，属于LLM在实际应用中的优化技术，因此归类为LLM应用。` `移动网络` `人工智能`

> TrimCaching: Parameter-sharing AI Model Caching in Wireless Edge Networks

# 摘要

> 下一代移动网络将加速AI模型向终端用户的下载。通过边缘服务器上的模型缓存，网络能够以低延迟向用户提供模型，这一模式被称为边缘模型缓存。本文提出了一种创新的模型放置策略——参数共享模型缓存（TrimCaching），它发现众多AI模型，如卷积神经网络和大型语言模型，其参数块中蕴含的可复用知识可以共享，从而提升存储效率。我们设计了一个参数共享模型放置问题，旨在通过权衡存储效率与服务延迟，提高多边缘无线网络的缓存命中率。尽管该问题属于受限的子模块最大化问题，缺乏多项式时间近似解，但我们针对实践中常见的特殊情况——少量参数块在模型间共享，提出了一种具有$\left(1-ε\right)/2$近似保证的多项式时间算法。对于一般情况，我们则采用贪婪算法解决。模拟结果显示，TrimCaching框架在缓存命中率上远超未利用AI模型共享参数的现有内容缓存技术。

> Next-generation mobile networks are expected to facilitate fast AI model downloading to end users. By caching models on edge servers, mobile networks can deliver models to end users with low latency, resulting in a paradigm called edge model caching. In this paper, we develop a novel model placement scheme, called parameter-sharing model caching (TrimCaching). TrimCaching exploits the key observation that a wide range of AI models, such as convolutional neural networks or large language models, can share a significant proportion of parameter blocks containing reusable knowledge, thereby improving storage efficiency. To this end, we formulate a parameter-sharing model placement problem to maximize the cache hit ratio in multi-edge wireless networks by balancing the fundamental tradeoff between storage efficiency and service latency. We show that the formulated problem is a submodular maximization problem with submodular constraints, for which no polynomial-time approximation algorithm exists. To overcome this challenge, we study an important special case, where a small fixed number of parameter blocks are shared across models, which often holds in practice. In such a case, a polynomial-time algorithm with $\left(1-ε\right)/2$-approximation guarantee is developed. Subsequently, we address the original problem for the general case by developing a greedy algorithm. Simulation results demonstrate that the proposed TrimCaching framework significantly improves the cache hit ratio compared with state-of-the-art content caching without exploiting shared parameters in AI models.

[Arxiv](https://arxiv.org/abs/2405.03990)