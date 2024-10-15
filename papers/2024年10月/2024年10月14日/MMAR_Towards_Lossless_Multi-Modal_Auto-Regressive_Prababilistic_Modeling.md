# MMAR：探索无损多模态自回归概率建模的新领域

发布时间：2024年10月14日

`LLM应用` `计算机视觉` `人工智能`

> MMAR: Towards Lossless Multi-Modal Auto-Regressive Prababilistic Modeling

# 摘要

> 多模态大型语言模型的进步催生了能同时理解与生成图像的联合概率模型。然而，现有方法在图像理解过程中常因离散化或去噪步骤而丢失信息。为此，我们推出了多模态自回归（MMAR）框架，采用连续值图像标记，避免信息流失。与传统扩散方法不同，MMAR 通过轻量级扩散头解耦扩散与自回归模型，确保图像生成向理解过渡时，骨干模型的隐藏表示不受限于去噪步骤。我们还提出了理论验证的数值稳定技术及平衡生成与理解任务的训练策略。在 18 个图像理解基准测试中，MMAR 表现卓越，媲美预训练 CLIP 视觉编码器，同时生成高质量图像。此外，我们的方法在更大数据和模型规模下展现出良好的扩展性。

> Recent advancements in multi-modal large language models have propelled the development of joint probabilistic models capable of both image understanding and generation. However, we have identifed that recent methods inevitably suffer from loss of image information during understanding task, due to either image discretization or diffusion denoising steps. To address this issue, we propose a novel Multi-Modal Auto-Regressive (MMAR) probabilistic modeling framework. Unlike discretization line of method, MMAR takes in continuous-valued image tokens to avoid information loss. Differing from diffusion-based approaches, we disentangle the diffusion process from auto-regressive backbone model by employing a light-weight diffusion head on top each auto-regressed image patch embedding. In this way, when the model transits from image generation to understanding through text generation, the backbone model's hidden representation of the image is not limited to the last denoising step. To successfully train our method, we also propose a theoretically proven technique that addresses the numerical stability issue and a training strategy that balances the generation and understanding task goals. Through extensive evaluations on 18 image understanding benchmarks, MMAR demonstrates much more superior performance than other joint multi-modal models, matching the method that employs pretrained CLIP vision encoder, meanwhile being able to generate high quality images at the same time. We also showed that our method is scalable with larger data and model size.

[Arxiv](https://arxiv.org/abs/2410.10798)