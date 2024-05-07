# R4：为检索增强型的大型语言模型设计的强化检索器、重排器与响应器

发布时间：2024年05月04日

`LLM应用` `信息检索`

> R4: Reinforced Retriever-Reorder-Responder for Retrieval-Augmented Large Language Models

# 摘要

> 增强检索的大型语言模型（LLMs）通过利用信息检索系统获取的内容来生成准确回应，以解决幻觉问题。但现有方法在执行文本生成任务时，往往简单地将相关文档附加至LLMs的提示中，忽略了检索文档与LLMs之间细微的结构语义互动。这一点在处理长篇文档增强的输入提示时尤为重要，因为LLMs在生成响应时容易出现信息丢失。为此，我们提出了一种新的工作流程——“增强检索器-重排序-响应器”（R^4），旨在为LLMs学习文档排序，以提升其生成能力，同时保持模型参数不变。该学习过程分为两个阶段：文档顺序调整和文档表示增强。文档顺序调整通过图注意力学习，根据响应质量的增强奖励，将文档排序优化至最佳顺序。而文档表示增强则通过文档级梯度对抗学习，进一步提升质量较差的响应的文档表示。大量实验证明，我们的流程在知识密集型任务上的事实问题回答性能优于多个公共数据集上的强基线。相关源代码和训练模型将在论文发表后公开。

> Retrieval-augmented large language models (LLMs) leverage relevant content retrieved by information retrieval systems to generate correct responses, aiming to alleviate the hallucination problem. However, existing retriever-responder methods typically append relevant documents to the prompt of LLMs to perform text generation tasks without considering the interaction of fine-grained structural semantics between the retrieved documents and the LLMs. This issue is particularly important for accurate response generation as LLMs tend to ``lose in the middle'' when dealing with input prompts augmented with lengthy documents. In this work, we propose a new pipeline named ``Reinforced Retriever-Reorder-Responder'' (R$^4$) to learn document orderings for retrieval-augmented LLMs, thereby further enhancing their generation abilities while the large numbers of parameters of LLMs remain frozen. The reordering learning process is divided into two steps according to the quality of the generated responses: document order adjustment and document representation enhancement. Specifically, document order adjustment aims to organize retrieved document orderings into beginning, middle, and end positions based on graph attention learning, which maximizes the reinforced reward of response quality. Document representation enhancement further refines the representations of retrieved documents for responses of poor quality via document-level gradient adversarial learning. Extensive experiments demonstrate that our proposed pipeline achieves better factual question-answering performance on knowledge-intensive tasks compared to strong baselines across various public datasets. The source codes and trained models will be released upon paper acceptance.

![R4：为检索增强型的大型语言模型设计的强化检索器、重排器与响应器](../../../paper_images/2405.02659/x1.png)

![R4：为检索增强型的大型语言模型设计的强化检索器、重排器与响应器](../../../paper_images/2405.02659/x2.png)

![R4：为检索增强型的大型语言模型设计的强化检索器、重排器与响应器](../../../paper_images/2405.02659/x3.png)

![R4：为检索增强型的大型语言模型设计的强化检索器、重排器与响应器](../../../paper_images/2405.02659/x4.png)

![R4：为检索增强型的大型语言模型设计的强化检索器、重排器与响应器](../../../paper_images/2405.02659/x5.png)

[Arxiv](https://arxiv.org/abs/2405.02659)