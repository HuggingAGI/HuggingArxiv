# 提升多选题干扰项生成质量，结合检索增强预训练与知识图谱融合技术

发布时间：2024年06月19日

`RAG

理由：该论文摘要中提到的“检索增强预训练”和引入知识图谱以增强生成性能，这些方法与检索增强生成（Retrieval-Augmented Generation, RAG）的概念相吻合。RAG是一种结合了检索和生成的方法，旨在通过检索外部知识来增强语言模型的生成能力。因此，这篇论文更符合RAG分类。` `知识图谱`

> Enhancing Distractor Generation for Multiple-Choice Questions with Retrieval Augmented Pretraining and Knowledge Graph Integration

# 摘要

> 本文针对多选题干扰项生成任务，提出了两项创新设计：一是“检索增强预训练”，优化语言模型预训练，使之更贴合干扰项生成任务；二是引入知识图谱，以增强生成性能。实验结果显示，我们的模型在基准数据集上的表现大幅领先现有技术，最佳模型在MCQ数据集和Sciq数据集上的F1@3分数分别提升至16.47和16.50。

> In this paper, we tackle the task of distractor generation (DG) for multiple-choice questions. Our study introduces two key designs. First, we propose \textit{retrieval augmented pretraining}, which involves refining the language model pretraining to align it more closely with the downstream task of DG. Second, we explore the integration of knowledge graphs to enhance the performance of DG. Through experiments with benchmarking datasets, we show that our models significantly outperform the state-of-the-art results. Our best-performing model advances the F1@3 score from 14.80 to 16.47 in MCQ dataset and from 15.92 to 16.50 in Sciq dataset.

![提升多选题干扰项生成质量，结合检索增强预训练与知识图谱融合技术](../../../paper_images/2406.13578/rap_pretrain_1.png)

![提升多选题干扰项生成质量，结合检索增强预训练与知识图谱融合技术](../../../paper_images/2406.13578/OverviewofKnowledgeAugmentedGeneration.png)

![提升多选题干扰项生成质量，结合检索增强预训练与知识图谱融合技术](../../../paper_images/2406.13578/KGRetrieval.png)

[Arxiv](https://arxiv.org/abs/2406.13578)