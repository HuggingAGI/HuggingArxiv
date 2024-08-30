# PromptSmooth：利用提示学习确保医疗视觉-语言模型的稳健性

发布时间：2024年08月29日

`LLM应用` `计算机视觉`

> PromptSmooth: Certifying Robustness of Medical Vision-Language Models via Prompt Learning

# 摘要

> 医学视觉-语言模型（Med-VLMs）经过大量医学图像-文本对数据集的训练和特定任务的微调，已成为医学图像分析的主流。但近期研究指出，这些模型易受对抗性攻击，引发安全与鲁棒性担忧。随机平滑技术虽能提升模型对抗扰动的鲁棒性，但需重新训练模型以适应Gaussian噪声，这在实际中常难以实现。为此，我们提出PromptSmooth框架，利用提示学习，高效提升Med-VLMs的鲁棒性。该框架通过学习文本提示，使预训练模型能零-shot或few-shot适应Gaussian噪声，平衡准确性与鲁棒性，并减少计算负担。此外，PromptSmooth仅需单一模型处理多噪声水平，显著降低传统方法的计算成本。综合实验显示，PromptSmooth在多种成像模式的六个数据集上表现出色。相关代码与模型已公开于https://github.com/nhussein/promptsmooth。

> Medical vision-language models (Med-VLMs) trained on large datasets of medical image-text pairs and later fine-tuned for specific tasks have emerged as a mainstream paradigm in medical image analysis. However, recent studies have highlighted the susceptibility of these Med-VLMs to adversarial attacks, raising concerns about their safety and robustness. Randomized smoothing is a well-known technique for turning any classifier into a model that is certifiably robust to adversarial perturbations. However, this approach requires retraining the Med-VLM-based classifier so that it classifies well under Gaussian noise, which is often infeasible in practice. In this paper, we propose a novel framework called PromptSmooth to achieve efficient certified robustness of Med-VLMs by leveraging the concept of prompt learning. Given any pre-trained Med-VLM, PromptSmooth adapts it to handle Gaussian noise by learning textual prompts in a zero-shot or few-shot manner, achieving a delicate balance between accuracy and robustness, while minimizing the computational overhead. Moreover, PromptSmooth requires only a single model to handle multiple noise levels, which substantially reduces the computational cost compared to traditional methods that rely on training a separate model for each noise level. Comprehensive experiments based on three Med-VLMs and across six downstream datasets of various imaging modalities demonstrate the efficacy of PromptSmooth. Our code and models are available at https://github.com/nhussein/promptsmooth.

[Arxiv](https://arxiv.org/abs/2408.16769)