# [ViTCN 是一种视觉Transformer对比网络，专为推理任务设计。]

发布时间：2024年03月14日

`Agent` `心理学` `教育学`

> ViTCN: Vision Transformer Contrastive Network For Reasoning

> 机器学习模型已在多个领域取得卓越成就，如计算机视觉模型在物体识别上表现非凡，而大型语言模型如 GPT 能够与人类般自如地展开对话。然而，对AI而言，抽象推理仍是一大挑战，它们是否真能像人一样思考，这个问题尚待解答。Raven 进阶矩阵测试（RPM）是一项专门评估人类推理能力的标准，它包含一组由八个图像构成的问题集，参与者需找出这些图像间的内在规律，并从八个候选选项中选出最符合逻辑的一项来完整序列。此测试广泛应用在衡量人类推理力和智商上。针对这一挑战，有研究者提出一个名为RAVEN的数据集，用以检验机器学习模型的抽象推理性能。本文中，我们构建了一个基于先前对比感知推理网络（CoPiNet）工作的Vision Transformer对比网络，它引入了来自心理学、认知学及教育学的对比效应，在排列不变模型解决Raven进阶矩阵问题上确立了新的标准，并在此基础上运用先进的Vision Transformer架构进行拓展。这一整合旨在深化机器从RAVEN数据集的像素级输入和全局特征中理解和推理时空信息的能力。

> Machine learning models have achieved significant milestones in various domains, for example, computer vision models have an exceptional result in object recognition, and in natural language processing, where Large Language Models (LLM) like GPT can start a conversation with human-like proficiency. However, abstract reasoning remains a challenge for these models, Can AI really thinking like a human? still be a question yet to be answered. Raven Progressive Matrices (RPM) is a metric designed to assess human reasoning capabilities. It presents a series of eight images as a problem set, where the participant should try to discover the underlying rules among these images and select the most appropriate image from eight possible options that best completes the sequence. This task always be used to test human reasoning abilities and IQ. Zhang et al proposed a dataset called RAVEN which can be used to test Machine Learning model abstract reasoning ability. In this paper, we purposed Vision Transformer Contrastive Network which build on previous work with the Contrastive Perceptual Inference network (CoPiNet), which set a new benchmark for permutationinvariant models Raven Progressive Matrices by incorporating contrast effects from psychology, cognition, and education, and extends this foundation by leveraging the cutting-edge Vision Transformer architecture. This integration aims to further refine the machine ability to process and reason about spatial-temporal information from pixel-level inputs and global wise features on RAVEN dataset.

[Arxiv](https://arxiv.org/abs/2403.09962)