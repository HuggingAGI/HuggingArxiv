# FedMKT：大型与小型语言模型的联邦互知识转移技术

发布时间：2024年06月04日

`LLM应用

理由：这篇论文介绍了一种名为FedMKT的框架，该框架旨在通过联邦学习的方式，实现大型语言模型（LLMs）与小型语言模型（SLMs）之间的知识转移，以提升两者的性能。这种方法直接应用于语言模型的实际使用和优化中，属于LLM的具体应用场景，因此归类为LLM应用。` `机器学习`

> FedMKT: Federated Mutual Knowledge Transfer for Large and Small Language Models

# 摘要

> 近期，联邦学习大型语言模型（LLMs）的研究重点在于，让客户端能够协同微调本地同质LLMs，或是将服务器端LLMs的知识传递给下游的小型语言模型（SLMs）。但在同时提升服务器LLM与客户端SLMs方面，仍存在明显不足。为此，我们推出了FedMKT，一个专为大、小语言模型设计的参数高效联邦互知识转移框架。该框架能自适应地将服务器LLM的知识传递给客户端SLMs，并同时吸收客户端的独特领域知识以丰富LLM。我们采用最小编辑距离（MinED）进行令牌对齐，进而实现客户端SLMs与服务器LLM之间的选择性知识互换，以期共同提升性能。通过在异构、同质及一对一三种场景下的大量实验，我们利用多种公共LLMs和SLMs在各类NLP文本生成任务上验证了FedMKT的效果。实验结果表明，在LLM的助力下，客户端SLMs的性能得到了显著提升。此外，经FedMKT优化的LLM性能与基于客户端数据的直接微调相当，充分展现了FedMKT的效能与适应性。

> Recent research in federated large language models (LLMs) has primarily focused on enabling clients to fine-tune their locally deployed homogeneous LLMs collaboratively or on transferring knowledge from server-based LLMs to small language models (SLMs) at downstream clients. However, a significant gap remains in the simultaneous mutual enhancement of both the server's LLM and clients' SLMs. To bridge this gap, we propose FedMKT, a parameter-efficient federated mutual knowledge transfer framework for large and small language models. This framework is designed to adaptively transfer knowledge from the server's LLM to clients' SLMs while concurrently enriching the LLM with clients' unique domain insights. We facilitate token alignment using minimum edit distance (MinED) and then selective mutual knowledge transfer between client-side SLMs and a server-side LLM, aiming to collectively enhance their performance. Through extensive experiments across three distinct scenarios, heterogeneous, homogeneous, and one-to-one, we evaluate the effectiveness of FedMKT using various public LLMs and SLMs on a range of NLP text generation tasks. Empirical results demonstrate significant performance improvements in clients' SLMs with the aid of the LLM. Furthermore, the LLM optimized by FedMKT achieves a performance comparable to that achieved through direct fine-tuning based on clients' data, highlighting the effectiveness and adaptability of FedMKT.

![FedMKT：大型与小型语言模型的联邦互知识转移技术](../../../paper_images/2406.02224/fedmkt_framework.png)

[Arxiv](https://arxiv.org/abs/2406.02224)