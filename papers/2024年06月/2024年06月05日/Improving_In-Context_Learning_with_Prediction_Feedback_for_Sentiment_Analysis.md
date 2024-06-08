# 借助预测反馈优化情境学习，提升情感分析效果

发布时间：2024年06月05日

`LLM应用

这篇论文摘要描述了一种针对大型语言模型（LLMs）在情感分析领域的应用改进方法。研究通过引入先前预测与反馈机制来提升LLMs对情感的准确解读，这种方法通过三个步骤实现：获取初步预测、设计反馈、通过反馈优化情感理解。实验结果表明，这种方法在情感分析数据集上相比传统情境学习（ICL）方法有显著的性能提升。因此，这篇论文属于LLM应用分类，因为它专注于改进LLMs在特定任务（情感分析）中的应用性能。` `情感分析`

> Improving In-Context Learning with Prediction Feedback for Sentiment Analysis

# 摘要

> 大型语言模型（LLMs）在情感分析领域通过情境学习（ICL）已取得显著成效，但细微情感的辨别仍是一大难题。借鉴人类通过反馈调整理解的能力，本研究引入先前预测与反馈机制，旨在提升LLMs对情感的准确解读。研究提出的框架分为三步：首先获取LLMs的初步预测，其次根据预测的准确性设计反馈，最后通过反馈驱动的提示优化情感理解。实验结果显示，在九个情感分析数据集上，该框架相比传统ICL方法，平均F1分数提升了5.95%，表现更为出色。

> Large language models (LLMs) have achieved promising results in sentiment analysis through the in-context learning (ICL) paradigm. However, their ability to distinguish subtle sentiments still remains a challenge. Inspired by the human ability to adjust understanding via feedback, this paper enhances ICL by incorporating prior predictions and feedback, aiming to rectify sentiment misinterpretation of LLMs. Specifically, the proposed framework consists of three steps: (1) acquiring prior predictions of LLMs, (2) devising predictive feedback based on correctness, and (3) leveraging a feedback-driven prompt to refine sentiment understanding. Experimental results across nine sentiment analysis datasets demonstrate the superiority of our framework over conventional ICL methods, with an average F1 improvement of 5.95%.

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/confusion_matrix_chatgpt_rest.png)

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/confusion_matrix_chatgpt_twemo.png)

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/x1.png)

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/x2.png)

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/ratio_new.png)

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/x3.png)

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/x4.png)

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/x5.png)

![借助预测反馈优化情境学习，提升情感分析效果](../../../paper_images/2406.02911/combined_plot_new.png)

[Arxiv](https://arxiv.org/abs/2406.02911)