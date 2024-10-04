# Loong：借助自回归语言模型，轻松生成分钟级长视频

发布时间：2024年10月03日

`LLM应用` `视频生成` `人工智能`

> Loong: Generating Minute-level Long Videos with Autoregressive Language Models

# 摘要

> 生成内容丰富的长视频（分钟级）虽具挑战，但意义重大。自回归大型语言模型（LLMs）在自然语言处理中生成连贯长序列方面表现卓越，但在视频生成领域，其应用仍局限于几秒短视频。我们深入剖析了自回归LLM视频生成器难以生成长视频的难题，并提出Loong，一种能生成分钟级长视频的新型自回归LLM视频生成器。我们统一建模文本与视频标记，并采用渐进式短至长训练及损失重新加权策略，以解决长视频训练中的损失不平衡问题。此外，我们还探索了视频标记重新编码与采样策略，以减少推理误差累积。Loong在10秒视频上训练后，可根据文本提示生成分钟级长视频。更多精彩样本，请访问：https://epiphqny.github.io/Loong-video。

> It is desirable but challenging to generate content-rich long videos in the scale of minutes. Autoregressive large language models (LLMs) have achieved great success in generating coherent and long sequences of tokens in the domain of natural language processing, while the exploration of autoregressive LLMs for video generation is limited to generating short videos of several seconds. In this work, we conduct a deep analysis of the challenges that prevent autoregressive LLM-based video generators from generating long videos. Based on the observations and analysis, we propose Loong, a new autoregressive LLM-based video generator that can generate minute-long videos. Specifically, we model the text tokens and video tokens as a unified sequence for autoregressive LLMs and train the model from scratch. We propose progressive short-to-long training with a loss re-weighting scheme to mitigate the loss imbalance problem for long video training. We further investigate inference strategies, including video token re-encoding and sampling strategies, to diminish error accumulation during inference. Our proposed Loong can be trained on 10-second videos and be extended to generate minute-level long videos conditioned on text prompts, as demonstrated by the results. More samples are available at: https://epiphqny.github.io/Loong-video.

[Arxiv](https://arxiv.org/abs/2410.02757)