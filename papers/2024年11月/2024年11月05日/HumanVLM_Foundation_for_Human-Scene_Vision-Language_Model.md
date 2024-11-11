# HumanVLM：人类场景视觉语言模型的基础

发布时间：2024年11月05日

`LLM应用` `视觉语言`

> HumanVLM: Foundation for Human-Scene Vision-Language Model

# 摘要

> 人类场景视觉语言任务在各种社交应用中越来越普遍，但最近的进展主要依赖于专门为个别任务定制的模型。新兴研究表明，大型视觉语言模型（VLMs）可以提高各种下游视觉语言理解任务的性能。然而，通用领域模型在专业领域往往表现不佳。本研究引入了一个特定领域的大型视觉语言模型，即人类场景视觉语言模型（HumanVLM），旨在为人类场景视觉语言任务提供基础。具体而言，（1）我们从互联网创建了一个大规模的人类场景多模态图像 - 文本数据集（HumanCaption-10M），以促进特定领域的对齐；（2）开发了一种以人为中心的图像字幕方法，捕捉人脸、身体和背景，并构建了一个高质量的人类场景图像 - 文本数据集（HumanCaptionHQ，约 311k 对），其中包含尽可能多的关于人的详细信息；（3）使用 HumanCaption-10M 和 HumanCaptionHQ，我们训练了一个 HumanVLM。在实验中，我们随后在各种下游任务中评估了我们的 HumanVLM，它在规模相当的多模态模型中表现出优越的整体性能，特别是在与人相关的任务中表现出色，并显著优于类似模型，包括 Qwen2VL 和 ChatGPT-4o。HumanVLM 以及所介绍的数据将刺激人类周边领域的研究。

> Human-scene vision-language tasks are increasingly prevalent in diverse social applications, yet recent advancements predominantly rely on models specifically tailored to individual tasks. Emerging research indicates that large vision-language models (VLMs) can enhance performance across various downstream vision-language understanding tasks. However, general-domain models often underperform in specialized fields. This study introduces a domain-specific Large Vision-Language Model, Human-Scene Vision-Language Model (HumanVLM), designed to provide a foundation for human-scene Vision-Language tasks. Specifically, (1) we create a large-scale human-scene multimodal image-text dataset (HumanCaption-10M) sourced from the Internet to facilitate domain-specific alignment; (2) develop a captioning approach for human-centered images, capturing human faces, bodies, and backgrounds, and construct a high-quality Human-Scene image-text dataset (HumanCaptionHQ, about 311k pairs) that contain as much detailed information as possible about human; (3) Using HumanCaption-10M and HumanCaptionHQ, we train a HumanVLM. In the experiments, we then evaluate our HumanVLM across varous downstream tasks, where it demonstrates superior overall performance among multimodal models of comparable scale, particularly excelling in human-related tasks and significantly outperforming similar models, including Qwen2VL and ChatGPT-4o. HumanVLM, alongside the data introduced, will stimulate the research in human-around fields.

[Arxiv](https://arxiv.org/abs/2411.03034)