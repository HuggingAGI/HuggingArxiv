# TimeMarker：一款具备出色时间定位能力的通用型视频-LLM，可用于长短视频的理解

发布时间：2024年11月27日

`LLM应用` `语言模型`

> TimeMarker: A Versatile Video-LLM for Long and Short Video Understanding with Superior Temporal Localization Ability

# 摘要

> 大型语言模型（LLMs）的迅猛发展有力地促进了多模态大型语言模型（LMMs）的发展，尤其在视觉语言任务领域。然而，现有的视频语言模型常常忽视精确的时间定位，在处理不同长度的视频时也颇为棘手。我们推出了 TimeMarker，这是一款专为基于视频内容的高质量对话而设计的通用视频语言模型，注重时间定位。TimeMarker 融入了时间分隔符标记以增强时间感知，能精准标记视频中的特定时刻。它运用 AnyLength 机制进行动态帧采样和自适应标记合并，可有效应对短和长的视频。另外，TimeMarker 借助各类数据集，包括进一步转换的与时间相关的视频问答数据集，来强化其时间理解能力。图像和交错数据也被加以利用，以进一步提升模型的语义感知能力。评估显示，TimeMarker 在多个基准测试中均达到了顶尖水平，在短和长视频类别中均表现卓越。我们的项目页面位于 url{https://github.com/TimeMarker-LLM/TimeMarker/}。

> Rapid development of large language models (LLMs) has significantly advanced multimodal large language models (LMMs), particularly in vision-language tasks. However, existing video-language models often overlook precise temporal localization and struggle with videos of varying lengths. We introduce TimeMarker, a versatile Video-LLM designed for high-quality dialogue based on video content, emphasizing temporal localization. TimeMarker integrates Temporal Separator Tokens to enhance temporal awareness, accurately marking specific moments within videos. It employs the AnyLength mechanism for dynamic frame sampling and adaptive token merging, enabling effective handling of both short and long videos. Additionally, TimeMarker utilizes diverse datasets, including further transformed temporal-related video QA datasets, to bolster its temporal understanding capabilities. Image and interleaved data are also employed to further enhance the model's semantic perception ability. Evaluations demonstrate that TimeMarker achieves state-of-the-art performance across multiple benchmarks, excelling in both short and long video categories. Our project page is at url{https://github.com/TimeMarker-LLM/TimeMarker/}.

[Arxiv](https://arxiv.org/abs/2411.18211)