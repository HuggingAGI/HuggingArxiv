# 本研究致力于深入探究电子商务排名系统的鲁棒性，旨在全面分析和提升该系统在复杂环境下的稳定性和可靠性。

发布时间：2024年03月07日

`Agent`

> Towards Robustness Analysis of E-Commerce Ranking System

> 在各类应用中，信息检索扮演着核心角色，而机器学习的进步已使ML算法成功应用于信息检索领域，尤其是在排名系统的设计中。尽管许多研究专注于基于ML的排名系统鲁棒性，却鲜有关注商业电商系统，且未建立实际场景与人为操控查询的相关性桥梁。本篇论文率先进行了首个关于电商排名系统鲁棒性的系统化实证研究，其中鲁棒性被定义为对语义等价查询保持稳定的排序输出。为量化评估这一鲁棒性，我们创新性地提出一种综合考量当前缺失的排序位置及商品特有信息的新度量标准。通过运用真实电商环境下的大规模数据进行深入研究，我们揭示出对于语义相同的查询，其排序结果往往不一致，这意味着提升鲁棒性有着广阔的空间。基于以上观察，我们建议采取如利用大型语言模型等多种策略来增强系统鲁棒性。值得注意的是，此处探讨的鲁棒性问题并非错误或遗漏的表现，而是在面临丰富多样的选项时，系统可能呈现出多种同样具有吸引力的商品排列组合，但也可能导致消费者困扰。鉴于电商商家正不断优化搜索结果的质量，我们期望这项研究能为衡量排名系统的鲁棒性提供宝贵的参考依据。

> Information retrieval (IR) is a pivotal component in various applications. Recent advances in machine learning (ML) have enabled the integration of ML algorithms into IR, particularly in ranking systems. While there is a plethora of research on the robustness of ML-based ranking systems, these studies largely neglect commercial e-commerce systems and fail to establish a connection between real-world and manipulated query relevance. In this paper, we present the first systematic measurement study on the robustness of e-commerce ranking systems. We define robustness as the consistency of ranking outcomes for semantically identical queries. To quantitatively analyze robustness, we propose a novel metric that considers both ranking position and item-specific information that are absent in existing metrics. Our large-scale measurement study with real-world data from e-commerce retailers reveals an open opportunity to measure and improve robustness since semantically identical queries often yield inconsistent ranking results. Based on our observations, we propose several solution directions to enhance robustness, such as the use of Large Language Models. Note that the issue of robustness discussed herein does not constitute an error or oversight. Rather, in scenarios where there exists a vast array of choices, it is feasible to present a multitude of products in various permutations, all of which could be equally appealing. However, this extensive selection may lead to customer confusion. As e-commerce retailers use various techniques to improve the quality of search results, we hope that this research offers valuable guidance for measuring the robustness of the ranking systems.

[Arxiv](https://arxiv.org/abs/2403.04257)