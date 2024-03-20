# VideoAgent，一款搭载记忆增强技术的多模态智能体，专为深入理解视频内容而设计。

发布时间：2024年03月18日

`Agent` `视频理解` `多模态`

> VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding

> 我们研究如何借助新颖的统一记忆机制，将多个基础模型（如大型语言模型和视觉-语言模型）融合起来，以攻克复杂视频理解难题，特别关注长视频中长时间跨度的关系捕捉。创新提出的VideoAgent多模态智能体独树一帜：首先，它构建了一个结构化的记忆系统，能够同时储存视频中普遍的时间事件叙述和以对象为中心的追踪状态；其次，面对任务查询输入时，VideoAgent灵活调动一系列工具，如视频片段定位、对象记忆查询等，并联手其他视觉基础模型，借力LLMs的零样本工具运用能力，实现交互式任务解答。实验证明，VideoAgent在多个长时序视频理解基准测试上成绩斐然，相较于基准方法，在NExT-QA任务上平均提升了6.6%，在EgoSchema任务上更是飙升26.0%，大大缩短了开源模型与诸如Gemini 1.5 Pro等私有模型间的性能差距。

> We explore how reconciling several foundation models (large language models and vision-language models) with a novel unified memory mechanism could tackle the challenging video understanding problem, especially capturing the long-term temporal relations in lengthy videos. In particular, the proposed multimodal agent VideoAgent: 1) constructs a structured memory to store both the generic temporal event descriptions and object-centric tracking states of the video; 2) given an input task query, it employs tools including video segment localization and object memory querying along with other visual foundation models to interactively solve the task, utilizing the zero-shot tool-use ability of LLMs. VideoAgent demonstrates impressive performances on several long-horizon video understanding benchmarks, an average increase of 6.6% on NExT-QA and 26.0% on EgoSchema over baselines, closing the gap between open-sourced models and private counterparts including Gemini 1.5 Pro.

[Arxiv](https://arxiv.org/abs/2403.11481)