# ReVisionLLM：用于一小时长视频中时间接地的递归式视觉语言模型

发布时间：2024年11月22日

`LLM应用` `视频处理` `模型训练`

> ReVisionLLM: Recursive Vision-Language Model for Temporal Grounding in Hour-Long Videos

# 摘要

> 大型语言模型（LLMs）在从冗长文本中获取信息方面表现出色，然而其视觉语言对应模型（VLMs）在处理数小时长的视频时却困难重重，尤其在时间定位方面。具体来说，这些VLMs受限于帧的限制，常常丢失在扩展视频内容中准确定位事件所需的关键时间细节。我们提出了ReVisionLLM，这是一款专为定位数小时长视频中的事件而设计的递归视觉语言模型。受人类搜索策略的启发，我们的模型起初瞄准广泛的感兴趣片段，逐步修正焦点以精准确定时间边界。我们的模型能够无缝处理时长差异极大的视频，从几分钟到数小时皆可。我们还引入了一种分层训练策略，先从短剪辑入手捕捉不同事件，再逐渐拓展到更长的视频。据我们所知，ReVisionLLM是首个能在数小时长视频中进行时间定位的VLM，在多个数据集上的表现大幅优于以往的先进方法（在MAD上的R1@0.1提升了+2.6%）。代码可在https://github.com/Tanveer81/ReVisionLLM获取。

> Large language models (LLMs) excel at retrieving information from lengthy text, but their vision-language counterparts (VLMs) face difficulties with hour-long videos, especially for temporal grounding. Specifically, these VLMs are constrained by frame limitations, often losing essential temporal details needed for accurate event localization in extended video content. We propose ReVisionLLM, a recursive vision-language model designed to locate events in hour-long videos. Inspired by human search strategies, our model initially targets broad segments of interest, progressively revising its focus to pinpoint exact temporal boundaries. Our model can seamlessly handle videos of vastly different lengths, from minutes to hours. We also introduce a hierarchical training strategy that starts with short clips to capture distinct events and progressively extends to longer videos. To our knowledge, ReVisionLLM is the first VLM capable of temporal grounding in hour-long videos, outperforming previous state-of-the-art methods across multiple datasets by a significant margin (+2.6% R1@0.1 on MAD). The code is available at https://github.com/Tanveer81/ReVisionLLM.

[Arxiv](https://arxiv.org/abs/2411.14901)