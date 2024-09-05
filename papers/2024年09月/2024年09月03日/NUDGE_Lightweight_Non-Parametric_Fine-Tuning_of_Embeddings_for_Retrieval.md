# NUDGE：为检索任务提供轻量级、非参数化的嵌入微调方案。

发布时间：2024年09月03日

`RAG` `信息技术` `数据检索`

> NUDGE: Lightweight Non-Parametric Fine-Tuning of Embeddings for Retrieval

# 摘要

> 在预训练模型中进行密集向量嵌入的$k$-最近邻搜索（$k$-NN检索）是文本和图像检索的主流方法，也广泛应用于检索增强生成（RAG）系统。为了提升检索准确性，开发者常对嵌入进行微调。现有策略包括直接微调预训练模型或训练适配器模型以转换其输出，但后者虽高效却牺牲了准确性。我们提出的NUDGE方法，通过直接调整数据记录的嵌入，不仅大幅提升了$k$-NN检索的准确性，而且在效率上也显著优于现有方法。我们对NUDGE进行了深入的理论与实验分析，证明即使在NP难问题背景下，通过合理约束，NUDGE仍能高效运行且避免语义扭曲。实验结果显示，NUDGE在多个预训练模型和标准数据集上，不仅提升了检索性能，而且在速度和准确性上均大幅超越传统微调方法。

> $k$-Nearest Neighbor search on dense vector embeddings ($k$-NN retrieval) from pre-trained embedding models is the predominant retrieval method for text and images, as well as Retrieval-Augmented Generation (RAG) pipelines. In practice, application developers often fine-tune the embeddings to improve their accuracy on the dataset and query workload in hand. Existing approaches either fine-tune the pre-trained model itself or, more efficiently, but at the cost of accuracy, train adaptor models to transform the output of the pre-trained model. We present NUDGE, a family of novel non-parametric embedding fine-tuning approaches that are significantly more accurate and efficient than both sets of existing approaches. NUDGE directly modifies the embeddings of data records to maximize the accuracy of $k$-NN retrieval. We present a thorough theoretical and experimental study of NUDGE's non-parametric approach. We show that even though the underlying problem is NP-Hard, constrained variations can be solved efficiently. These constraints additionally ensure that the changes to the embeddings are modest, avoiding large distortions to the semantics learned during pre-training. In experiments across five pre-trained models and nine standard text and image retrieval datasets, NUDGE runs in minutes and often improves NDCG@10 by more than 10% over existing fine-tuning methods. On average, NUDGE provides 3.3x and 4.3x higher increase in accuracy and runs 200x and 3x faster, respectively, over fine-tuning the pre-trained model and training adaptors.

[Arxiv](https://arxiv.org/abs/2409.02343)