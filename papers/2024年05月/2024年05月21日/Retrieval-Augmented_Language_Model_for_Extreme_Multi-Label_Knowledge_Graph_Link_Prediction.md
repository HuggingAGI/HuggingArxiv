# 检索增强型语言模型：应对极端多标签知识图谱链接预测挑战

发布时间：2024年05月21日

`RAG

理由：这篇论文主要探讨了如何通过检索增强技术（Retrieval-Augmented Generation, RAG）结合知识图谱来解决大型语言模型在开放式查询中的外推问题，特别是针对多重响应的情况。论文提出了一种新的任务——极端多标签知识图谱链接预测，并展示了如何通过定制化的增强策略和文本数据的融入来提升模型性能。这与RAG技术的核心思想相符，即通过外部知识源增强语言模型的生成能力。因此，这篇论文应归类于RAG。` `知识图谱`

> Retrieval-Augmented Language Model for Extreme Multi-Label Knowledge Graph Link Prediction

# 摘要

> 大型语言模型在开放式查询中的外推面临两大挑战：幻觉现象和训练成本高昂。这些问题在特定领域和个性化数据应用中尤为突出，要求模型既能提供真实回答，又需降低微调成本。现有研究通过将知识图谱信息融入较小语言模型的输入中尝试解决问题，但存在两大缺陷：未能有效提取大型知识图谱中的相关信息，以及对特性各异的图谱采用统一增强策略，导致性能不佳。此外，开放式查询常产生多重响应，使外推更为复杂。为此，我们提出了一项新任务——极端多标签知识图谱链接预测，旨在利用结构化现实知识实现多响应外推。我们的检索器综合实体、关系与文本数据，精准定位相关邻居。实验证明，针对不同特性的知识图谱需定制化增强策略，且文本数据的融入显著提升了模型性能。我们的框架结合了检索增强技术与知识图谱，以精简的参数规模，实现了基于特定知识图谱的高效外推。相关代码已发布于GitHub：https://github.com/exiled1143/Retrieval-Augmented-Language-Model-for-Multi-Label-Knowledge-Graph-Link-Prediction.git

> Extrapolation in Large language models (LLMs) for open-ended inquiry encounters two pivotal issues: (1) hallucination and (2) expensive training costs. These issues present challenges for LLMs in specialized domains and personalized data, requiring truthful responses and low fine-tuning costs. Existing works attempt to tackle the problem by augmenting the input of a smaller language model with information from a knowledge graph (KG). However, they have two limitations: (1) failing to extract relevant information from a large one-hop neighborhood in KG and (2) applying the same augmentation strategy for KGs with different characteristics that may result in low performance. Moreover, open-ended inquiry typically yields multiple responses, further complicating extrapolation. We propose a new task, the extreme multi-label KG link prediction task, to enable a model to perform extrapolation with multiple responses using structured real-world knowledge. Our retriever identifies relevant one-hop neighbors by considering entity, relation, and textual data together. Our experiments demonstrate that (1) KGs with different characteristics require different augmenting strategies, and (2) augmenting the language model's input with textual data improves task performance significantly. By incorporating the retrieval-augmented framework with KG, our framework, with a small parameter size, is able to extrapolate based on a given KG. The code can be obtained on GitHub: https://github.com/exiled1143/Retrieval-Augmented-Language-Model-for-Multi-Label-Knowledge-Graph-Link-Prediction.git

[Arxiv](https://arxiv.org/abs/2405.12656)