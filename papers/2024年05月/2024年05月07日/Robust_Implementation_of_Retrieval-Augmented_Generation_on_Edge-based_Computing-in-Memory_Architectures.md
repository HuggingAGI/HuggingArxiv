# 在内存计算架构的边缘计算环境中，增强检索生成的稳健实现解释：在

发布时间：2024年05月07日

`RAG

这篇论文主要讨论了检索增强生成（RAG）方法在边缘设备上的应用，以及如何通过基于内存计算（CiM）的新框架来提高RAG的效率和可扩展性。它提出了一种结合对比学习和噪声感知训练的鲁棒CiM支持的RAG（RoCR）框架，以加速矩阵乘法并减少数据传输开销。这与大型语言模型（LLM）的应用和理论都有所不同，因为它专注于RAG方法的改进，而不是LLM本身的理论或应用。同时，它也不涉及Agent的概念，因此不属于Agent分类。因此，最合适的分类是RAG。` `边缘计算`

> Robust Implementation of Retrieval-Augmented Generation on Edge-based Computing-in-Memory Architectures

# 摘要

> 边缘设备上的大型语言模型（LLMs）通过微调参数来学习，但这种方法对资源的需求仍然沉重。检索增强生成（RAG）作为一种高效的学习方法，能在不更新模型参数的情况下提升内容质量，但每次用户交互时对配置文件数据的重复搜索会导致延迟和数据累积。传统方法限制了用户数据的大小，影响了RAG的可扩展性。本文提出了一种基于内存计算（CiM）的新框架，通过在内存中直接进行计算来加速矩阵乘法，避免了数据传输的昂贵开销。我们的鲁棒CiM支持的RAG（RoCR）框架，结合了对比学习和噪声感知训练，使RAG能够高效地利用CiM搜索配置文件数据，这是首次尝试利用CiM加速RAG的研究。

> Large Language Models (LLMs) deployed on edge devices learn through fine-tuning and updating a certain portion of their parameters. Although such learning methods can be optimized to reduce resource utilization, the overall required resources remain a heavy burden on edge devices. Instead, Retrieval-Augmented Generation (RAG), a resource-efficient LLM learning method, can improve the quality of the LLM-generated content without updating model parameters. However, the RAG-based LLM may involve repetitive searches on the profile data in every user-LLM interaction. This search can lead to significant latency along with the accumulation of user data. Conventional efforts to decrease latency result in restricting the size of saved user data, thus reducing the scalability of RAG as user data continuously grows. It remains an open question: how to free RAG from the constraints of latency and scalability on edge devices? In this paper, we propose a novel framework to accelerate RAG via Computing-in-Memory (CiM) architectures. It accelerates matrix multiplications by performing in-situ computation inside the memory while avoiding the expensive data transfer between the computing unit and memory. Our framework, Robust CiM-backed RAG (RoCR), utilizing a novel contrastive learning-based training method and noise-aware training, can enable RAG to efficiently search profile data with CiM. To the best of our knowledge, this is the first work utilizing CiM to accelerate RAG.

[Arxiv](https://arxiv.org/abs/2405.04700)