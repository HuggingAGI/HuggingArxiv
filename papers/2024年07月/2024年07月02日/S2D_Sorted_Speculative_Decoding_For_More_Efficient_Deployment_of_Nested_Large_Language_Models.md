# S2D：通过排序推测解码，提升嵌套大型语言模型的部署效率

发布时间：2024年07月02日

`LLM应用` `人工智能` `云计算`

> S2D: Sorted Speculative Decoding For More Efficient Deployment of Nested Large Language Models

# 摘要

> 自回归大型语言模型的部署成本高昂，且随着模型规模的扩大，相关成本愈发显著。为此，业界提出了多种方法来加速令牌生成并降低成本。其中，推测解码 (SD) 通过并行验证多个令牌并利用辅助的小型草稿模型生成可能的令牌，成为加速 LLM 解码过程的佼佼者。通常，一个草稿模型服务于一个特定的目标模型，但现实中 LLM 种类繁多，我们可能需要同时处理多个目标模型。这种情况下，选择合适的草稿模型变得复杂，而搜索或定制草稿模型可能进一步增加部署成本。本文中，我们首先提出了一种新颖的多目标场景，用于草稿模型的快速推理部署。接着，我们介绍了一种更高效的排序推测解码机制，该机制在多目标环境中表现优于传统基准。我们在包括 Vicuna 7B、13B 和 LLama Chat 70B 在内的多种模型上验证了我们的方法，结果显示，我们的草稿模型在同时处理多个目标模型时，性能超越了基准。

> Deployment of autoregressive large language models (LLMs) is costly, and as these models increase in size, the associated costs will become even more considerable. Consequently, different methods have been proposed to accelerate the token generation process and reduce costs. Speculative decoding (SD) is among the most promising approaches to speed up the LLM decoding process by verifying multiple tokens in parallel and using an auxiliary smaller draft model to generate the possible tokens. In SD, usually, one draft model is used to serve a specific target model; however, in practice, LLMs are diverse, and we might need to deal with many target models or more than one target model simultaneously. In this scenario, it is not clear which draft model should be used for which target model, and searching among different draft models or training customized draft models can further increase deployment costs. In this paper, we first introduce a novel multi-target scenario for the deployment of draft models for faster inference. Then, we present a novel, more efficient sorted speculative decoding mechanism that outperforms regular baselines in multi-target settings. We evaluated our method on Spec-Bench in different settings, including base models such as Vicuna 7B, 13B, and LLama Chat 70B. Our results suggest that our draft models perform better than baselines for multiple target models at the same time.

[Arxiv](https://arxiv.org/abs/2407.01955)