# MotionLLM：融合大型语言模型的多模态运动与语言学习

发布时间：2024年05月27日

`LLM应用

这篇论文介绍了一个名为MotionLLM的多模态大型语言模型应用，该应用通过微调预训练的LLMs来实现单人和多人运动生成，并进行运动描述。它通过将运动编码量化为LLM能理解的离散令牌，构建了一个融合运动与文本的统一词汇表。这种方法展示了LLM在多模态应用中的泛化与鲁棒性，并且具有较高的效率和可扩展性。因此，这篇论文属于LLM应用分类。`

> MotionLLM: Multimodal Motion-Language Learning with Large Language Models

# 摘要

> 多模态大型语言模型（MM-LLMs）的最新进展显示了其在不同模态应用中的泛化与鲁棒性的潜力。以往的研究虽已通过多种技术（如语言建模）实现了3D人体运动生成，但这些方法多采用特制架构，且仅限于单人运动。受MM-LLMs启发，我们开发了MotionLLM，一个简洁而通用的框架，通过微调预训练的LLMs，能实现单人及多人运动生成，并进行运动描述。我们巧妙地将运动编码量化为LLM能理解的离散令牌，构建了一个融合运动与文本的统一词汇表。仅动用LLMs的1-3%参数，我们的单人运动生成便能媲美扩散模型及其他基于变压器、从头训练的模型。此外，我们的方法灵活可扩展，轻松通过单人运动的自动回归生成，扩展至多人运动生成。项目详情请访问：https://knoxzhao.github.io/MotionLLM。

> Recent advancements in Multimodal Large Language Models (MM-LLMs) have demonstrated promising potential in terms of generalization and robustness when applied to different modalities. While previous works have already achieved 3D human motion generation using various approaches including language modeling, they mostly % are mostly carefully designed use specialized architecture and are restricted to single-human motion generation. Inspired by the success of MM-LLMs, we propose MotionLLM, a simple and general framework that can achieve single-human, multi-human motion generation, and motion captioning by fine-tuning pre-trained LLMs. Specifically, we encode and quantize motions into discrete LLM-understandable tokens, which results in a unified vocabulary consisting of both motion and text tokens. With only 1--3% parameters of the LLMs trained by using adapters, our single-human motion generation achieves comparable results to those diffusion models and other trained-from-scratch transformer-based models. Additionally, we show that our approach is scalable and flexible, allowing easy extension to multi-human motion generation through autoregressive generation of single-human motions. Project page: https://knoxzhao.github.io/MotionLLM

![MotionLLM：融合大型语言模型的多模态运动与语言学习](../../../paper_images/2405.17013/x1.png)

![MotionLLM：融合大型语言模型的多模态运动与语言学习](../../../paper_images/2405.17013/x2.png)

![MotionLLM：融合大型语言模型的多模态运动与语言学习](../../../paper_images/2405.17013/x3.png)

![MotionLLM：融合大型语言模型的多模态运动与语言学习](../../../paper_images/2405.17013/x4.png)

![MotionLLM：融合大型语言模型的多模态运动与语言学习](../../../paper_images/2405.17013/x5.png)

![MotionLLM：融合大型语言模型的多模态运动与语言学习](../../../paper_images/2405.17013/survey1_.png)

![MotionLLM：融合大型语言模型的多模态运动与语言学习](../../../paper_images/2405.17013/survey2_.png)

[Arxiv](https://arxiv.org/abs/2405.17013)