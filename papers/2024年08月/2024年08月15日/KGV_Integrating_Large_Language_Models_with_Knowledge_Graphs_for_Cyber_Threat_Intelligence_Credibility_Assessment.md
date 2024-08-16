# KGV 结合 LLM 与知识图谱，提升网络威胁情报的可信度评估。

发布时间：2024年08月15日

`LLM应用` `网络安全` `威胁情报`

> KGV: Integrating Large Language Models with Knowledge Graphs for Cyber Threat Intelligence Credibility Assessment

# 摘要

> 网络威胁情报是抵御复杂网络攻击的关键工具，但对其质量的评估研究甚少，且依赖专家手动分析。本文提出了一种结合知识图谱和大型语言模型的CTI质量评估框架。我们利用LLM自动提取关键声明进行验证，并通过段落构建的知识图谱进行事实核查，简化了传统复杂的知识图谱构建方式。此外，我们首次公开了威胁情报评估数据集，为研究提供了新视角。实验表明，我们的方法在减少数据标注的同时，显著提升了评估性能，达到了XXX的准确性。

> Cyber threat intelligence is a critical tool that many organizations and individuals use to protect themselves from sophisticated, organized, persistent, and weaponized cyber attacks. However, few studies have focused on the quality assessment of threat intelligence provided by intelligence platforms, and this work still requires manual analysis by cybersecurity experts. In this paper, we propose a knowledge graph-based verifier, a novel Cyber Threat Intelligence (CTI) quality assessment framework that combines knowledge graphs and Large Language Models (LLMs). Our approach introduces LLMs to automatically extract OSCTI key claims to be verified and utilizes a knowledge graph consisting of paragraphs for fact-checking. This method differs from the traditional way of constructing complex knowledge graphs with entities as nodes. By constructing knowledge graphs with paragraphs as nodes and semantic similarity as edges, it effectively enhances the semantic understanding ability of the model and simplifies labeling requirements. Additionally, to fill the gap in the research field, we created and made public the first dataset for threat intelligence assessment from heterogeneous sources. To the best of our knowledge, this work is the first to create a dataset on threat intelligence reliability verification, providing a reference for future research. Experimental results show that KGV (Knowledge Graph Verifier) significantly improves the performance of LLMs in intelligence quality assessment. Compared with traditional methods, we reduce a large amount of data annotation while the model still exhibits strong reasoning capabilities. Finally, our method can achieve XXX accuracy in network threat assessment.

[Arxiv](https://arxiv.org/abs/2408.08088)