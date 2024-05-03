# 本文探讨了利用大型语言模型进行上下文感知聚类的方法。

发布时间：2024年05月01日

`LLM应用` `文本聚类` `电子商务`

> Context-Aware Clustering using Large Language Models

# 摘要

> 大型语言模型（LLMs）在文本理解和生成方面取得了显著成就，但其在文本聚类任务中的应用尚未充分挖掘。我们发现，尽管闭源LLMs能够为实体集合提供优秀的聚类效果，但由于计算资源的庞大需求和成本问题，它们的应用并不具备可扩展性。为此，我们提出了CACTUS——一种创新的系统化方法，它利用开源LLMs来高效执行实体子集的监督聚类，尤其针对基于文本的实体。传统的文本聚类技术往往忽略了实体子集所提供的上下文信息。此外，尽管存在一些基于语言模型的聚类方法，但专为监督聚类任务设计的方法却寥寥无几。本文提出了一种新颖的聚类方法，通过LLMs捕获上下文，并通过一种可扩展的实体间注意力机制实现。我们设计了一种新的增强型三重损失函数，专为监督聚类量身定制，以应对直接应用三重损失函数于此问题的固有难题。同时，我们引入了一种基于文本增强技术的自监督聚类任务，旨在提升模型的泛化性能。在评估过程中，我们从闭源LLM中获取了基准聚类数据，并将这些信息转移到开源LLM中，实现了在监督聚类框架下，使用更快速、成本更低的开源模型来执行相同任务。我们在多个电子商务查询和产品聚类数据集上进行的实验证明，我们的方法在多个外部聚类评估指标上显著超越了现有的无监督和监督基线方法。

> Despite the remarkable success of Large Language Models (LLMs) in text understanding and generation, their potential for text clustering tasks remains underexplored. We observed that powerful closed-source LLMs provide good quality clusterings of entity sets but are not scalable due to the massive compute power required and the associated costs. Thus, we propose CACTUS (Context-Aware ClusTering with aUgmented triplet losS), a systematic approach that leverages open-source LLMs for efficient and effective supervised clustering of entity subsets, particularly focusing on text-based entities. Existing text clustering methods fail to effectively capture the context provided by the entity subset. Moreover, though there are several language modeling based approaches for clustering, very few are designed for the task of supervised clustering. This paper introduces a novel approach towards clustering entity subsets using LLMs by capturing context via a scalable inter-entity attention mechanism. We propose a novel augmented triplet loss function tailored for supervised clustering, which addresses the inherent challenges of directly applying the triplet loss to this problem. Furthermore, we introduce a self-supervised clustering task based on text augmentation techniques to improve the generalization of our model. For evaluation, we collect ground truth clusterings from a closed-source LLM and transfer this knowledge to an open-source LLM under the supervised clustering framework, allowing a faster and cheaper open-source model to perform the same task. Experiments on various e-commerce query and product clustering datasets demonstrate that our proposed approach significantly outperforms existing unsupervised and supervised baselines under various external clustering evaluation metrics.

[Arxiv](https://arxiv.org/abs/2405.00988)