# TOMATO：对多模态基础模型的视觉时间推理能力进行评估

发布时间：2024年10月30日

`其他` `人工智能`

> TOMATO: Assessing Visual Temporal Reasoning Capabilities in Multimodal Foundation Models

# 摘要

> 现有的基准常常突显最先进的多模态基础模型（MFMs）在借助时间上下文进行视频理解时所展现的出色性能。然而，这些模型在视觉时间推理方面的真实表现究竟怎样？我们针对现有基准的研究表明，MFMs 的这种能力或许被高估了，因为不少问题仅通过单个、少量或者无序的帧就能解决。为了系统地审视当下的视觉时间推理任务，我们提出了三条原则以及相应的指标：（1）多帧增益；（2）帧顺序敏感度；（3）帧信息差异。依循这些原则，我们引入了 TOMATO，即时间推理多模态评估，这是一个精心打造的新基准，旨在严格测评 MFMs 在视频理解中的时间推理能力。TOMATO 涵盖了 1484 个精心策划且有人工注释的问题，涉及六个任务（即动作计数、方向、旋转、形状与趋势、速度和频率以及视觉线索），应用于 1417 个视频，其中包括 805 个自录制和生成的视频，涵盖了以人为核心、真实世界以及模拟场景。我们的综合评估显示，表现最佳的模型与人类的性能差距达 57.3%。此外，我们的深入分析还揭示了当前 MFMs 除这一差距外更本质的局限性。虽然它们能精准识别孤立帧中的事件，却无法将这些帧解读为连续的序列。我们坚信 TOMATO 会成为评估下一代 MFMs 的关键测试平台，并呼吁社区开发能够通过视频模式理解人类世界动态的 AI 系统。

> Existing benchmarks often highlight the remarkable performance achieved by state-of-the-art Multimodal Foundation Models (MFMs) in leveraging temporal context for video understanding. However, how well do the models truly perform visual temporal reasoning? Our study of existing benchmarks shows that this capability of MFMs is likely overestimated as many questions can be solved by using a single, few, or out-of-order frames. To systematically examine current visual temporal reasoning tasks, we propose three principles with corresponding metrics: (1) Multi-Frame Gain, (2) Frame Order Sensitivity, and (3) Frame Information Disparity. Following these principles, we introduce TOMATO, Temporal Reasoning Multimodal Evaluation, a novel benchmark crafted to rigorously assess MFMs' temporal reasoning capabilities in video understanding. TOMATO comprises 1,484 carefully curated, human-annotated questions spanning six tasks (i.e., action count, direction, rotation, shape & trend, velocity & frequency, and visual cues), applied to 1,417 videos, including 805 self-recorded and -generated videos, that encompass human-centric, real-world, and simulated scenarios. Our comprehensive evaluation reveals a human-model performance gap of 57.3% with the best-performing model. Moreover, our in-depth analysis uncovers more fundamental limitations beyond this gap in current MFMs. While they can accurately recognize events in isolated frames, they fail to interpret these frames as a continuous sequence. We believe TOMATO will serve as a crucial testbed for evaluating the next-generation MFMs and as a call to the community to develop AI systems capable of comprehending human world dynamics through the video modality.

[Arxiv](https://arxiv.org/abs/2410.23266)