# LINKAGE：利用 LLM 对非事实性问答进行多样质量参考的列表排序评估

发布时间：2024年09月23日

`LLM应用` `问答系统`

> LINKAGE: Listwise Ranking among Varied-Quality References for Non-Factoid QA Evaluation via LLMs

# 摘要

> 非事实性问答（NFQA）因答案多样且无客观标准而难以评估。传统自动评估指标如ROUGE或BERTScore无法准确衡量语义相似性。近期，大型语言模型（LLMs）因其卓越的NLP任务表现而被引入NFQA评估。常见方法包括点对点评分和成对比较。受排序方法从点到对再到列表的演变启发，我们提出了一种新的列表排序NFQA评估方法，利用LLMs对候选答案进行排序。对于无多级答案的NF问题，我们借助LLMs生成多样质量的参考答案列表，以提升评估效果。实验结果显示，我们的方法在相关性上显著优于传统自动评分和点对点、成对方法。

> Non-Factoid (NF) Question Answering (QA) is challenging to evaluate due to diverse potential answers and no objective criterion. The commonly used automatic evaluation metrics like ROUGE or BERTScore cannot accurately measure semantic similarities or answers from different perspectives. Recently, Large Language Models (LLMs) have been resorted to for NFQA evaluation due to their compelling performance on various NLP tasks. Common approaches include pointwise scoring of each candidate answer and pairwise comparisons between answers. Inspired by the evolution from pointwise to pairwise to listwise in learning-to-rank methods, we propose a novel listwise NFQA evaluation approach, that utilizes LLMs to rank candidate answers in a list of reference answers sorted by descending quality. Moreover, for NF questions that do not have multi-grade or any golden answers, we leverage LLMs to generate the reference answer list of various quality to facilitate the listwise evaluation. Extensive experimental results on three NFQA datasets, i.e., ANTIQUE, the TREC-DL-NF, and WebGLM show that our method has significantly higher correlations with human annotations compared to automatic scores and common pointwise and pairwise approaches.

[Arxiv](https://arxiv.org/abs/2409.14744)