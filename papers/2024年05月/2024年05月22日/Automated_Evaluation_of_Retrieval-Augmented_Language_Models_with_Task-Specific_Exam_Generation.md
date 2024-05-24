# 通过任务特定考试生成，自动化评估检索增强型语言模型

发布时间：2024年05月22日

`RAG

理由：这篇论文主要关注的是检索增强型大型语言模型（RAG）的性能评估方法，特别是通过自动生成的合成考试来精确测量RAG在特定任务上的准确性。这种方法涉及对RAG系统的组件选择和性能优化，以及对影响RAG性能的因素的分析。因此，这篇论文的内容与RAG模型的应用和评估紧密相关，属于RAG分类。` `问答系统` `教育评估`

> Automated Evaluation of Retrieval-Augmented Language Models with Task-Specific Exam Generation

# 摘要

> 我们提出了一种创新方法，用于精确测量检索增强型大型语言模型（RAG）在特定任务上的准确性。该方法通过自动生成的合成考试对RAG进行评估，考试内容为基于任务相关文档库的多项选择题。我们的策略自动化、经济高效、易于理解且稳定，旨在为RAG系统挑选最优组件。借助项目反应理论（IRT），我们评估了考试的质量及其对任务准确性的信息价值，并通过迭代优化，剔除了对模型能力评估不足的问题。我们在四个开放式问答任务上验证了此方法，涵盖了Arxiv摘要、StackExchange问题、AWS DevOps故障排除指南及SEC文件。实验还揭示了影响RAG性能的多种因素，如模型大小、检索机制、提示策略和微调方法。尤为重要的是，我们发现选择合适的检索算法往往比单纯扩大语言模型规模更能显著提升性能。

> We propose a new method to measure the task-specific accuracy of Retrieval-Augmented Large Language Models (RAG). Evaluation is performed by scoring the RAG on an automatically-generated synthetic exam composed of multiple choice questions based on the corpus of documents associated with the task. Our method is an automated, cost-efficient, interpretable, and robust strategy to select the optimal components for a RAG system. We leverage Item Response Theory (IRT) to estimate the quality of an exam and its informativeness on task-specific accuracy. IRT also provides a natural way to iteratively improve the exam by eliminating the exam questions that are not sufficiently informative about a model's ability. We demonstrate our approach on four new open-ended Question-Answering tasks based on Arxiv abstracts, StackExchange questions, AWS DevOps troubleshooting guides, and SEC filings. In addition, our experiments reveal more general insights into factors impacting RAG performance like size, retrieval mechanism, prompting and fine-tuning. Most notably, our findings show that choosing the right retrieval algorithms often leads to bigger performance gains than simply using a larger language model.

[Arxiv](https://arxiv.org/abs/2405.13622)