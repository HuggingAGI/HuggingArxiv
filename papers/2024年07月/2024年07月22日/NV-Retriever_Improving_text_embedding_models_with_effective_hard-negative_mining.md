# NV-Retriever：利用硬负采样技术，提升文本嵌入模型的性能

发布时间：2024年07月22日

`RAG` `信息检索` `问答系统`

> NV-Retriever: Improving text embedding models with effective hard-negative mining

# 摘要

> 文本嵌入模型在信息检索领域广受欢迎，如基于RAG的语义搜索和问答系统。这些模型多为经过对比学习微调的Transformer模型。尽管新架构和训练方法层出不穷，但挖掘负文本的过程仍未得到充分探索。本文提出了一系列正相关感知的挖掘方法，有效去除假负文本，并通过全面的消融研究，探索了不同模型配置下的硬负挖掘方法。我们推出的NV-Retriever-v1模型在MTEB检索基准测试中以60.9分领先，较之前方法提升0.65分，于2024年7月7日发布时位居榜首。

> Text embedding models have been popular for information retrieval applications such as semantic search and Question-Answering systems based on Retrieval-Augmented Generation (RAG). Those models are typically Transformer models that are fine-tuned with contrastive learning objectives. Many papers introduced new embedding model architectures and training approaches, however, one of the key ingredients, the process of mining negative passages, remains poorly explored or described. One of the challenging aspects of fine-tuning embedding models is the selection of high quality hard-negative passages for contrastive learning. In this paper we propose a family of positive-aware mining methods that leverage the positive relevance score for more effective false negatives removal. We also provide a comprehensive ablation study on hard-negative mining methods over their configurations, exploring different teacher and base models. We demonstrate the efficacy of our proposed methods by introducing the NV-Retriever-v1 model, which scores 60.9 on MTEB Retrieval (BEIR) benchmark and 0.65 points higher than previous methods. The model placed 1st when it was published to MTEB Retrieval on July 07, 2024.

![NV-Retriever：利用硬负采样技术，提升文本嵌入模型的性能](../../../paper_images/2407.15831/sampleteaser)

![NV-Retriever：利用硬负采样技术，提升文本嵌入模型的性能](../../../paper_images/2407.15831/sample-franklin)

[Arxiv](https://arxiv.org/abs/2407.15831)