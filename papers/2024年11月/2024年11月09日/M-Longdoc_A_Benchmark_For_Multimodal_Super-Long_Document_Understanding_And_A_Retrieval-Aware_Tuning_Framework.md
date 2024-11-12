# M-Longdoc：用于多模态超长文档理解的基准和检索感知调整框架

发布时间：2024年11月09日

`LLM应用` `文档处理`

> M-Longdoc: A Benchmark For Multimodal Super-Long Document Understanding And A Retrieval-Aware Tuning Framework

# 摘要

> 理解和回答文档相关问题的能力在许多商业和实际应用中可能是有用的。然而，文档通常包含冗长且多样的多模态内容，如文本、图形和表格，这对于人类来说要彻底阅读是非常耗时的。因此，迫切需要开发有效和自动化的方法来帮助人类完成这项任务。在这项工作中，我们引入了 M-LongDoc，这是一个包含 851 个样本的基准，以及一个用于评估大型多模态模型性能的自动化框架。我们还提出了一种检索感知的调整方法，用于高效和有效的多模态文档阅读。与现有工作相比，我们的基准由更新的、长达数百页的文档组成，同时还需要开放式的解决方案，而不仅仅是抽取式的答案。据我们所知，我们的训练框架是第一个直接解决多模态长文档检索设置的框架。为了能够调整开源模型，我们以全自动的方式为这类文档的问答任务构建了一个训练语料库。实验表明，与基线开源模型相比，我们的调整方法使模型响应的正确性相对提高了 4.6%。我们的数据、代码和模型可在 https://multimodal-documents.github.io 上获取。

> The ability to understand and answer questions over documents can be useful in many business and practical applications. However, documents often contain lengthy and diverse multimodal contents such as texts, figures, and tables, which are very time-consuming for humans to read thoroughly. Hence, there is an urgent need to develop effective and automated methods to aid humans in this task. In this work, we introduce M-LongDoc, a benchmark of 851 samples, and an automated framework to evaluate the performance of large multimodal models. We further propose a retrieval-aware tuning approach for efficient and effective multimodal document reading. Compared to existing works, our benchmark consists of more recent and lengthy documents with hundreds of pages, while also requiring open-ended solutions and not just extractive answers. To our knowledge, our training framework is the first to directly address the retrieval setting for multimodal long documents. To enable tuning open-source models, we construct a training corpus in a fully automatic manner for the question-answering task over such documents. Experiments show that our tuning approach achieves a relative improvement of 4.6% for the correctness of model responses, compared to the baseline open-source models. Our data, code, and models are available at https://multimodal-documents.github.io.

[Arxiv](https://arxiv.org/abs/2411.06176)