# DTVLT：一个基于 LLM 的视觉语言跟踪多模态多样化文本基准

发布时间：2024年10月03日

`LLM应用` `视频理解` `人工智能`

> DTVLT: A Multi-modal Diverse Text Benchmark for Visual Language Tracking Based on LLM

# 摘要

> 视觉语言跟踪 (VLT) 是当前研究的热点，通过融合语言数据，提升多模态算法的性能，并将传统单对象跟踪 (SOT) 扩展至视频理解领域。然而，现有 VLT 基准多依赖于简短的人工注释，这些描述难以捕捉视频动态的细微之处，且语言风格单一。这导致算法倾向于“死记硬背”，而非深入理解视频内容。借助大型语言模型 (LLM)，我们能够生成多样化的文本注释。为此，我们创建了名为 DTVLT 的新基准，涵盖短期、长期和全局实例跟踪三大任务，并提供四种不同粒度的文本注释。我们希望通过这种多粒度策略，推动 VLT 和视频理解的研究。此外，我们还对 DTVLT 进行了全面实验，分析了多样化文本对跟踪性能的影响，并识别了现有算法的性能瓶颈，以期为后续研究提供支持。相关基准、实验结果和工具包将陆续在 http://videocube.aitestunion.com/ 发布。

> Visual language tracking (VLT) has emerged as a cutting-edge research area, harnessing linguistic data to enhance algorithms with multi-modal inputs and broadening the scope of traditional single object tracking (SOT) to encompass video understanding applications. Despite this, most VLT benchmarks still depend on succinct, human-annotated text descriptions for each video. These descriptions often fall short in capturing the nuances of video content dynamics and lack stylistic variety in language, constrained by their uniform level of detail and a fixed annotation frequency. As a result, algorithms tend to default to a "memorize the answer" strategy, diverging from the core objective of achieving a deeper understanding of video content. Fortunately, the emergence of large language models (LLMs) has enabled the generation of diverse text. This work utilizes LLMs to generate varied semantic annotations (in terms of text lengths and granularities) for representative SOT benchmarks, thereby establishing a novel multi-modal benchmark. Specifically, we (1) propose a new visual language tracking benchmark with diverse texts, named DTVLT, based on five prominent VLT and SOT benchmarks, including three sub-tasks: short-term tracking, long-term tracking, and global instance tracking. (2) We offer four granularity texts in our benchmark, considering the extent and density of semantic information. We expect this multi-granular generation strategy to foster a favorable environment for VLT and video understanding research. (3) We conduct comprehensive experimental analyses on DTVLT, evaluating the impact of diverse text on tracking performance and hope the identified performance bottlenecks of existing algorithms can support further research in VLT and video understanding. The proposed benchmark, experimental results and toolkit will be released gradually on http://videocube.aitestunion.com/.

[Arxiv](https://arxiv.org/abs/2410.02492)