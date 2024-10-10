# PDF-WuKong：一款高效阅读长 PDF 的大型多模态模型，通过端到端稀疏采样技术实现卓越性能。

发布时间：2024年10月08日

`LLM应用` `学术研究` `文档处理`

> PDF-WuKong: A Large Multimodal Model for Efficient Long PDF Reading with End-to-End Sparse Sampling

# 摘要

> 文档理解任务复杂，涉及大量文本和视觉信息。近期，大型语言模型 (LLM) 的进步显著提升了这一任务的性能。然而，现有方法多聚焦于纯文本或少量文档图像，难以应对长 PDF 文档，尤其是学术论文中的交错文本和图像。为此，我们推出了 PDF-WuKong，一种多模态大型语言模型 (MLLM)，专为长 PDF 文档的多模态问答 (QA) 设计。PDF-WuKong 引入稀疏采样器，同时处理文本和图像，大幅提升 MLLM 的效率和能力。该采样器与图像编码器结合，筛选出与用户查询最相关的段落或图表供语言模型处理。为训练和评估模型，我们构建了 PaperPDF 数据集，包含大量 arXiv 学术论文，并提出多种策略自动生成 100 万个 QA 对及其证据来源。实验显示，我们的方法在长多模态 PDF 理解任务上表现卓越，F1 值平均高出 8.6%，超越了专有产品。代码和数据集将在 https://github.com/yh-hust/PDF-Wukong 发布。

> Document understanding is a challenging task to process and comprehend large amounts of textual and visual information. Recent advances in Large Language Models (LLMs) have significantly improved the performance of this task. However, existing methods typically focus on either plain text or a limited number of document images, struggling to handle long PDF documents with interleaved text and images, especially in academic papers. In this paper, we introduce PDF-WuKong, a multimodal large language model (MLLM) which is designed to enhance multimodal question-answering (QA) for long PDF documents. PDF-WuKong incorporates a sparse sampler that operates on both text and image representations, significantly improving the efficiency and capability of the MLLM. The sparse sampler is integrated with the MLLM's image encoder and selects the paragraphs or diagrams most pertinent to user queries for processing by the language model. To effectively train and evaluate our model, we construct PaperPDF, a dataset consisting of a broad collection of academic papers sourced from arXiv, multiple strategies are proposed to generate automatically 1M QA pairs along with their corresponding evidence sources. Experimental results demonstrate the superiority and high efficiency of our approach over other models on the task of long multimodal PDF understanding, surpassing proprietary products by an average of 8.6% on F1. Our code and dataset will be released at https://github.com/yh-hust/PDF-Wukong.

[Arxiv](https://arxiv.org/abs/2410.05970)