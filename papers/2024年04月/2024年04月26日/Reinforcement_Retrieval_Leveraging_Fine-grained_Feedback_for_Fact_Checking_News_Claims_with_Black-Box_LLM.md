# 本文介绍了一种强化检索方法，该方法通过细粒度反馈来优化黑盒大型语言模型在事实核查新闻声明方面的性能。

发布时间：2024年04月26日

`LLM应用`

> Reinforcement Retrieval Leveraging Fine-grained Feedback for Fact Checking News Claims with Black-Box LLM

# 摘要

> 检索增强型语言模型在自然语言处理（NLP）的多个领域，尤其是在关键事实任务中，表现出了显著的潜力。但是，由于高级大型语言模型（LLM）的不可预测性以及特定任务的监督信号缺乏检索导向，使得在黑箱LLM环境下训练检索模型遭遇了不小的挑战。为了提升新闻声明的事实核查能力，我们提出了一种新颖的方法——细粒度反馈与强化检索（FFRR），它利用黑箱LLM来优化事实核查过程。FFRR通过两级策略，从LLM获取细粒度的反馈信息，这些信息随后作为优化检索策略的奖励信号，通过评估检索文档与任务非检索基准真相的一致性来进行。我们在两个公共数据集上对模型进行了评估，这些数据集专门用于验证现实世界中的新闻声明，评估结果显示FFRR在与强大的LLM支持的基准模型以及非LLM的基准模型相比，实现了显著的性能提升。

> Retrieval-augmented language models have exhibited promising performance across various areas of natural language processing (NLP), including fact-critical tasks. However, due to the black-box nature of advanced large language models (LLMs) and the non-retrieval-oriented supervision signal of specific tasks, the training of retrieval model faces significant challenges under the setting of black-box LLM. We propose an approach leveraging Fine-grained Feedback with Reinforcement Retrieval (FFRR) to enhance fact-checking on news claims by using black-box LLM. FFRR adopts a two-level strategy to gather fine-grained feedback from the LLM, which serves as a reward for optimizing the retrieval policy, by rating the retrieved documents based on the non-retrieval ground truth of the task. We evaluate our model on two public datasets for real-world news claim verification, and the results demonstrate that FFRR achieves significant improvements over strong LLM-enabled and non-LLM baselines.

[Arxiv](https://arxiv.org/abs/2404.17283)