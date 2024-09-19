# LLM-wrapper：视觉-语言基础模型的黑盒语义感知适应方案

发布时间：2024年09月18日

`LLM应用` `计算机视觉`

> LLM-wrapper: Black-Box Semantic-Aware Adaptation of Vision-Language Foundation Models

# 摘要

> 视觉语言模型 (VLM) 虽在多任务中表现出色，但其零-shot 能力不及专用或微调模型。微调 VLM 需“白盒”访问模型架构与权重，并需专业设计微调目标与优化超参数，这限制了其应用。为此，我们提出 LLM-wrapper，利用大型语言模型 (LLM) 以“黑盒”方式增强 VLM，对其输出进行推理。在 Referring Expression Comprehension (REC) 这一需空间与语义推理的开放词汇任务中，LLM-wrapper 显著提升现成模型性能，媲美经典微调效果。

> Vision Language Models (VLMs) have shown impressive performances on numerous tasks but their zero-shot capabilities can be limited compared to dedicated or fine-tuned models. Yet, fine-tuning VLMs comes with limitations as it requires `white-box' access to the model's architecture and weights as well as expertise to design the fine-tuning objectives and optimize the hyper-parameters, which are specific to each VLM and downstream task. In this work, we propose LLM-wrapper, a novel approach to adapt VLMs in a `black-box' manner by leveraging large language models (LLMs) so as to reason on their outputs. We demonstrate the effectiveness of LLM-wrapper on Referring Expression Comprehension (REC), a challenging open-vocabulary task that requires spatial and semantic reasoning. Our approach significantly boosts the performance of off-the-shelf models, resulting in competitive results when compared with classic fine-tuning.

[Arxiv](https://arxiv.org/abs/2409.11919)