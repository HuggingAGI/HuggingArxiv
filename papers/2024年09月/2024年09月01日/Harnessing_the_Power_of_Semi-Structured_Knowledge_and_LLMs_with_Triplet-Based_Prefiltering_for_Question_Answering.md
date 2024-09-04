# 结合半结构化知识与基于三元组预过滤的LLM，提升问答能力

发布时间：2024年09月01日

`LLM应用` `产品推荐`

> Harnessing the Power of Semi-Structured Knowledge and LLMs with Triplet-Based Prefiltering for Question Answering

# 摘要

> 大型语言模型（LLM）往往缺乏特定领域知识，即便经过微调也易产生错误信息。为此，我们引入了4StepFocus流程，特别是其预处理步骤，旨在大幅提升LLM的答案准确性。该流程通过引导模型利用其捕捉关系和基础推理的能力，有效整合外部知识。具体而言，4StepFocus通过在半结构化知识库中进行基于三元组的搜索，以直接且可追溯的方式筛选潜在正确答案，随后基于非结构化数据对候选答案进行排序。这一方法与仅依赖潜在表示的方法形成鲜明对比。4StepFocus的步骤包括：1) 利用LLM生成三元组提取关系数据，2) 通过知识图谱替换三元组中的变量以缩小候选答案范围，3) 利用向量相似性搜索结合非结构化数据对候选答案进行排序，4) 结合背景数据由LLM对最佳候选进行重新排序。实验结果显示，该方法在医学、产品推荐及学术论文搜索等领域表现出色，不仅增强了信息的可追溯性，更在性能上超越了现有顶尖方法。本文开辟了一个新的研究方向，为未来的深入探索提供了广阔空间。相关源代码已公开在https://github.com/kramerlab/4StepFocus。

> Large Language Models (LLMs) frequently lack domain-specific knowledge and even fine-tuned models tend to hallucinate. Hence, more reliable models that can include external knowledge are needed. We present a pipeline, 4StepFocus, and specifically a preprocessing step, that can substantially improve the answers of LLMs. This is achieved by providing guided access to external knowledge making use of the model's ability to capture relational context and conduct rudimentary reasoning by themselves. The method narrows down potentially correct answers by triplets-based searches in a semi-structured knowledge base in a direct, traceable fashion, before switching to latent representations for ranking those candidates based on unstructured data. This distinguishes it from related methods that are purely based on latent representations. 4StepFocus consists of the steps: 1) Triplet generation for extraction of relational data by an LLM, 2) substitution of variables in those triplets to narrow down answer candidates employing a knowledge graph, 3) sorting remaining candidates with a vector similarity search involving associated non-structured data, 4) reranking the best candidates by the LLM with background data provided. Experiments on a medical, a product recommendation, and an academic paper search test set demonstrate that this approach is indeed a powerful augmentation. It not only adds relevant traceable background information from information retrieval, but also improves performance considerably in comparison to state-of-the-art methods. This paper presents a novel, largely unexplored direction and therefore provides a wide range of future work opportunities. Used source code is available at https://github.com/kramerlab/4StepFocus.

[Arxiv](https://arxiv.org/abs/2409.00861)