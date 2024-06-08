# FedMKT：大型与小型语言模型间的联邦互知识转移

发布时间：2024年06月04日

`LLM应用

理由：这篇论文主要探讨了如何通过FedMKT框架在服务器端的大型语言模型（LLM）和客户端的小型语言模型（SLMs）之间实现有效的知识转移和互增强。这种方法涉及到具体的应用场景和技术实现，如令牌对齐和选择性知识互换，旨在提升模型性能。因此，它属于大型语言模型（LLM）的应用范畴，而不是理论研究或Agent、RAG相关的研究。` `人工智能` `机器学习`

> FedMKT: Federated Mutual Knowledge Transfer for Large and Small Language Models

# 摘要

> 近期研究聚焦于如何让客户端协同微调本地同质大型语言模型，或从服务器端LLM向客户端小型语言模型转移知识。但服务器端LLM与客户端SLMs之间的同步互增强仍是一大挑战。为此，我们开发了FedMKT框架，旨在高效地在大型与小型语言模型间实现互知识转移，同时让LLM吸收客户端的独特领域知识。我们利用最小编辑距离进行令牌对齐，并实现客户端SLMs与服务器端LLM间的选择性知识互换，以提升整体性能。在异构、同质及一对一三种场景下的大量实验表明，FedMKT显著提升了客户端SLMs的性能，且优化后的LLM性能与基于客户端数据的直接微调相媲美，证明了FedMKT的有效性与适应性。

> Recent research in federated large language models (LLMs) has primarily focused on enabling clients to fine-tune their locally deployed homogeneous LLMs collaboratively or on transferring knowledge from server-based LLMs to small language models (SLMs) at downstream clients. However, a significant gap remains in the simultaneous mutual enhancement of both the server's LLM and clients' SLMs. To bridge this gap, we propose FedMKT, a parameter-efficient federated mutual knowledge transfer framework for large and small language models. This framework is designed to adaptively transfer knowledge from the server's LLM to clients' SLMs while concurrently enriching the LLM with clients' unique domain insights. We facilitate token alignment using minimum edit distance (MinED) and then selective mutual knowledge transfer between client-side SLMs and a server-side LLM, aiming to collectively enhance their performance. Through extensive experiments across three distinct scenarios, heterogeneous, homogeneous, and one-to-one, we evaluate the effectiveness of FedMKT using various public LLMs and SLMs on a range of NLP text generation tasks. Empirical results demonstrate significant performance improvements in clients' SLMs with the aid of the LLM. Furthermore, the LLM optimized by FedMKT achieves a performance comparable to that achieved through direct fine-tuning based on clients' data, highlighting the effectiveness and adaptability of FedMKT.

![FedMKT：大型与小型语言模型间的联邦互知识转移](../../../paper_images/2406.02224/fedmkt_framework.png)

[Arxiv](https://arxiv.org/abs/2406.02224)