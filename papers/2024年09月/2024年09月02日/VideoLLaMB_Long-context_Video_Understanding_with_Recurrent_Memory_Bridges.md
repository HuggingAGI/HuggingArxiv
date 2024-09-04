# VideoLLaMB：借助循环记忆桥实现长上下文视频理解

发布时间：2024年09月02日

`LLM应用` `视频处理` `学术研究`

> VideoLLaMB: Long-context Video Understanding with Recurrent Memory Bridges

# 摘要

> 近年来，大型视频-语言模型在实时规划和精细交互方面展现出显著潜力。然而，高计算需求和标注数据集的稀缺性限制了其在学术界的实际应用。为此，我们推出了VideoLLaMB框架，该框架通过桥接层中的时间记忆令牌，有效编码视频序列和历史视觉数据，保持语义连续性，提升多任务性能。VideoLLaMB包含循环记忆令牌和SceneTilling算法，将视频分割为语义单元，确保语义完整。实证显示，VideoLLaMB在VideoQA基准上领先5.5分，在以自我为中心的规划任务上领先2.06分。在MVBench测试中，VideoLLaMB-7B显著优于同类模型。即使在视频长度增加8倍的情况下，VideoLLaMB仍保持稳定性能。此外，在NIAVH基准上的帧检索结果进一步证实了其在长视频中精准定位帧的能力。SceneTilling算法还支持无需额外训练的流式视频字幕生成。在效率上，VideoLLaMB在单个Nvidia A100 GPU上支持高达320帧的处理，线性扩展GPU内存，确保高性能与成本效益，为长格式视频-语言模型在学术与实际应用中树立了新标杆。

> Recent advancements in large-scale video-language models have shown significant potential for real-time planning and detailed interactions. However, their high computational demands and the scarcity of annotated datasets limit their practicality for academic researchers. In this work, we introduce VideoLLaMB, a novel framework that utilizes temporal memory tokens within bridge layers to allow for the encoding of entire video sequences alongside historical visual data, effectively preserving semantic continuity and enhancing model performance across various tasks. This approach includes recurrent memory tokens and a SceneTilling algorithm, which segments videos into independent semantic units to preserve semantic integrity. Empirically, VideoLLaMB significantly outstrips existing video-language models, demonstrating a 5.5 points improvement over its competitors across three VideoQA benchmarks, and 2.06 points on egocentric planning. Comprehensive results on the MVBench show that VideoLLaMB-7B achieves markedly better results than previous 7B models of same LLM. Remarkably, it maintains robust performance as PLLaVA even as video length increases up to 8 times. Besides, the frame retrieval results on our specialized Needle in a Video Haystack (NIAVH) benchmark, further validate VideoLLaMB's prowess in accurately identifying specific frames within lengthy videos. Our SceneTilling algorithm also enables the generation of streaming video captions directly, without necessitating additional training. In terms of efficiency, VideoLLaMB, trained on 16 frames, supports up to 320 frames on a single Nvidia A100 GPU with linear GPU memory scaling, ensuring both high performance and cost-effectiveness, thereby setting a new foundation for long-form video-language models in both academic and practical applications.

[Arxiv](https://arxiv.org/abs/2409.01071)