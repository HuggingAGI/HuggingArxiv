# 借助大型语言模型，探索结构与知识融合的表示学习，以精准推荐概念

发布时间：2024年05月20日

`Agent

这篇论文主要关注的是如何利用大型语言模型（LLMs）来智能推荐学习概念，这是一个典型的Agent应用场景。论文中提出的结构与知识感知表示学习框架——SKarREC，旨在通过融合人类知识体系和LLMs中的事实知识，以及利用知识图中概念间的先后关系，来构建概念的文本表示。此外，论文还设计了一种基于图的适配器，通过对比学习在知识图上预训练，以获得平滑且结构感知的概念表示，并通过推荐任务微调，形成了一个从文本到知识再到推荐的流畅适应流程。这些内容表明，该论文是在Agent的框架下探讨如何利用LLMs来实现智能推荐系统，因此归类为Agent。` `知识图谱`

> Learning Structure and Knowledge Aware Representation with Large Language Models for Concept Recommendation

# 摘要

> 概念推荐旨在根据学习者的知识状态和人类知识体系，智能推荐下一个学习概念。尽管知识追踪模型能预测知识状态，但以往方法未能有效融合人类知识体系于教育模型设计中。随着大语言模型（LLMs）的飞速发展，众多领域已开始利用LLMs生成和编码文本，并引入外部知识。然而，将LLMs应用于概念推荐面临两大挑战：一是如何构建融合人类知识体系的概念文本；二是如何有效调整非平滑、各向异性的文本编码以适应概念推荐。为此，本文创新性地提出了结构与知识感知表示学习框架——SKarREC。我们不仅利用LLMs中的事实知识，还结合知识图中概念间的先后关系，构建了概念的文本表示。此外，我们设计了一种基于图的适配器，通过对比学习在知识图上预训练，以获得平滑且结构感知的概念表示，并通过推荐任务微调，形成了一个从文本到知识再到推荐的流畅适应流程。实验证明，我们的方法在转换文本编码以适应概念推荐方面表现更佳，广泛实验结果显示了其有效性。

> Concept recommendation aims to suggest the next concept for learners to study based on their knowledge states and the human knowledge system. While knowledge states can be predicted using knowledge tracing models, previous approaches have not effectively integrated the human knowledge system into the process of designing these educational models. In the era of rapidly evolving Large Language Models (LLMs), many fields have begun using LLMs to generate and encode text, introducing external knowledge. However, integrating LLMs into concept recommendation presents two urgent challenges: 1) How to construct text for concepts that effectively incorporate the human knowledge system? 2) How to adapt non-smooth, anisotropic text encodings effectively for concept recommendation? In this paper, we propose a novel Structure and Knowledge Aware Representation learning framework for concept Recommendation (SKarREC). We leverage factual knowledge from LLMs as well as the precedence and succession relationships between concepts obtained from the knowledge graph to construct textual representations of concepts. Furthermore, we propose a graph-based adapter to adapt anisotropic text embeddings to the concept recommendation task. This adapter is pre-trained through contrastive learning on the knowledge graph to get a smooth and structure-aware concept representation. Then, it's fine-tuned through the recommendation task, forming a text-to-knowledge-to-recommendation adaptation pipeline, which effectively constructs a structure and knowledge-aware concept representation. Our method does a better job than previous adapters in transforming text encodings for application in concept recommendation. Extensive experiments on real-world datasets demonstrate the effectiveness of the proposed approach.

[Arxiv](https://arxiv.org/abs/2405.12442)