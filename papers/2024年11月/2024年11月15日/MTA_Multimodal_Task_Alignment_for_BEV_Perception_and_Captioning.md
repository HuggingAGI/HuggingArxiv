# MTA：实现 BEV 感知与字幕的多模态任务对齐

发布时间：2024年11月15日

`LLM应用` `自动驾驶` `多模态`

> MTA: Multimodal Task Alignment for BEV Perception and Captioning

# 摘要

> 以鸟瞰图（BEV）为基础的 3D 感知在自动驾驶应用中至关重要。大型语言模型的兴起让基于 BEV 的字幕备受关注，以理解周边环境中物体的行为。然而，现有的方法把感知和字幕当作独立任务，只注重其中一项任务的性能，忽略了多模态对齐的潜在益处。为了填补模态间的这一空缺，我们推出了 MTA，这是一个新颖的多模态任务对齐框架，能同时促进 BEV 感知和字幕生成。MTA 包含两个关键部分：（1）BEV - 语言对齐（BLA），这是一种能将 BEV 场景表示与真实语言表示对齐的上下文学习机制；（2）检测 - 字幕对齐（DCA），这是一种能将检测和字幕输出对齐的跨模态提示机制。MTA 在训练时融入最先进的基线，运行时不增加额外的计算复杂度。在 nuScenes 和 TOD3Cap 数据集上的大量实验表明，MTA 明显优于最先进的基线，感知方面提升了 4.9％，字幕方面提升了 9.2％。这些结果突显了统一对齐在协调基于 BEV 的感知和字幕方面的有效性。

> Bird's eye view (BEV)-based 3D perception plays a crucial role in autonomous driving applications. The rise of large language models has spurred interest in BEV-based captioning to understand object behavior in the surrounding environment. However, existing approaches treat perception and captioning as separate tasks, focusing on the performance of only one of the tasks and overlooking the potential benefits of multimodal alignment. To bridge this gap between modalities, we introduce MTA, a novel multimodal task alignment framework that boosts both BEV perception and captioning. MTA consists of two key components: (1) BEV-Language Alignment (BLA), a contextual learning mechanism that aligns the BEV scene representations with ground-truth language representations, and (2) Detection-Captioning Alignment (DCA), a cross-modal prompting mechanism that aligns detection and captioning outputs. MTA integrates into state-of-the-art baselines during training, adding no extra computational complexity at runtime. Extensive experiments on the nuScenes and TOD3Cap datasets show that MTA significantly outperforms state-of-the-art baselines, achieving a 4.9% improvement in perception and a 9.2% improvement in captioning. These results underscore the effectiveness of unified alignment in reconciling BEV-based perception and captioning.

[Arxiv](https://arxiv.org/abs/2411.10639)