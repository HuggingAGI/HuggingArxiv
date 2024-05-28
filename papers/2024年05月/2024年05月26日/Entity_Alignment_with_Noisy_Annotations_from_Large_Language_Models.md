# 利用大型语言模型中的噪声标注进行实体对齐

发布时间：2024年05月26日

`Agent

这篇论文主要介绍了一个名为LLM4EA的框架，该框架利用大型语言模型（LLMs）进行实体对齐（EA）任务。它通过创新的主动学习策略和无监督标签精炼器来优化实体对齐过程，减少了对人工标签的依赖，并提高了标签的准确性。这个框架可以被视为一个智能Agent，因为它能够自主地处理和优化任务，而不需要持续的人工干预。因此，这篇论文更适合归类到Agent分类中。` `知识图谱` `数据融合`

> Entity Alignment with Noisy Annotations from Large Language Models

# 摘要

> 实体对齐（EA）旨在通过识别等价实体对来融合两个知识图谱（KGs）。现有方法依赖人工标签，但在实际应用中，聘请跨领域专家进行标注成本高昂。大型语言模型（LLMs）的出现为自动化EA提供了新思路，因其强大的语义处理能力。然而，直接应用LLMs于EA面临挑战，因为现实世界KGs的标注空间庞大，且LLMs可能产生误导性标签。为此，我们提出了LLM4EA框架，有效利用LLMs进行EA。我们设计了一种创新的主动学习策略，通过优先处理KG间和KG内结构中最关键的实体，大幅缩减了标注空间。同时，引入无监督标签精炼器，通过深入概率推理不断提升标签准确性。我们根据基础EA模型的反馈，迭代优化策略。实验结果显示，LLM4EA在四个基准数据集上表现出色，兼具高效、稳健和高效能。

> Entity alignment (EA) aims to merge two knowledge graphs (KGs) by identifying equivalent entity pairs. While existing methods heavily rely on human-generated labels, it is prohibitively expensive to incorporate cross-domain experts for annotation in real-world scenarios. The advent of Large Language Models (LLMs) presents new avenues for automating EA with annotations, inspired by their comprehensive capability to process semantic information. However, it is nontrivial to directly apply LLMs for EA since the annotation space in real-world KGs is large. LLMs could also generate noisy labels that may mislead the alignment. To this end, we propose a unified framework, LLM4EA, to effectively leverage LLMs for EA. Specifically, we design a novel active learning policy to significantly reduce the annotation space by prioritizing the most valuable entities based on the entire inter-KG and intra-KG structure. Moreover, we introduce an unsupervised label refiner to continuously enhance label accuracy through in-depth probabilistic reasoning. We iteratively optimize the policy based on the feedback from a base EA model. Extensive experiments demonstrate the advantages of LLM4EA on four benchmark datasets in terms of effectiveness, robustness, and efficiency.

![利用大型语言模型中的噪声标注进行实体对齐](../../../paper_images/2405.16806/x1.png)

![利用大型语言模型中的噪声标注进行实体对齐](../../../paper_images/2405.16806/x2.png)

![利用大型语言模型中的噪声标注进行实体对齐](../../../paper_images/2405.16806/x3.png)

![利用大型语言模型中的噪声标注进行实体对齐](../../../paper_images/2405.16806/x4.png)

[Arxiv](https://arxiv.org/abs/2405.16806)