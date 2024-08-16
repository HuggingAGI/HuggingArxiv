# DaRec：大型语言模型与推荐系统解耦对齐的创新框架

发布时间：2024年08月15日

`LLM理论` `推荐系统` `人工智能`

> DaRec: A Disentangled Alignment Framework for Large Language Model and Recommender System

# 摘要

> 大型语言模型 (LLM) 凭借其强大的推理能力，在推荐系统中表现出色。为了从 LLM 中提炼知识以强化协同模型，研究者采用了对比学习等技术进行表示对齐。然而，我们发现直接对齐 LLM 与协同模型的表示并非最佳方案，这一结论基于信息论。因此，如何有效对齐这两者间的语义表示仍是一个未解之谜。受此启发，我们设计了一个创新的即插即用对齐框架。该框架首先通过投影层和表示正则化，将 LLM 和协同模型的潜在表示分解为特定与共享组件，然后对共享表示进行全局与局部结构对齐，以促进知识迁移。理论证明，这种分解能包含更多相关信息，减少无关信息，从而提升推荐任务的效能。实验结果显示，我们的方法超越了现有顶尖算法。

> Benefiting from the strong reasoning capabilities, Large language models (LLMs) have demonstrated remarkable performance in recommender systems. Various efforts have been made to distill knowledge from LLMs to enhance collaborative models, employing techniques like contrastive learning for representation alignment. In this work, we prove that directly aligning the representations of LLMs and collaborative models is sub-optimal for enhancing downstream recommendation tasks performance, based on the information theorem. Consequently, the challenge of effectively aligning semantic representations between collaborative models and LLMs remains unresolved. Inspired by this viewpoint, we propose a novel plug-and-play alignment framework for LLMs and collaborative models. Specifically, we first disentangle the latent representations of both LLMs and collaborative models into specific and shared components via projection layers and representation regularization. Subsequently, we perform both global and local structure alignment on the shared representations to facilitate knowledge transfer. Additionally, we theoretically prove that the specific and shared representations contain more pertinent and less irrelevant information, which can enhance the effectiveness of downstream recommendation tasks. Extensive experimental results on benchmark datasets demonstrate that our method is superior to existing state-of-the-art algorithms.

[Arxiv](https://arxiv.org/abs/2408.08231)