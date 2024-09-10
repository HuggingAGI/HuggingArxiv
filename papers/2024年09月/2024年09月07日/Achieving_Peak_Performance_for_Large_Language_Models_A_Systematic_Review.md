# 大型语言模型性能巅峰之路：系统性回顾

发布时间：2024年09月07日

`LLM理论` `计算机科学`

> Achieving Peak Performance for Large Language Models: A Systematic Review

# 摘要

> 近年来，大型语言模型（LLM）在自然语言处理（NLP）领域大放异彩。然而，这些模型需要海量参数才能达到高性能，随着模型规模迈向万亿参数，计算和内存成本也随之飙升，令许多研究人员望而却步。本文针对这一挑战，遵循PRISMA声明，对2017年至2023年间的983篇文献进行了系统综述，精选出65篇进行深入分析。我们探讨了优化和加速LLM的策略，涵盖训练、硬件、可扩展性等多个维度，并通过两个案例研究展示了如何在资源有限的情况下，依然保持模型的高性能。

> In recent years, large language models (LLMs) have achieved remarkable success in natural language processing (NLP). LLMs require an extreme amount of parameters to attain high performance. As models grow into the trillion-parameter range, computational and memory costs increase significantly. This makes it difficult for many researchers to access the resources needed to train or apply these models. Optimizing LLM performance involves two main approaches: fine-tuning pre-trained models for specific tasks to achieve state-of-the-art performance, and reducing costs or improving training time while maintaining similar performance. This paper presents a systematic literature review (SLR) following the Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA) statement. We reviewed 65 publications out of 983 from 2017 to December 2023, retrieved from 5 databases. The study presents methods to optimize and accelerate LLMs while achieving cutting-edge results without sacrificing accuracy. We begin with an overview of the development of language modeling, followed by a detailed explanation of commonly used frameworks and libraries, and a taxonomy for improving and speeding up LLMs based on three classes: LLM training, LLM inference, and system serving. We then delve into recent optimization and acceleration strategies such as training optimization, hardware optimization, scalability and reliability, accompanied by the taxonomy and categorization of these strategies. Finally, we provide an in-depth comparison of each class and strategy, with two case studies on optimizing model training and enhancing inference efficiency. These case studies showcase practical approaches to address LLM resource limitations while maintaining performance.

[Arxiv](https://arxiv.org/abs/2409.04833)