# VisRAG：多模态文档上的视觉检索增强生成

发布时间：2024年10月14日

`RAG` `文档处理` `多模态学习`

> VisRAG: Vision-based Retrieval-augmented Generation on Multi-modality Documents

# 摘要

> Retrieval-augmented generation (RAG) 让大型语言模型 (LLM) 能够借助外部知识源进行生成，但现有系统仅依赖文本，无法利用视觉信息如布局和图像，这些在多模态文档中至关重要。本文提出的 VisRAG，通过构建基于视觉-语言模型 (VLM) 的 RAG 流程，直接将文档作为图像嵌入并检索，从而增强生成效果。相比传统文本 RAG，VisRAG 避免了解析过程中的信息损失，更全面地保留了原始文档的信息。实验显示，VisRAG 在检索和生成阶段均超越传统 RAG，端到端性能提升达 25-39%。VisRAG 不仅有效利用训练数据，还展现出强大的泛化能力，成为多模态文档 RAG 的理想选择。代码和数据已公开，详见 https://github.com/openbmb/visrag。

> Retrieval-augmented generation (RAG) is an effective technique that enables large language models (LLMs) to utilize external knowledge sources for generation. However, current RAG systems are solely based on text, rendering it impossible to utilize vision information like layout and images that play crucial roles in real-world multi-modality documents. In this paper, we introduce VisRAG, which tackles this issue by establishing a vision-language model (VLM)-based RAG pipeline. In this pipeline, instead of first parsing the document to obtain text, the document is directly embedded using a VLM as an image and then retrieved to enhance the generation of a VLM. Compared to traditional text-based RAG, VisRAG maximizes the retention and utilization of the data information in the original documents, eliminating the information loss introduced during the parsing process. We collect both open-source and synthetic data to train the retriever in VisRAG and explore a variety of generation methods. Experiments demonstrate that VisRAG outperforms traditional RAG in both the retrieval and generation stages, achieving a 25--39\% end-to-end performance gain over traditional text-based RAG pipeline. Further analysis reveals that VisRAG is effective in utilizing training data and demonstrates strong generalization capability, positioning it as a promising solution for RAG on multi-modality documents. Our code and data are available at https://github.com/openbmb/visrag .

[Arxiv](https://arxiv.org/abs/2410.10594)