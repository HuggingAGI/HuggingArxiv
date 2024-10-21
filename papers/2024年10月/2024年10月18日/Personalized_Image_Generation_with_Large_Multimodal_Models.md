# 个性化图像生成：探索大型多模态模型的无限可能

发布时间：2024年10月18日

`LLM应用` `个性化内容生成` `图像处理`

> Personalized Image Generation with Large Multimodal Models

# 摘要

> 个性化内容过滤，如推荐系统，已成为缓解信息过载的关键。然而，这些系统仅限于现有内容的过滤，难以满足用户多样化的需求。为此，个性化内容生成应运而生，成为解决这一问题的有力方向。尽管大多数研究聚焦于个性化文本生成，但个性化图像生成仍处于起步阶段，面临从复杂多模态数据中准确捕捉用户视觉偏好的挑战。更棘手的是，缺乏足够的监督数据。为应对这些挑战，我们推出了Pigeon框架，利用先进的多模态模型，通过三个专用模块精准捕捉用户视觉偏好。同时，我们设计了两阶段偏好对齐方案，以缓解数据稀缺问题。实验证明，Pigeon在个性化贴纸和电影海报生成任务中表现卓越，超越了众多基线模型。

> Personalized content filtering, such as recommender systems, has become a critical infrastructure to alleviate information overload. However, these systems merely filter existing content and are constrained by its limited diversity, making it difficult to meet users' varied content needs. To address this limitation, personalized content generation has emerged as a promising direction with broad applications. Nevertheless, most existing research focuses on personalized text generation, with relatively little attention given to personalized image generation. The limited work in personalized image generation faces challenges in accurately capturing users' visual preferences and needs from noisy user-interacted images and complex multimodal instructions. Worse still, there is a lack of supervised data for training personalized image generation models.
  To overcome the challenges, we propose a Personalized Image Generation Framework named Pigeon, which adopts exceptional large multimodal models with three dedicated modules to capture users' visual preferences and needs from noisy user history and multimodal instructions. To alleviate the data scarcity, we introduce a two-stage preference alignment scheme, comprising masked preference reconstruction and pairwise preference alignment, to align Pigeon with the personalized image generation task. We apply Pigeon to personalized sticker and movie poster generation, where extensive quantitative results and human evaluation highlight its superiority over various generative baselines.

[Arxiv](https://arxiv.org/abs/2410.14170)