# VTG-LLM：融合时间戳知识于视频LLMs，提升视频时间定位能力

发布时间：2024年05月22日

`LLM应用

这篇论文主要探讨了视频时间定位（VTG）技术，并提出了针对视频大型语言模型（video LLMs）的改进方法。论文中提到的构建高质量数据集（VTG-IT-120K）和设计新型模型（VTG-LLM），旨在提高模型对视频时间信息的理解和处理能力。这些内容直接关联到大型语言模型在特定应用场景（即视频时间定位）中的实际应用和性能提升，因此属于LLM应用分类。` `视频处理` `人工智能`

> VTG-LLM: Integrating Timestamp Knowledge into Video LLMs for Enhanced Video Temporal Grounding

# 摘要

> 视频时间定位（VTG）技术，旨在通过语言查询精准捕捉视频中的事件时刻，对视频浏览和编辑等应用至关重要。尽管视频大型语言模型（video LLMs）在视频内容理解上取得了长足进步，但在精确捕捉视频时间戳方面仍显不足，影响了其在VTG任务上的表现。为此，我们强调两个关键改进方向：一是构建高质量的指令调整数据集，覆盖主流VTG任务；二是将时间戳知识直接融入模型，以提升对时间信息的理解效率。为此，我们推出了VTG-IT-120K，一个全面且高质量的数据集，涵盖了时刻检索、视频字幕、摘要及亮点检测等任务。同时，我们设计了VTG-LLM模型，它巧妙地将时间戳知识融入视觉令牌，并引入了处理时间戳的绝对时间令牌，避免了概念混淆，并采用了高效的令牌压缩技术，以支持更多视频帧的采样。实验结果显示，VTG-LLM在多个VTG任务上均优于其他方法。相关代码和数据集已公开于\url{https://github.com/gyxxyg/VTG-LLM}。

> Video Temporal Grounding (VTG) focuses on accurately identifying event timestamps within a particular video based on a linguistic query, playing a vital role in downstream tasks such as video browsing and editing. While Video Large Language Models (video LLMs) have made significant progress in understanding video content, they often face challenges in accurately pinpointing timestamps within videos, which limits their performance on VTG tasks. Therefore, to improve video LLMs' ability to effectively locate timestamps, we argue that two critical aspects need to be enhanced. First, it is essential to have high-quality instructional tuning datasets that encompass mainstream VTG tasks. Second, directly incorporating timestamp knowledge into video LLMs is crucial, as it enables models to efficiently comprehend timestamp information. To address these needs, we first introduce VTG-IT-120K, a high-quality and comprehensive instruction tuning dataset that covers VTG tasks such as moment retrieval, dense video captioning, video summarization, and video highlight detection. Furthermore, we propose a specially designed video LLM model for VTG tasks, VTG-LLM, which (1) effectively integrates timestamp knowledge into visual tokens; (2) incorporates absolute-time tokens that specifically handle timestamp knowledge, thereby avoiding concept shifts; and (3) introduces a lightweight, high-performance slot-based token compression method to facilitate the sampling of more video frames. Comprehensive experiments showcase the superior performance of VTG-LLM in comparison to other video LLM methods across various VTG tasks. Our code and datasets are available at \url{https://github.com/gyxxyg/VTG-LLM}.

[Arxiv](https://arxiv.org/abs/2405.13382)