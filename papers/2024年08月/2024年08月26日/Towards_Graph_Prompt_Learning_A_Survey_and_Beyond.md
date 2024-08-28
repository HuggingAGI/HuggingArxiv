# 探索图提示学习：调查与展望

发布时间：2024年08月26日

`LLM应用` `社交网络分析` `推荐系统`

> Towards Graph Prompt Learning: A Survey and Beyond

# 摘要

> “预训练与提示学习”范式在大规模应用中展现了卓越的适应性，广泛适用于问答、图像识别及多模态检索等领域。该方法充分发挥了大型预训练模型的优势，降低了下游任务的数据与计算需求，提升了模型在多任务中的灵活性。图作为一种多功能数据结构，在社交网络分析、推荐系统及生物图等领域中至关重要。尽管在NLP和CV领域取得了显著成果，但这一范式在图领域的应用尚处于起步阶段。图数据中节点与边缘特征的分布差异及拓扑结构的多样性，可能导致预训练与下游任务间的兼容性问题。为此，我们致力于总结缓解这些差异的方法，涉及提示设计、技术比较、应用评估及挑战识别。本次调查涵盖了该领域100多项研究，总结了设计原则与最新应用，如文本属性图、分子、蛋白质及推荐系统。通过深入分析，我们旨在为图提示学习提供基础认识，不仅惠及图挖掘领域，更将影响人工通用智能的广泛社群。

> Large-scale "pre-train and prompt learning" paradigms have demonstrated remarkable adaptability, enabling broad applications across diverse domains such as question answering, image recognition, and multimodal retrieval. This approach fully leverages the potential of large-scale pre-trained models, reducing downstream data requirements and computational costs while enhancing model applicability across various tasks. Graphs, as versatile data structures that capture relationships between entities, play pivotal roles in fields such as social network analysis, recommender systems, and biological graphs. Despite the success of pre-train and prompt learning paradigms in Natural Language Processing (NLP) and Computer Vision (CV), their application in graph domains remains nascent. In graph-structured data, not only do the node and edge features often have disparate distributions, but the topological structures also differ significantly. This diversity in graph data can lead to incompatible patterns or gaps between pre-training and fine-tuning on downstream graphs. We aim to bridge this gap by summarizing methods for alleviating these disparities. This includes exploring prompt design methodologies, comparing related techniques, assessing application scenarios and datasets, and identifying unresolved problems and challenges. This survey categorizes over 100 relevant works in this field, summarizing general design principles and the latest applications, including text-attributed graphs, molecules, proteins, and recommendation systems. Through this extensive review, we provide a foundational understanding of graph prompt learning, aiming to impact not only the graph mining community but also the broader Artificial General Intelligence (AGI) community.

[Arxiv](https://arxiv.org/abs/2408.14520)