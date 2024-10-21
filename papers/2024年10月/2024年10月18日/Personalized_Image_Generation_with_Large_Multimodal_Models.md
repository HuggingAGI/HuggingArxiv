# 个性化图像生成：大型多模态模型的艺术

发布时间：2024年10月18日

`LLM应用` `个性化内容生成` `图像处理`

> Personalized Image Generation with Large Multimodal Models

# 摘要

> 个性化内容过滤，如推荐系统，已成为缓解信息过载的关键。然而，这些系统仅筛选现有内容，受限于其有限多样性，难以满足用户多样化的需求。为此，个性化内容生成应运而生，成为前景广阔的方向。尽管多数研究聚焦于个性化文本生成，但个性化图像生成领域仍显不足。该领域面临从噪声用户交互图像和复杂多模态指令中准确捕捉用户视觉偏好和需求的挑战，且缺乏监督数据。为应对这些挑战，我们提出了Pigeon框架，采用卓越的多模态模型，配备三个专用模块，从用户历史和多模态指令中捕捉视觉偏好和需求。为缓解数据稀缺，我们设计了两阶段偏好对齐方案，包括掩码偏好重建和成对偏好对齐。Pigeon应用于个性化贴纸和电影海报生成，其优越性在广泛的定量结果和人工评估中得以体现。

> Personalized content filtering, such as recommender systems, has become a critical infrastructure to alleviate information overload. However, these systems merely filter existing content and are constrained by its limited diversity, making it difficult to meet users' varied content needs. To address this limitation, personalized content generation has emerged as a promising direction with broad applications. Nevertheless, most existing research focuses on personalized text generation, with relatively little attention given to personalized image generation. The limited work in personalized image generation faces challenges in accurately capturing users' visual preferences and needs from noisy user-interacted images and complex multimodal instructions. Worse still, there is a lack of supervised data for training personalized image generation models.
  To overcome the challenges, we propose a Personalized Image Generation Framework named Pigeon, which adopts exceptional large multimodal models with three dedicated modules to capture users' visual preferences and needs from noisy user history and multimodal instructions. To alleviate the data scarcity, we introduce a two-stage preference alignment scheme, comprising masked preference reconstruction and pairwise preference alignment, to align Pigeon with the personalized image generation task. We apply Pigeon to personalized sticker and movie poster generation, where extensive quantitative results and human evaluation highlight its superiority over various generative baselines.

[Arxiv](https://arxiv.org/abs/2410.14170)