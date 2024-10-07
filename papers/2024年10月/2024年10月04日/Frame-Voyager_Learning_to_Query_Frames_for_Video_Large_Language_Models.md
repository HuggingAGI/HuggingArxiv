# Frame-Voyager：探索如何为视频大型语言模型高效查询帧

发布时间：2024年10月04日

`LLM应用` `视频处理` `人工智能`

> Frame-Voyager: Learning to Query Frames for Video Large Language Models

# 摘要

> 视频大型语言模型 (Video-LLMs) 在视频理解方面取得了显著进展，但受限于输入令牌的最大长度，无法处理整个视频。现有的帧选择方法，如均匀采样和文本检索，未能充分考虑视频信息密度的变化和任务指令的复杂性，导致性能不佳。为此，我们提出了 Frame-Voyager，它能够根据任务中的文本查询，智能选择信息丰富的帧组合。为了训练 Frame-Voyager，我们设计了一套新的数据收集和标注流程，利用预训练的 Video-LLM 对帧组合进行排序。具体来说，我们遍历视频中的 T 帧组合，通过 Video-LLM 计算预测损失并排序，以此作为监督信号，训练 Frame-Voyager 选择低损失的帧组合。实验结果显示，Frame-Voyager 在多个视频问答基准测试中表现出色，展示了其作为 Video-LLMs 即插即用解决方案的巨大潜力。

> Video Large Language Models (Video-LLMs) have made remarkable progress in video understanding tasks. However, they are constrained by the maximum length of input tokens, making it impractical to input entire videos. Existing frame selection approaches, such as uniform frame sampling and text-frame retrieval, fail to account for the information density variations in the videos or the complex instructions in the tasks, leading to sub-optimal performance. In this paper, we propose Frame-Voyager that learns to query informative frame combinations, based on the given textual queries in the task. To train Frame-Voyager, we introduce a new data collection and labeling pipeline, by ranking frame combinations using a pre-trained Video-LLM. Given a video of M frames, we traverse its T-frame combinations, feed them into a Video-LLM, and rank them based on Video-LLM's prediction losses. Using this ranking as supervision, we train Frame-Voyager to query the frame combinations with lower losses. In experiments, we evaluate Frame-Voyager on four Video Question Answering benchmarks by plugging it into two different Video-LLMs. The experimental results demonstrate that Frame-Voyager achieves impressive results in all settings, highlighting its potential as a plug-and-play solution for Video-LLMs.

[Arxiv](https://arxiv.org/abs/2410.03226)