# 利用强化调整，大型语言模型能同时检测立场并揭穿谣言

发布时间：2024年06月04日

`LLM应用

这篇论文摘要描述了一个基于大型语言模型（LLMs）的系统JSDRV，用于联合检测立场和验证谣言的多任务学习。该系统通过强化调整框架和混合奖励机制来优化LLM在立场检测（SD）和谣言验证（RV）任务上的性能。这种方法不仅提升了LLMs在联合任务中的性能，还展示了良好的泛化能力，能够适应非LLM作为任务模型的场景。因此，这篇论文属于LLM应用类别，因为它专注于使用LLMs来解决实际的多任务学习问题。` `社交媒体` `谣言检测`

> Reinforcement Tuning for Detecting Stances and Debunking Rumors Jointly with Large Language Models

# 摘要

> 在联合检测立场和验证谣言的多任务学习中，由于需要获取帖子级别的立场数据和声明级别的谣言真实性数据，这一挑战显得尤为艰巨。为此，我们采用大型语言模型（LLMs）作为基础标注工具，针对联合立场检测（SD）和谣言验证（RV）任务，创造性地提出了JSDRV系统。我们设计了一种强化调整框架，旨在提升LLM在SD和RV任务中的联合预测能力。具体而言，我们制定了一套策略，用于筛选LLM在不同级别上标注的数据，并结合混合奖励机制，精选高质量标签，以优化LLM在两项任务上的微调效果。实验结果显示，JSDRV不仅显著提升了LLMs在联合任务中的性能，超越了现有技术，还能适应非LLM作为任务模型的场景，展现出良好的泛化能力。

> Learning multi-task models for jointly detecting stance and verifying rumors poses challenges due to the need for training data of stance at post level and rumor veracity at claim level, which are difficult to obtain. To address this issue, we leverage large language models (LLMs) as the foundation annotators for the joint stance detection (SD) and rumor verification (RV) tasks, dubbed as JSDRV. We introduce a novel reinforcement tuning framework to enhance the joint predictive capabilities of LLM-based SD and RV components. Specifically, we devise a policy for selecting LLM-annotated data at the two levels, employing a hybrid reward mechanism to choose high-quality labels for effective LLM fine-tuning on both tasks. Results demonstrate that JSDRV improves the capabilities of LLMs in the joint tasks, not only outperforming state-of-the-art methods but also generalizing to non-LLMs accommodated as task models.

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x1.png)

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x2.png)

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x3.png)

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x4.png)

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x5.png)

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x6.png)

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x7.png)

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x8.png)

![利用强化调整，大型语言模型能同时检测立场并揭穿谣言](../../../paper_images/2406.02143/x9.png)

[Arxiv](https://arxiv.org/abs/2406.02143)