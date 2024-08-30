# VideoLLM-MoD：利用深度混合视觉计算技术，实现视频语言流的高效处理

发布时间：2024年08月29日

`LLM应用` `视频处理` `人工智能`

> VideoLLM-MoD: Efficient Video-Language Streaming with Mixture-of-Depths Vision Computation

# 摘要

> 在大型视觉-语言模型中，增加视觉标记虽能提升理解力，却也大幅增加了内存与计算负担，尤其是在处理长视频流时。尽管已有方法如Q-Former和Perceiver Resampler尝试减轻这一负担，但它们未能充分利用LLMs的键值缓存上下文，可能导致视觉线索的遗漏。本文提出了一种创新策略——VideoLLM-MoD，通过“跳过层”方式利用冗余视觉标记，而非简单减少标记数量，有效降低了计算需求。具体而言，我们训练模型跳过大部分视觉标记的计算，直接传递至下一层，从而显著提升效率，节省约42%的训练时间和30%的内存。这种方法不仅减少了计算量，还保持了视觉标记的数量，甚至在性能上超越了原始模型。实验结果显示，VideoLLM-MoD在多个数据集的叙述、预测和总结任务中均达到了业界领先水平。

> A well-known dilemma in large vision-language models (e.g., GPT-4, LLaVA) is that while increasing the number of vision tokens generally enhances visual understanding, it also significantly raises memory and computational costs, especially in long-term, dense video frame streaming scenarios. Although learnable approaches like Q-Former and Perceiver Resampler have been developed to reduce the vision token burden, they overlook the context causally modeled by LLMs (i.e., key-value cache), potentially leading to missed visual cues when addressing user queries. In this paper, we introduce a novel approach to reduce vision compute by leveraging redundant vision tokens "skipping layers" rather than decreasing the number of vision tokens. Our method, VideoLLM-MoD, is inspired by mixture-of-depths LLMs and addresses the challenge of numerous vision tokens in long-term or streaming video. Specifically, for each transformer layer, we learn to skip the computation for a high proportion (e.g., 80\%) of vision tokens, passing them directly to the next layer. This approach significantly enhances model efficiency, achieving approximately \textasciitilde42\% time and \textasciitilde30\% memory savings for the entire training. Moreover, our method reduces the computation in the context and avoid decreasing the vision tokens, thus preserving or even improving performance compared to the vanilla model. We conduct extensive experiments to demonstrate the effectiveness of VideoLLM-MoD, showing its state-of-the-art results on multiple benchmarks, including narration, forecasting, and summarization tasks in COIN, Ego4D, and Ego-Exo4D datasets.

[Arxiv](https://arxiv.org/abs/2408.16730)