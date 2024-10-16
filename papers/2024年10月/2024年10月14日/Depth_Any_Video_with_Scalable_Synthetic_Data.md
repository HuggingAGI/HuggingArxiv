# 用可扩展的合成数据实现任意视频深度

发布时间：2024年10月14日

`其他` `视频处理` `计算机视觉`

> Depth Any Video with Scalable Synthetic Data

# 摘要

> 视频深度估计因缺乏一致且可扩展的地面实况数据而长期受阻，导致结果不稳定。本文提出 Depth Any Video 模型，通过两项创新突破这一瓶颈。首先，我们构建了可扩展的合成数据管道，从多样环境中实时捕捉深度数据，生成 40,000 个 5 秒视频片段，并精确标注深度。其次，我们利用生成视频扩散模型的先验知识，结合旋转位置编码和流匹配等技术，提升处理现实视频的灵活性和效率。与以往固定长度视频模型不同，我们采用混合时长训练策略，适应不同长度和帧率的视频，甚至在单帧上表现出色。推理时，我们提出深度插值方法，使模型能在长达 150 帧的序列中推断高分辨率深度。该模型在空间准确性和时间一致性上超越了所有先前模型。

> 
Abstract:Video depth estimation has long been hindered by the scarcity of consistent and scalable ground truth data, leading to inconsistent and unreliable results. In this paper, we introduce Depth Any Video, a model that tackles the challenge through two key innovations. First, we develop a scalable synthetic data pipeline, capturing real-time video depth data from diverse synthetic environments, yielding 40,000 video clips of 5-second duration, each with precise depth annotations. Second, we leverage the powerful priors of generative video diffusion models to handle real-world videos effectively, integrating advanced techniques such as rotary position encoding and flow matching to further enhance flexibility and efficiency. Unlike previous models, which are limited to fixed-length video sequences, our approach introduces a novel mixed-duration training strategy that handles videos of varying lengths and performs robustly across different frame rates-even on single frames. At inference, we propose a depth interpolation method that enables our model to infer high-resolution video depth across sequences of up to 150 frames. Our model outperforms all previous generative depth models in terms of spatial accuracy and temporal consistency.
    

[Arxiv](https://arxiv.org/pdf/2410.10815)