# 为解决长尾知识难题，本研究致力于探索自动问题与答案生成技术，旨在高效精准地生成针对海量且分布稀疏的长尾知识的问题与答案对。

发布时间：2024年03月02日

`LLM应用`

> Automatic Question-Answer Generation for Long-Tail Knowledge

# 摘要

> 近年来，预训练LLMs因能有效处理开放领域问题回答而备受瞩目，尤其在解答常识性问题上表现卓越。然而，对于不常见的长尾知识（尾部实体），LLMs的学习能力仍显不足。受限于人工构建QA数据集所需的巨大成本，当前可获取的QA数据集种类有限，难以全面评估LLMs在处理尾部实体上的性能。为此，本文创新性地提出一种自动构建针对尾部实体的专业QA数据集方法，并探讨了该过程中所面临的科研挑战。通过在我们新生成的长尾QA数据集上运用预训练LLMs进行深入广泛的实验，比较了它们在利用或不利用诸如Wikipedia和Wikidata等外部知识图谱资源情况下的性能差异。

> Pretrained Large Language Models (LLMs) have gained significant attention for addressing open-domain Question Answering (QA). While they exhibit high accuracy in answering questions related to common knowledge, LLMs encounter difficulties in learning about uncommon long-tail knowledge (tail entities). Since manually constructing QA datasets demands substantial human resources, the types of existing QA datasets are limited, leaving us with a scarcity of datasets to study the performance of LLMs on tail entities. In this paper, we propose an automatic approach to generate specialized QA datasets for tail entities and present the associated research challenges. We conduct extensive experiments by employing pretrained LLMs on our newly generated long-tail QA datasets, comparing their performance with and without external resources including Wikipedia and Wikidata knowledge graphs.

[Arxiv](https://arxiv.org/abs/2403.01382)