# E.T. Bench：开启事件级视频与语言的开放式理解之旅

发布时间：2024年09月26日

`LLM应用` `视频分析` `人工智能`

> E.T. Bench: Towards Open-Ended Event-Level Video-Language Understanding

# 摘要

> 视频大型语言模型 (Video-LLMs) 的最新进展展示了其在通用视频理解中的巨大潜力。然而，现有基准仅通过视频级别的问答来评估模型，缺乏细粒度的事件级别评估和任务多样性。为此，我们引入了 E.T. Bench，这是一个大规模且高质量的开放式事件级别视频理解基准。E.T. Bench 包含 7.3K 样本，涵盖 12 个任务，涉及 7K 个视频 (总时长 251.4 小时)，分布在 8 个领域，提供全面的评估。我们在基准上评估了 8 个图像-LLMs 和 12 个视频-LLMs，结果显示，最先进的粗略级别理解模型难以解决细粒度任务，如在视频中定位感兴趣的事件。针对这些问题，我们提出了一个强大的基线模型 E.T. Chat，以及一个专门为细粒度事件级别理解定制的指令调优数据集 E.T. Instruct 164K。我们的解决方案在多个场景中展示了优越的性能。

> Recent advances in Video Large Language Models (Video-LLMs) have demonstrated their great potential in general-purpose video understanding. To verify the significance of these models, a number of benchmarks have been proposed to diagnose their capabilities in different scenarios. However, existing benchmarks merely evaluate models through video-level question-answering, lacking fine-grained event-level assessment and task diversity. To fill this gap, we introduce E.T. Bench (Event-Level & Time-Sensitive Video Understanding Benchmark), a large-scale and high-quality benchmark for open-ended event-level video understanding. Categorized within a 3-level task taxonomy, E.T. Bench encompasses 7.3K samples under 12 tasks with 7K videos (251.4h total length) under 8 domains, providing comprehensive evaluations. We extensively evaluated 8 Image-LLMs and 12 Video-LLMs on our benchmark, and the results reveal that state-of-the-art models for coarse-level (video-level) understanding struggle to solve our fine-grained tasks, e.g., grounding event-of-interests within videos, largely due to the short video context length, improper time representations, and lack of multi-event training data. Focusing on these issues, we further propose a strong baseline model, E.T. Chat, together with an instruction-tuning dataset E.T. Instruct 164K tailored for fine-grained event-level understanding. Our simple but effective solution demonstrates superior performance in multiple scenarios.

[Arxiv](https://arxiv.org/abs/2409.18111)