# PA-LLaVA：专为人类病理图像理解设计的大型语言与视觉助手

发布时间：2024年08月18日

`LLM应用` `计算病理学`

> PA-LLaVA: A Large Language-Vision Assistant for Human Pathology Image Understanding

# 摘要

> 在病理图像理解领域，我们创新性地开发了领域特定的大型语言-视觉助手PA-LLaVA，通过构建高质量的病理图像-文本数据集，并采用先进的PLIP模型和尺度不变连接器，有效提升了医学图像理解的性能。实验证明，PA-LLaVA在多模态模型中表现卓越，为计算病理学研究开辟了新路径。所有相关代码已公开，供学术界共享与探索。

> The previous advancements in pathology image understanding primarily involved developing models tailored to specific tasks. Recent studies has demonstrated that the large vision-language model can enhance the performance of various downstream tasks in medical image understanding. In this study, we developed a domain-specific large language-vision assistant (PA-LLaVA) for pathology image understanding. Specifically, (1) we first construct a human pathology image-text dataset by cleaning the public medical image-text data for domain-specific alignment; (2) Using the proposed image-text data, we first train a pathology language-image pretraining (PLIP) model as the specialized visual encoder for pathology image, and then we developed scale-invariant connector to avoid the information loss caused by image scaling; (3) We adopt two-stage learning to train PA-LLaVA, first stage for domain alignment, and second stage for end to end visual question \& answering (VQA) task. In experiments, we evaluate our PA-LLaVA on both supervised and zero-shot VQA datasets, our model achieved the best overall performance among multimodal models of similar scale. The ablation experiments also confirmed the effectiveness of our design. We posit that our PA-LLaVA model and the datasets presented in this work can promote research in field of computational pathology. All codes are available at: https://github.com/ddw2AIGROUP2CQUPT/PA-LLaVA}{https://github.com/ddw2AIGROUP2CQUPT/PA-LLaVA

[Arxiv](https://arxiv.org/abs/2408.09530)