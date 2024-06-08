# FedMKT：大型与小型语言模型间的联邦互知识转移

发布时间：2024年06月04日

`LLM应用

这篇论文介绍了一种名为FedMKT的框架，它是一种参数联邦互知识转移机制，用于在服务器的大型语言模型（LLMs）和客户端的小型语言模型（SLMs）之间进行知识转移。该框架旨在同时提升服务器LLM和客户端SLMs的性能，通过吸收客户端的独特领域见解，并采用最小编辑距离（MinED）进行令牌对齐，实施选择性知识互换。论文通过实验验证了FedMKT在多种NLP文本生成任务上的有效性，表明了其提升客户端SLMs性能的能力，并且优化后的LLM性能与基于客户端数据的直接微调相媲美。因此，这篇论文属于LLM应用类别，因为它关注的是如何应用LLM技术来改进和优化语言模型的实际应用。` `联邦学习`

> FedMKT: Federated Mutual Knowledge Transfer for Large and Small Language Models

# 摘要

> 近期，联邦学习大型语言模型（LLMs）的研究重点在于让客户端协同微调本地同质LLMs，或从服务器LLMs向客户端小型语言模型（SLMs）转移知识。但在同时提升服务器LLM与客户端SLMs方面，仍存巨大空白。为此，我们推出了FedMKT框架，一种高效的参数联邦互知识转移机制，旨在从服务器LLM向客户端SLMs智能转移知识，同时吸收客户端的独特领域见解。我们采用最小编辑距离（MinED）进行令牌对齐，并实施客户端SLMs与服务器LLM间的选择性知识互换，以共同提升性能。通过在异构、同质及一对一三种场景下的大量实验，我们验证了FedMKT在多种NLP文本生成任务上的有效性。实验结果表明，借助LLM，客户端SLMs的性能显著提升。此外，经FedMKT优化的LLM性能与基于客户端数据的直接微调相媲美，充分展现了FedMKT的效能与适应性。

> Recent research in federated large language models (LLMs) has primarily focused on enabling clients to fine-tune their locally deployed homogeneous LLMs collaboratively or on transferring knowledge from server-based LLMs to small language models (SLMs) at downstream clients. However, a significant gap remains in the simultaneous mutual enhancement of both the server's LLM and clients' SLMs. To bridge this gap, we propose FedMKT, a parameter-efficient federated mutual knowledge transfer framework for large and small language models. This framework is designed to adaptively transfer knowledge from the server's LLM to clients' SLMs while concurrently enriching the LLM with clients' unique domain insights. We facilitate token alignment using minimum edit distance (MinED) and then selective mutual knowledge transfer between client-side SLMs and a server-side LLM, aiming to collectively enhance their performance. Through extensive experiments across three distinct scenarios, heterogeneous, homogeneous, and one-to-one, we evaluate the effectiveness of FedMKT using various public LLMs and SLMs on a range of NLP text generation tasks. Empirical results demonstrate significant performance improvements in clients' SLMs with the aid of the LLM. Furthermore, the LLM optimized by FedMKT achieves a performance comparable to that achieved through direct fine-tuning based on clients' data, highlighting the effectiveness and adaptability of FedMKT.

![FedMKT：大型与小型语言模型间的联邦互知识转移](../../../paper_images/2406.02224/fedmkt_framework.png)

[Arxiv](https://arxiv.org/abs/2406.02224)