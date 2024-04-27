# 在不完整的知识图谱问答任务中，我们将大型语言模型（LLM）既视为智能代理，也视为知识库，以生成答案。

发布时间：2024年04月23日

`LLM应用` `知识图谱` `问答系统`

> Generate-on-Graph: Treat LLM as both Agent and KG in Incomplete Knowledge Graph Question Answering

# 摘要

> 为应对大型语言模型（LLMs）知识匮乏和易于产生幻觉的问题，众多研究致力于将LLMs与知识图谱（KGs）相结合。但这些方法多在完备的知识图谱问答（KGQA）环境中进行评估，即每个问题所涉及的事实三元组均被知识图谱全面覆盖。在此环境下，LLMs主要扮演搜索知识图谱以发现答案实体的角色，而非真正融合内外部知识。然而现实情况中，知识图谱往往无法全面覆盖所有问答所需的知识。本文旨在模拟现实世界环境，评估LLMs整合内外部知识的能力，提出了在不完全知识图谱（IKGQA）下进行问答的LLMs应用。在IKGQA中，所给知识图谱并未包含每个问题涉及的所有事实三元组。为此，我们提出了一种无需训练的方法——图上生成（GoG），它能够在探索知识图谱的同时产生新的事实三元组。具体而言，我们构建了一个选择-生成-回答框架，将LLMs视作探索知识图谱的智能体，同时也将其作为能够基于探索到的子图及其内在知识生成新事实的知识图谱。实验结果显示，我们的GoG方法在IKGQA任务上取得了一定成效，而大多数现有方法在此类任务上表现不佳。

> To address the issue of insufficient knowledge and the tendency to generate hallucination in Large Language Models (LLMs), numerous studies have endeavored to integrate LLMs with Knowledge Graphs (KGs). However, all these methods are evaluated on conventional Knowledge Graph Question Answering (KGQA) with complete KGs, where the factual triples involved in each question are entirely covered by the given KG. In this situation, LLM mainly acts as an agent to find answer entities by exploring the KG, rather than effectively integrating internal and external knowledge sources. However, in real-world scenarios, KGs are often incomplete to cover all the knowledge required to answer questions. To simulate real-world scenarios and evaluate the ability of LLMs to integrate internal and external knowledge, in this paper, we propose leveraging LLMs for QA under Incomplete Knowledge Graph (IKGQA), where the given KG doesn't include all the factual triples involved in each question. To handle IKGQA, we propose a training-free method called Generate-on-Graph (GoG) that can generate new factual triples while exploring on KGs. Specifically, we propose a selecting-generating-answering framework, which not only treat the LLM as an agent to explore on KGs, but also treat it as a KG to generate new facts based on the explored subgraph and its inherent knowledge. Experimental results on two datasets demonstrate that our GoG can solve IKGQA to a certain extent, while almost all previous methods cannot perform well on IKGQA.

[Arxiv](https://arxiv.org/abs/2404.14741)