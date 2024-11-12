# Invar-RAG：用于更好生成的不变的与大型语言模型对齐的检索

发布时间：2024年11月11日

`RAG` `信息检索` `问答系统`

> Invar-RAG: Invariant LLM-aligned Retrieval for Better Generation

# 摘要

> 检索增强生成（RAG）在提供可靠的答案预测和解决幻觉问题方面显示出了令人印象深刻的能力。典型的 RAG 实现使用强大的检索模型来提取外部信息，并使用大型语言模型（LLM）来生成答案。相比之下，最近基于 LLM 的检索因其在信息检索（IR）方面的显著改进而受到关注，这得益于 LLM 的语义理解能力。然而，直接将 LLM 应用于 RAG 系统存在挑战。这可能会导致特征局部性问题，因为大量的参数知识会阻碍对整个语料库中全局信息的有效利用；例如，基于 LLM 的检索器通常输入文档摘要而不是完整的文档。此外，LLM 中的各种预训练任务会引入方差，进一步削弱作为检索器的性能。
为了解决这些问题，我们提出了一种新颖的两阶段微调架构，称为 Invar-RAG。在检索阶段，通过集成基于 LoRA 的表示学习来构建基于 LLM 的检索器，以解决特征局部性问题。为了提高检索性能，我们开发了两种模式（不变模式和可变模式）和一个不变性损失来减少 LLM 的方差。在生成阶段，采用了一种改进的微调方法来提高 LLM 根据检索到的信息生成答案的准确性。实验结果表明，Invar-RAG 在三个开放域问答（ODQA）数据集上显著优于现有的基线。代码可在补充材料中获取以进行重现。

> Retrieval-augmented generation (RAG) has shown impressive capability in providing reliable answer predictions and addressing hallucination problems. A typical RAG implementation uses powerful retrieval models to extract external information and large language models (LLMs) to generate answers. In contrast, recent LLM-based retrieval has gained attention for its substantial improvements in information retrieval (IR) due to the LLMs' semantic understanding capability. However, directly applying LLM to RAG systems presents challenges. This may cause feature locality problems as massive parametric knowledge can hinder effective usage of global information across the corpus; for example, an LLM-based retriever often inputs document summaries instead of full documents. Moreover, various pre-trained tasks in LLMs introduce variance, further weakening performance as a retriever.
  To address these issues, we propose a novel two-stage fine-tuning architecture called Invar-RAG. In the retrieval stage, an LLM-based retriever is constructed by integrating LoRA-based representation learning to tackle feature locality issues. To enhance retrieval performance, we develop two patterns (invariant and variant patterns) and an invariance loss to reduce LLM variance. In the generation stage, a refined fine-tuning method is employed to improve LLM accuracy in generating answers based on retrieved information. Experimental results show that Invar-RAG significantly outperforms existing baselines across three open-domain question answering (ODQA) datasets. Code is available in the Supplementary Material for reproducibility.

[Arxiv](https://arxiv.org/abs/2411.07021)