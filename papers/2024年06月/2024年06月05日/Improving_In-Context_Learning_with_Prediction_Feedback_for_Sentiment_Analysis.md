# 利用预测反馈优化情境学习，以增强情感分析的效果

发布时间：2024年06月05日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在情感分析领域的应用，特别是在通过情境学习（ICL）和反馈机制来提高情感解读准确性的方法。研究通过引入先前预测与反馈机制，优化了LLMs的情感理解能力，并在实验中展示了其相较于传统方法的性能提升。因此，这篇论文属于LLM应用类别，因为它专注于LLMs在特定任务（情感分析）中的实际应用和改进。` `情感分析`

> Improving In-Context Learning with Prediction Feedback for Sentiment Analysis

# 摘要

> 大型语言模型（LLMs）在情感分析领域借助情境学习（ICL）取得了显著进展，但捕捉微妙情感的能力仍有待提升。借鉴人类通过反馈调整理解的方式，本研究引入先前预测与反馈机制，旨在改善LLMs的情感解读准确性。研究框架分为三步：首先收集LLMs的初始预测，其次根据预测准确性设计反馈，最后通过反馈驱动的提示优化情感理解。实验结果显示，相较于传统ICL方法，我们的框架在九个情感分析数据集上平均F1分数提升了5.95%，表现更佳。

> Large language models (LLMs) have achieved promising results in sentiment analysis through the in-context learning (ICL) paradigm. However, their ability to distinguish subtle sentiments still remains a challenge. Inspired by the human ability to adjust understanding via feedback, this paper enhances ICL by incorporating prior predictions and feedback, aiming to rectify sentiment misinterpretation of LLMs. Specifically, the proposed framework consists of three steps: (1) acquiring prior predictions of LLMs, (2) devising predictive feedback based on correctness, and (3) leveraging a feedback-driven prompt to refine sentiment understanding. Experimental results across nine sentiment analysis datasets demonstrate the superiority of our framework over conventional ICL methods, with an average F1 improvement of 5.95%.

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/confusion_matrix_chatgpt_rest.png)

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/confusion_matrix_chatgpt_twemo.png)

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/x1.png)

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/x2.png)

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/ratio_new.png)

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/x3.png)

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/x4.png)

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/x5.png)

![利用预测反馈优化情境学习，以增强情感分析的效果](../../../paper_images/2406.02911/combined_plot_new.png)

[Arxiv](https://arxiv.org/abs/2406.02911)