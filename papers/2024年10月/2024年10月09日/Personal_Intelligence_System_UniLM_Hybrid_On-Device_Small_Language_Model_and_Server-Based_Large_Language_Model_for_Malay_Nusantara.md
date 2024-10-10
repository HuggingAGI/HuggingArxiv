# UniLM 个人智能系统：结合设备端小型模型与服务器端大型模型，专为马来群岛语言设计。

发布时间：2024年10月09日

`LLM应用` `语言处理` `机器翻译`

> Personal Intelligence System UniLM: Hybrid On-Device Small Language Model and Server-Based Large Language Model for Malay Nusantara

# 摘要

> 在资源有限的环境中，高资源语言模型往往难以满足马来语的特定需求。本文提出了一种个人智能系统，巧妙融合了设备端和服务器端的模型。SLiM-34M专为设备端设计，低内存低功耗，而MANYAK-1.3B则负责服务器端任务，两者协同实现高效的语言处理。这些模型在机器翻译、问答等任务中表现出色，尤其是SLiM-34M，在预训练标记减少一半的情况下，准确性仍大幅提升。这项研究打破了“大规模资源是构建有效语言模型的必要条件”的固有观念，为马来语领域带来了资源高效的新模型，SLiM-34M与MANYAK-1.3B的精妙配合功不可没。

> In contexts with limited computational and data resources, high-resource language models often prove inadequate, particularly when addressing the specific needs of Malay languages. This paper introduces a Personal Intelligence System designed to efficiently integrate both on-device and server-based models. The system incorporates SLiM-34M for on-device processing, optimized for low memory and power usage, and MANYAK-1.3B for server-based tasks, allowing for scalable, high-performance language processing. The models achieve significant results across various tasks, such as machine translation, question-answering, and translate IndoMMLU. Particularly noteworthy is SLiM-34M's ability to achieve a high improvement in accuracy compared to other LLMs while using 2 times fewer pre-training tokens. This work challenges the prevailing assumption that large-scale computational resources are necessary to build effective language models, contributing to the development of resource-efficient models for the Malay language with the unique orchestration between SLiM-34M and MANYAK-1.3B.

[Arxiv](https://arxiv.org/abs/2410.06973)