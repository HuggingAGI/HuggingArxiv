# IT支持事件解决推荐系统：基于检索增强生成技术

发布时间：2024年09月06日

`RAG` `IT支持` `AIOps`

> Retrieval Augmented Generation-Based Incident Resolution Recommendation System for IT Support

# 摘要

> 在 IT 支持和 AIOps 领域实施生成式 AI 时，客户常面临领域覆盖和模型大小的双重挑战。由于成本和隐私顾虑，他们可能放弃使用如 GPT-4 这样的大型专有模型，转而选择覆盖面较小的较小模型。检索增强生成（RAG）为此提供了解决方案：通过检索系统获取领域知识，供小型生成模型利用。我们为 IT 支持领域的客户设计了一个系统，结合 RAG 进行答案生成、仅编码器模型分类和大型语言模型查询生成。本文详细介绍了系统架构、数据处理、开发过程、初步验证、部署计划及评估策略，并总结了实践中的经验教训。

> Clients wishing to implement generative AI in the domain of IT Support and AIOps face two critical issues: domain coverage and model size constraints due to model choice limitations. Clients might choose to not use larger proprietary models such as GPT-4 due to cost and privacy concerns and so are limited to smaller models with potentially less domain coverage that do not generalize to the client's domain. Retrieval augmented generation is a common solution that addresses both of these issues: a retrieval system first retrieves the necessary domain knowledge which a smaller generative model leverages as context for generation. We present a system developed for a client in the IT Support domain for support case solution recommendation that combines retrieval augmented generation (RAG) for answer generation with an encoder-only model for classification and a generative large language model for query generation. We cover architecture details, data collection and annotation, development journey and preliminary validations, expected final deployment process and evaluation plans, and finally lessons learned.

[Arxiv](https://arxiv.org/abs/2409.13707)