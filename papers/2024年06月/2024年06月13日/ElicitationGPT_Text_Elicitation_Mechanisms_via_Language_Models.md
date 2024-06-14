# ElicitationGPT：语言模型驱动的文本诱导技术

发布时间：2024年06月13日

`Agent

这篇论文摘要描述了一种使用大型语言模型ChatGPT来评估文本与真实文本的吻合度，并验证其是否符合人类偏好的方法。这种应用涉及到使用ChatGPT作为一个智能代理（Agent）来执行特定的任务，即评分和验证文本。因此，它属于Agent分类。虽然这个过程中使用了大型语言模型，但重点在于模型的应用而非理论研究，因此不属于LLM理论或LLM应用。同时，这个过程并不涉及到检索增强生成（RAG）技术，所以也不属于RAG分类。` `信息提取`

> ElicitationGPT: Text Elicitation Mechanisms via Language Models

# 摘要

> 评分规则，作为激励信息提取和机器学习模型训练的基石，用于衡量概率预测与实际状态的吻合度。本文创新性地利用大型语言模型ChatGPT，通过领域知识无关的查询，对提取文本与真实文本进行评分，并验证其是否符合人类偏好。实证研究聚焦于同行评分数据集中的同行评审，并与教师的评分进行对比分析。

> Scoring rules evaluate probabilistic forecasts of an unknown state against the realized state and are a fundamental building block in the incentivized elicitation of information and the training of machine learning models. This paper develops mechanisms for scoring elicited text against ground truth text using domain-knowledge-free queries to a large language model (specifically ChatGPT) and empirically evaluates their alignment with human preferences. The empirical evaluation is conducted on peer reviews from a peer-grading dataset and in comparison to manual instructor scores for the peer reviews.

[Arxiv](https://arxiv.org/abs/2406.09363)