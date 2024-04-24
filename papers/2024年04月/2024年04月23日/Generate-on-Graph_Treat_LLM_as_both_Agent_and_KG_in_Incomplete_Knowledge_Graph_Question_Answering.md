# 在不完整的知识图谱问答任务中，我们将大型语言模型（LLM）视作既是行动者也是知识库。

发布时间：2024年04月23日

`LLM应用` `知识图谱` `问答系统`

> Generate-on-Graph: Treat LLM as both Agent and KG in Incomplete Knowledge Graph Question Answering

# 摘要

> 为应对大型语言模型（LLMs）知识匮乏及易于产生虚构信息的挑战，众多研究致力于将LLMs与知识图谱（KGs）相结合。但这些方法多在完备的知识图谱问答（KGQA）环境中进行评估，即每个问题所涉及的事实三元组均完全包含在给定的KG中。在此环境下，LLMs主要作为搜索KG以寻找答案实体的代理，而非真正融合内外部知识源。然而，现实世界中的知识图谱往往并不完整，无法覆盖所有问答所需的知识。为模拟现实场景并评估LLMs整合知识的能力，本文提出了一种新方法，即使用LLMs在不完整知识图谱（IKGQA）下进行问答，这里的KG并未包含每个问题所涉及的所有事实三元组。为应对IKGQA挑战，我们提出了一种无需训练的方法——在图上生成（GoG），它能够在探索KG的过程中生成新的事实三元组。具体而言，我们构建了一个选择-生成-回答框架，将LLMs既视作探索KG的代理，也视作能够基于探索到的子图及其内在知识生成新事实的KG。在两个数据集上的实验结果显示，我们的GoG方法能够在一定程度上解决IKGQA问题，而大多数现有方法在IKGQA上的表现并不理想。

> To address the issue of insufficient knowledge and the tendency to generate hallucination in Large Language Models (LLMs), numerous studies have endeavored to integrate LLMs with Knowledge Graphs (KGs). However, all these methods are evaluated on conventional Knowledge Graph Question Answering (KGQA) with complete KGs, where the factual triples involved in each question are entirely covered by the given KG. In this situation, LLM mainly acts as an agent to find answer entities by exploring the KG, rather than effectively integrating internal and external knowledge sources. However, in real-world scenarios, KGs are often incomplete to cover all the knowledge required to answer questions. To simulate real-world scenarios and evaluate the ability of LLMs to integrate internal and external knowledge, in this paper, we propose leveraging LLMs for QA under Incomplete Knowledge Graph (IKGQA), where the given KG doesn't include all the factual triples involved in each question. To handle IKGQA, we propose a training-free method called Generate-on-Graph (GoG) that can generate new factual triples while exploring on KGs. Specifically, we propose a selecting-generating-answering framework, which not only treat the LLM as an agent to explore on KGs, but also treat it as a KG to generate new facts based on the explored subgraph and its inherent knowledge. Experimental results on two datasets demonstrate that our GoG can solve IKGQA to a certain extent, while almost all previous methods cannot perform well on IKGQA.

[Arxiv](https://arxiv.org/abs/2404.14741)