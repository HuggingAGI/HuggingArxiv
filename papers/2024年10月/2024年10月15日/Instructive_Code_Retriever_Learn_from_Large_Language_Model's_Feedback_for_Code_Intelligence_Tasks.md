# 指导性代码检索器：借助大型语言模型的反馈，提升代码智能任务的表现

发布时间：2024年10月15日

`LLM应用` `软件开发` `人工智能`

> Instructive Code Retriever: Learn from Large Language Model's Feedback for Code Intelligence Tasks

# 摘要

> 近期研究提出，通过 In-Context Learning (ICL) 结合大型语言模型 (LLM)，无需微调即可处理代码智能任务。ICL 利用任务指令和示例演示，指导模型生成准确答案，无需更新参数。尽管 ICL 在代码智能任务中表现出色，但其性能高度依赖于示例选择。以往研究中，BM25 在示例检索方面取得了一定成功，但现有方法难以理解查询的语义和结构信息，导致演示效果不佳。此外，这些方法难以适应用户查询在不同领域中的复杂动态特性。为此，我们提出了一种名为 Instructive Code Retriever (ICR) 的新方法，旨在检索增强模型推理能力的示例。通过基于树的损失函数，ICR 学习语料库的语义和结构信息。我们还结合 LLM 的反馈，优化检索器的训练，以更好地理解查询与示例的关联。实验结果显示，ICR 显著优于现有最先进方法。在代码摘要、程序合成和错误修复等任务中，ICR 的表现均有显著提升，例如在代码摘要任务中，BLEU-4 分别提高了 50.0% 和 90.0%，在程序合成任务中，CodeBLEU 提高了 74.6%，在错误修复任务中，BLEU-4 分别提高了 3.6 和 3.2。

> Recent studies proposed to leverage large language models (LLMs) with In-Context Learning (ICL) to handle code intelligence tasks without fine-tuning. ICL employs task instructions and a set of examples as demonstrations to guide the model in generating accurate answers without updating its parameters. While ICL has proven effective for code intelligence tasks, its performance heavily relies on the selected examples. Previous work has achieved some success in using BM25 to retrieve examples for code intelligence tasks. However, existing approaches lack the ability to understand the semantic and structural information of queries, resulting in less helpful demonstrations. Moreover, they do not adapt well to the complex and dynamic nature of user queries in diverse domains. In this paper, we introduce a novel approach named Instructive Code Retriever (ICR), which is designed to retrieve examples that enhance model inference across various code intelligence tasks and datasets. We enable ICR to learn the semantic and structural information of the corpus by a tree-based loss function. To better understand the correlation between queries and examples, we incorporate the feedback from LLMs to guide the training of the retriever. Experimental results demonstrate that our retriever significantly outperforms state-of-the-art approaches. We evaluate our model's effectiveness on various tasks, i.e., code summarization, program synthesis, and bug fixing. Compared to previous state-of-the-art algorithms, our method achieved improvements of 50.0% and 90.0% in terms of BLEU-4 for two code summarization datasets, 74.6% CodeBLEU on program synthesis dataset, and increases of 3.6 and 3.2 BLEU-4 on two bug fixing datasets.

[Arxiv](https://arxiv.org/abs/2410.11300)