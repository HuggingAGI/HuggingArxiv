# AdaCM$^2$: 有关借助自适应跨模态内存缩减来理解极长期视频

发布时间：2024年11月19日

`LLM应用` `人工智能`

> AdaCM$^2$: On Understanding Extremely Long-Term Video with Adaptive Cross-Modality Memory Reduction

# 摘要

> 大型语言模型（LLMs）的发展通过将 LLMs 与视觉模型相结合，促进了视频理解任务的提升。然而，现有的大多数基于 LLM 的模型（比如 VideoLLaMA、VideoChat）都只能处理短时长视频。近期为理解长时视频所做的尝试，是将视觉特征提取并压缩至固定内存大小。但这些方法仅借助视觉模态来合并视频令牌，忽略了视觉与文本查询的相关性，致使难以有效应对复杂的问答任务。为应对长视频和复杂提示的挑战，我们提出了 AdaCM$^2$，这是首次引入自适应跨模态内存缩减方法，以自回归的方式实现视频流中的视频-文本对齐。我们在诸如视频字幕、视频问答和视频分类等各种视频理解任务上开展的大量实验表明，AdaCM$^2$ 在多个数据集上达到了最先进的性能，同时大幅降低了内存使用量。特别值得一提的是，它在 LVU 数据集中的多个任务上实现了 4.5%的提升，GPU 内存消耗最多降低了 65%。

> The advancements in large language models (LLMs) have propelled the improvement of video understanding tasks by incorporating LLMs with visual models. However, most existing LLM-based models (e.g., VideoLLaMA, VideoChat) are constrained to processing short-duration videos. Recent attempts to understand long-term videos by extracting and compressing visual features into a fixed memory size. Nevertheless, those methods leverage only visual modality to merge video tokens and overlook the correlation between visual and textual queries, leading to difficulties in effectively handling complex question-answering tasks. To address the challenges of long videos and complex prompts, we propose AdaCM$^2$, which, for the first time, introduces an adaptive cross-modality memory reduction approach to video-text alignment in an auto-regressive manner on video streams. Our extensive experiments on various video understanding tasks, such as video captioning, video question answering, and video classification, demonstrate that AdaCM$^2$ achieves state-of-the-art performance across multiple datasets while significantly reducing memory usage. Notably, it achieves a 4.5% improvement across multiple tasks in the LVU dataset with a GPU memory consumption reduction of up to 65%.

[Arxiv](https://arxiv.org/abs/2411.12593)