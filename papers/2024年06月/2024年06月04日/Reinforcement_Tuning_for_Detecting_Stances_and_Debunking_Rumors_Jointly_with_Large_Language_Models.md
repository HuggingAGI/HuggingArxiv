# 利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。

发布时间：2024年06月04日

`LLM应用

这篇论文摘要描述了一个基于大型语言模型（LLMs）的创新框架JSDRV，用于联合检测立场和验证谣言的多任务学习。该框架通过强化调整和混合奖励机制优化了LLM在特定任务上的性能，并展示了在联合任务中的显著提升。这表明论文主要关注的是LLM在实际应用中的优化和性能提升，因此属于LLM应用分类。` `社交媒体` `谣言检测`

> Reinforcement Tuning for Detecting Stances and Debunking Rumors Jointly with Large Language Models

# 摘要

> 为了应对联合检测立场和验证谣言的多任务学习挑战，我们利用大型语言模型（LLMs）作为基础标注工具，创新性地提出了JSDRV框架。通过引入强化调整框架，我们优化了LLM在SD和RV任务上的联合预测能力。特别地，我们设计了一种策略，用于在帖子和声明两个级别上精选LLM标注的数据，并采用混合奖励机制确保标签质量，从而在两个任务上对LLM进行高效微调。实验结果显示，JSDRV不仅显著提升了LLMs在联合任务中的性能，还超越了现有技术，并能适应非LLM作为任务模型的情况。

> Learning multi-task models for jointly detecting stance and verifying rumors poses challenges due to the need for training data of stance at post level and rumor veracity at claim level, which are difficult to obtain. To address this issue, we leverage large language models (LLMs) as the foundation annotators for the joint stance detection (SD) and rumor verification (RV) tasks, dubbed as JSDRV. We introduce a novel reinforcement tuning framework to enhance the joint predictive capabilities of LLM-based SD and RV components. Specifically, we devise a policy for selecting LLM-annotated data at the two levels, employing a hybrid reward mechanism to choose high-quality labels for effective LLM fine-tuning on both tasks. Results demonstrate that JSDRV improves the capabilities of LLMs in the joint tasks, not only outperforming state-of-the-art methods but also generalizing to non-LLMs accommodated as task models.

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x1.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x2.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x3.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x4.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x5.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x6.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x7.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x8.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重功能。](../../../paper_images/2406.02143/x9.png)

[Arxiv](https://arxiv.org/abs/2406.02143)