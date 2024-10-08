# HiReview：一种基于分层分类的自动文献综述生成方法

发布时间：2024年10月02日

`LLM应用` `学术研究` `文献综述`

> HiReview: Hierarchical Taxonomy-Driven Automatic Literature Review Generation

# 摘要

> 我们推出了 HiReview，一个创新的分层分类驱动自动文献综述生成框架。面对学术文档的爆炸性增长，传统手动综述既费时又费力，而传统摘要模型又难以胜任。大型语言模型 (LLM) 虽潜力巨大，但相关研究仍显不足。为此，我们设计了两阶段方法：先分类后生成，结合图聚类与检索增强 LLM。首先，在引用网络中定位相关子社区，再通过文本与引用关系聚类构建分类树。随后，LLM 为各层级生成精准摘要，确保文献全面且有序。实验证明，HiReview 在分层组织、内容相关性和事实准确性上均超越现有技术，为自动文献综述开辟了新路径。

> In this work, we present HiReview, a novel framework for hierarchical taxonomy-driven automatic literature review generation. With the exponential growth of academic documents, manual literature reviews have become increasingly labor-intensive and time-consuming, while traditional summarization models struggle to generate comprehensive document reviews effectively. Large language models (LLMs), with their powerful text processing capabilities, offer a potential solution; however, research on incorporating LLMs for automatic document generation remains limited. To address key challenges in large-scale automatic literature review generation (LRG), we propose a two-stage taxonomy-then-generation approach that combines graph-based hierarchical clustering with retrieval-augmented LLMs. First, we retrieve the most relevant sub-community within the citation network, then generate a hierarchical taxonomy tree by clustering papers based on both textual content and citation relationships. In the second stage, an LLM generates coherent and contextually accurate summaries for clusters or topics at each hierarchical level, ensuring comprehensive coverage and logical organization of the literature. Extensive experiments demonstrate that HiReview significantly outperforms state-of-the-art methods, achieving superior hierarchical organization, content relevance, and factual accuracy in automatic literature review generation tasks.

[Arxiv](https://arxiv.org/abs/2410.03761)