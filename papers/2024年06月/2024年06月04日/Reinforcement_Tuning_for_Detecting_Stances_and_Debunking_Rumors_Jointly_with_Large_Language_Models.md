# 利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。

发布时间：2024年06月04日

`Agent

理由：这篇论文主要描述了一个基于大型语言模型（LLMs）的系统，名为JSDRV，用于联合检测立场和验证谣言。该系统通过引入一个强化调整框架来提升LLM在两个任务上的性能。这个系统可以被视为一个Agent，因为它能够执行特定的任务（立场检测和谣言验证），并且通过策略和奖励机制进行自我调整和优化。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论。` `社交媒体` `谣言检测`

> Reinforcement Tuning for Detecting Stances and Debunking Rumors Jointly with Large Language Models

# 摘要

> 由于获取帖子级别的立场数据和声明级别的谣言真实性数据困难重重，联合检测立场与验证谣言的多任务学习面临挑战。为此，我们采用大型语言模型（LLMs）作为联合立场检测与谣言验证任务的基础标注工具，命名为JSDRV。我们创新性地引入了一个强化调整框架，旨在提升LLM在SD和RV任务中的联合预测能力。具体而言，我们设计了一套策略，用于挑选LLM在不同层级标注的数据，并结合混合奖励机制，精选高质量标签，以实现对LLM在两项任务上的高效微调。实验结果显示，JSDRV不仅显著提升了LLMs在联合任务中的性能，超越了现有技术，还能适应非LLM作为任务模型的情况，展现出良好的泛化能力。

> Learning multi-task models for jointly detecting stance and verifying rumors poses challenges due to the need for training data of stance at post level and rumor veracity at claim level, which are difficult to obtain. To address this issue, we leverage large language models (LLMs) as the foundation annotators for the joint stance detection (SD) and rumor verification (RV) tasks, dubbed as JSDRV. We introduce a novel reinforcement tuning framework to enhance the joint predictive capabilities of LLM-based SD and RV components. Specifically, we devise a policy for selecting LLM-annotated data at the two levels, employing a hybrid reward mechanism to choose high-quality labels for effective LLM fine-tuning on both tasks. Results demonstrate that JSDRV improves the capabilities of LLMs in the joint tasks, not only outperforming state-of-the-art methods but also generalizing to non-LLMs accommodated as task models.

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x1.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x2.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x3.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x4.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x5.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x6.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x7.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x8.png)

![利用强化调整，大型语言模型能有效检测立场并揭穿谣言，实现双重目标。](../../../paper_images/2406.02143/x9.png)

[Arxiv](https://arxiv.org/abs/2406.02143)