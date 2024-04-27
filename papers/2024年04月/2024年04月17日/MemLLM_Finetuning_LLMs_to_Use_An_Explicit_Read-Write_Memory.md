# MemLLM：为大型语言模型（LLM）定制优化，引入外显式读写记忆功能。

发布时间：2024年04月17日

`LLM理论` `人工智能` `知识管理`

> MemLLM: Finetuning LLMs to Use An Explicit Read-Write Memory

# 摘要

> 当前的大型语言模型（LLMs）在知识密集任务上虽有所建树，但因依赖参数作为隐式存储机制而受限，难以应对知识的罕见性和时间上的衰减问题。参数记忆的晦涩性也使得理解和预防幻觉变得困难。虽然参数记忆池和模型编辑提供了部分解决方案，但检索增强生成（RAG）作为一种非参数化方法，也存在结构性缺失、可解释性复杂化以及存储知识管理困难等问题。本文提出了MemLLM，这是一种创新的方法，通过整合结构化且显式的读写记忆模块来提升LLMs。MemLLM通过允许LLM与记忆进行动态交互，增强了其利用存储知识的能力，有效应对了前述挑战。实验结果证明，MemLLM不仅提升了LLMs在语言建模上的表现，更在知识密集任务中增强了其性能和可解释性。我们视MemLLM为推动LLMs通过记忆增强变得更具事实基础和依据性的关键一步。

> While current large language models (LLMs) demonstrate some capabilities in knowledge-intensive tasks, they are limited by relying on their parameters as an implicit storage mechanism. As a result, they struggle with infrequent knowledge and temporal degradation. In addition, the uninterpretable nature of parametric memorization makes it challenging to understand and prevent hallucination. Parametric memory pools and model editing are only partial solutions. Retrieval Augmented Generation (RAG) $\unicode{x2013}$ though non-parametric $\unicode{x2013}$ has its own limitations: it lacks structure, complicates interpretability and makes it hard to effectively manage stored knowledge. In this paper, we introduce MemLLM, a novel method of enhancing LLMs by integrating a structured and explicit read-and-write memory module. MemLLM tackles the aforementioned challenges by enabling dynamic interaction with the memory and improving the LLM's capabilities in using stored knowledge. Our experiments indicate that MemLLM enhances the LLM's performance and interpretability, in language modeling in general and knowledge-intensive tasks in particular. We see MemLLM as an important step towards making LLMs more grounded and factual through memory augmentation.

![MemLLM：为大型语言模型（LLM）定制优化，引入外显式读写记忆功能。](../../../paper_images/2404.11672/x1.png)

![MemLLM：为大型语言模型（LLM）定制优化，引入外显式读写记忆功能。](../../../paper_images/2404.11672/x2.png)

![MemLLM：为大型语言模型（LLM）定制优化，引入外显式读写记忆功能。](../../../paper_images/2404.11672/x3.png)

![MemLLM：为大型语言模型（LLM）定制优化，引入外显式读写记忆功能。](../../../paper_images/2404.11672/x4.png)

![MemLLM：为大型语言模型（LLM）定制优化，引入外显式读写记忆功能。](../../../paper_images/2404.11672/x5.png)

[Arxiv](https://arxiv.org/abs/2404.11672)