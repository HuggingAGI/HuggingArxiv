# 一个针对篮球广播镜头的简单又有效的时间定位流程

发布时间：2024年10月30日

`其他` `视频分析`

> A Simple and Effective Temporal Grounding Pipeline for Basketball Broadcast Footage

# 摘要

> 我们推出了一条用于篮球广播视频与分析对齐的可靠时间定位流程。给定一系列的帧作为输入，我们的方法能迅速且精准地从篮球广播场景中提取出剩余时间和节次值。我们的工作旨在加速大型多模态视频数据集的开发，以用于训练体育动作识别领域中对数据需求极大的视频模型。我们的方法将包含密集事件注释的预标记逐场注释语料库与视频帧对齐，能够实现对标记视频片段的快速检索。和以往方法不同，我们无需通过微调现成的对象检测器来定位游戏时钟，而是直接找到语义文本区域。我们的端到端方式提升了工作的通用性。另外，插值和平行化技术让我们的流程能够在大型计算集群中进行部署。所有代码均已公开。

> We present a reliable temporal grounding pipeline for video-to-analytic alignment of basketball broadcast footage. Given a series of frames as input, our method quickly and accurately extracts time-remaining and quarter values from basketball broadcast scenes. Our work intends to expedite the development of large, multi-modal video datasets to train data-hungry video models in the sports action recognition domain. Our method aligns a pre-labeled corpus of play-by-play annotations containing dense event annotations to video frames, enabling quick retrieval of labeled video segments. Unlike previous methods, we forgo the need to localize game clocks by fine-tuning an out-of-the-box object detector to find semantic text regions directly. Our end-to-end approach improves the generality of our work. Additionally, interpolation and parallelization techniques prepare our pipeline for deployment in a large computing cluster. All code is made publicly available.

[Arxiv](https://arxiv.org/abs/2411.00862)