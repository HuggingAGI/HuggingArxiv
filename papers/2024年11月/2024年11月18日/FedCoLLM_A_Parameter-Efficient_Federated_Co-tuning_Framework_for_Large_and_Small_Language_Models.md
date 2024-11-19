# FedCoLLM：针对大型和小型语言模型的参数高效联邦协同调优框架

发布时间：2024年11月18日

`LLM应用` `联邦学习`

> FedCoLLM: A Parameter-Efficient Federated Co-tuning Framework for Large and Small Language Models

# 摘要

> 通过让大型语言模型（LLMs）适配特定领域任务，或者用特定领域知识丰富它们，我们就能充分发挥 LLMs 的能力。不过，在实现服务器端的 LLM 与下游客户端的小型语言模型（SLMs）相互同时增强方面，仍存在差距。为此，我们提出了 FedCoLLM，这是一个新颖且参数高效的联邦框架，专门用于协同调整 LLMs 和 SLMs。该方法旨在将服务器端 LLMs 的知识自适应地传递给客户端的 SLMs，同时用来自客户端的领域见解丰富 LLMs。为达此目的，FedCoLLM 结合 SLMs 运用轻量级适配器，在尊重数据隐私的同时促进服务器与客户端之间的知识交流，还能将计算和通信开销降至最低。我们利用各种公共 LLMs 和 SLMs 在一系列 NLP 文本生成任务中对 FedCoLLM 进行评估，结果显示在 LLMs 的助力下，客户端 SLMs 的性能显著提升。同时，经 FedCoLLM 增强的 LLMs 性能与直接在客户端数据上微调所得的性能相当。

> By adapting Large Language Models (LLMs) to domain-specific tasks or enriching them with domain-specific knowledge, we can fully harness the capabilities of LLMs. Nonetheless, a gap persists in achieving simultaneous mutual enhancement between the server's LLM and the downstream clients' Small Language Models (SLMs). To address this, we propose FedCoLLM, a novel and parameter-efficient federated framework designed for co-tuning LLMs and SLMs. This approach is aimed at adaptively transferring server-side LLMs knowledge to clients' SLMs while simultaneously enriching the LLMs with domain insights from the clients. To accomplish this, FedCoLLM utilizes lightweight adapters in conjunction with SLMs, facilitating knowledge exchange between server and clients in a manner that respects data privacy while also minimizing computational and communication overhead. Our evaluation of FedCoLLM, utilizing various public LLMs and SLMs across a range of NLP text generation tasks, reveals that the performance of clients' SLMs experiences notable improvements with the assistance of the LLMs. Simultaneously, the LLMs enhanced via FedCoLLM achieves comparable performance to that obtained through direct fine-tuning on clients' data.

[Arxiv](https://arxiv.org/abs/2411.11707)