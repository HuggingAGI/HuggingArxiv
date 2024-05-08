# TrimCaching：无线边缘网络中共享参数的AI模型缓存技术在无线边缘网络中，TrimCaching 技术通过共享参数的方式，实现了AI模型的有效缓存，提高了网络的响应速度和处理能力。这种创新的方法不仅优化了资源分配，还增强了边缘计算的智能化水平，为未来的无线通信网络提供了新的发展方向。

发布时间：2024年05月07日

`LLM应用

这篇论文探讨了在边缘计算环境中，如何通过模型缓存策略来提高大型语言模型（LLM）的访问效率和降低延迟。它提出了一种新的模型放置策略，即参数共享模型缓存（TrimCaching），这种策略利用了不同AI模型之间共享参数块的特性，以提高存储效率和缓存命中率。这与LLM的应用场景紧密相关，特别是在优化网络性能和用户体验方面。因此，这篇论文属于LLM应用分类。` `移动网络` `人工智能`

> TrimCaching: Parameter-sharing AI Model Caching in Wireless Edge Networks

# 摘要

> 下一代移动网络将加速AI模型向终端用户的快速下载。通过边缘服务器上的模型缓存，网络能够以低延迟向用户提供模型，这一模式被称为边缘模型缓存。本文提出了一种创新的模型放置策略——参数共享模型缓存（TrimCaching），它揭示了众多AI模型，如卷积神经网络或大型语言模型，能够共享大量包含可复用知识的参数块，从而提升存储效率。我们设计了一个参数共享模型放置问题，旨在通过权衡存储效率与服务延迟，在多边缘无线网络中提升缓存命中率。尽管面临子模块最大化问题的挑战，我们针对实践中常见的小固定数量参数块共享情况，提出了一种具有$\left(1-ε\right)/2$近似保证的多项式时间算法。对于更广泛的情况，我们采用贪婪算法解决原始问题。模拟结果显示，TrimCaching框架在缓存命中率上远超不利用AI模型共享参数的现有内容缓存技术。

> Next-generation mobile networks are expected to facilitate fast AI model downloading to end users. By caching models on edge servers, mobile networks can deliver models to end users with low latency, resulting in a paradigm called edge model caching. In this paper, we develop a novel model placement scheme, called parameter-sharing model caching (TrimCaching). TrimCaching exploits the key observation that a wide range of AI models, such as convolutional neural networks or large language models, can share a significant proportion of parameter blocks containing reusable knowledge, thereby improving storage efficiency. To this end, we formulate a parameter-sharing model placement problem to maximize the cache hit ratio in multi-edge wireless networks by balancing the fundamental tradeoff between storage efficiency and service latency. We show that the formulated problem is a submodular maximization problem with submodular constraints, for which no polynomial-time approximation algorithm exists. To overcome this challenge, we study an important special case, where a small fixed number of parameter blocks are shared across models, which often holds in practice. In such a case, a polynomial-time algorithm with $\left(1-ε\right)/2$-approximation guarantee is developed. Subsequently, we address the original problem for the general case by developing a greedy algorithm. Simulation results demonstrate that the proposed TrimCaching framework significantly improves the cache hit ratio compared with state-of-the-art content caching without exploiting shared parameters in AI models.

[Arxiv](https://arxiv.org/abs/2405.03990)