# RAG Foundry：一款专为提升大型语言模型在检索增强生成方面的框架

发布时间：2024年08月05日

`RAG` `软件开发` `人工智能`

> RAG Foundry: A Framework for Enhancing LLMs for Retrieval Augmented Generation

# 摘要

> 构建检索增强生成（RAG）系统复杂且要求高，涉及对数据、应用场景及精细设计决策的深刻理解。评估这些系统同样充满挑战，需综合考量检索精准度与生成质量。为此，我们推出了RAG Foundry开源框架，旨在强化大型语言模型以适应RAG应用。该框架集数据构建、模型训练、推理及评估于一体，简化流程，助力在RAG场景下高效创建和评估数据增强型语言模型。这一整合设计加速了RAG技术的原型开发与实验迭代，让用户能便捷地利用内部或专业知识源生成数据、训练RAG模型。我们通过在三个知识密集型数据集上对Llama-3和Phi-3模型进行多样化RAG配置的增强与微调，验证了框架的有效性，实现了性能的持续提升。相关代码已开放源码，详见https://github.com/IntelLabs/RAGFoundry。

> Implementing Retrieval-Augmented Generation (RAG) systems is inherently complex, requiring deep understanding of data, use cases, and intricate design decisions. Additionally, evaluating these systems presents significant challenges, necessitating assessment of both retrieval accuracy and generative quality through a multi-faceted approach. We introduce RAG Foundry, an open-source framework for augmenting large language models for RAG use cases. RAG Foundry integrates data creation, training, inference and evaluation into a single workflow, facilitating the creation of data-augmented datasets for training and evaluating large language models in RAG settings. This integration enables rapid prototyping and experimentation with various RAG techniques, allowing users to easily generate datasets and train RAG models using internal or specialized knowledge sources. We demonstrate the framework effectiveness by augmenting and fine-tuning Llama-3 and Phi-3 models with diverse RAG configurations, showcasing consistent improvements across three knowledge-intensive datasets. Code is released as open-source in https://github.com/IntelLabs/RAGFoundry.

[Arxiv](https://arxiv.org/abs/2408.02545)