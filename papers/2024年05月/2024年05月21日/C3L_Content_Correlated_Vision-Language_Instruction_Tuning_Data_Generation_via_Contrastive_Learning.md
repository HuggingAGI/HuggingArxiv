# C3L：借助对比学习，打造内容关联的视觉-语言指令调优数据生成方法

发布时间：2024年05月21日

`RAG

理由：这篇论文主要关注的是视觉-语言指令调优（VLIT），并提出了一种基于对比学习的方法（C3L）来提高大型视觉-语言模型（LVLMs）生成VLIT数据的质量。这种方法涉及到模型的调优和改进，特别是在多模态数据处理方面。虽然这与大型语言模型（LLM）有关，但更侧重于模型的应用和改进，特别是通过对比学习来优化模型的性能，这与RAG（Retrieval-Augmented Generation）模型的概念相似，即通过增强检索机制来改善生成模型的性能。因此，将其归类为RAG更为合适。` `人工智能` `机器学习`

> C3L: Content Correlated Vision-Language Instruction Tuning Data Generation via Contrastive Learning

# 摘要

> 视觉-语言指令调优（VLIT）对于大型视觉-语言模型（LVLMs）至关重要。随着开源LVLMs能力的增强，研究人员已开始利用这些模型生成VLIT数据，并取得显著成果。但这种方法面临两大挑战：一是多模态模型易受先验语言知识影响，导致生成的VLIT数据与图像内容相关性不足；二是以往为提升生成能力而增加的额外训练阶段，反而削弱了模型对新输入的适应性。为此，本文提出了一种基于对比学习的创新方法（C3L），通过设计内容相关性模块和引入对比学习，显著提高了LVLMs生成VLIT数据的质量。在多个基准测试中的自动评估结果证实了该方法的有效性。

> Vision-Language Instruction Tuning (VLIT) is a critical training phase for Large Vision-Language Models (LVLMs). With the improving capabilities of open-source LVLMs, researchers have increasingly turned to generate VLIT data by using open-source LVLMs and achieved significant progress. However, such data generation approaches are bottlenecked by the following challenges: 1) Since multi-modal models tend to be influenced by prior language knowledge, directly using LVLMs to generate VLIT data would inevitably lead to low content relevance between generated data and images. 2) To improve the ability of the models to generate VLIT data, previous methods have incorporated an additional training phase to boost the generative capacity. This process hurts the generalization of the models to unseen inputs (i.e., "exposure bias" problem). In this paper, we propose a new Content Correlated VLIT data generation via Contrastive Learning (C3L). Specifically, we design a new content relevance module which enhances the content relevance between VLIT data and images by computing Image Instruction Correspondence Scores S(I2C). Moreover, a contrastive learning module is introduced to further boost the VLIT data generation capability of the LVLMs. A large number of automatic measures on four benchmarks show the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2405.12752)