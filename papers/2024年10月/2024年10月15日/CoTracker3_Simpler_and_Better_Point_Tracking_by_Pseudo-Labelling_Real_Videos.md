# CoTracker3：借助伪标签技术，在真实视频中实现更简便且高效的点跟踪。

发布时间：2024年10月15日

`其他` `视频追踪` `计算机视觉`

> CoTracker3: Simpler and Better Point Tracking by Pseudo-Labelling Real Videos

# 摘要

> 摘要：由于标注真实视频的难度，大多数顶尖的点追踪器依赖于合成数据训练。然而，合成与真实视频间的统计差异可能导致性能不佳。为此，我们推出了CoTracker3，包含新型追踪模型与半监督训练方法，利用现成教师生成伪标签，使无标注真实视频得以训练。新模型简化了架构，训练更简便，数据需求减少1000倍，效果更佳。我们还探讨了扩展行为，分析了更多无监督真实数据对追踪性能的影响。CoTracker3提供在线与离线版本，可靠追踪可见及被遮挡的点。

> 
Abstract:Most state-of-the-art point trackers are trained on synthetic data due to the difficulty of annotating real videos for this task. However, this can result in suboptimal performance due to the statistical gap between synthetic and real videos. In order to understand these issues better, we introduce CoTracker3, comprising a new tracking model and a new semi-supervised training recipe. This allows real videos without annotations to be used during training by generating pseudo-labels using off-the-shelf teachers. The new model eliminates or simplifies components from previous trackers, resulting in a simpler and often smaller architecture. This training scheme is much simpler than prior work and achieves better results using 1,000 times less data. We further study the scaling behaviour to understand the impact of using more real unsupervised data in point tracking. The model is available in online and offline variants and reliably tracks visible and occluded points.
    

[Arxiv](https://arxiv.org/pdf/2410.11831)