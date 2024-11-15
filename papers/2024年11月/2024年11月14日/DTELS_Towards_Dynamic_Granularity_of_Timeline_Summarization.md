# DTELS：致力于实现时间线摘要的动态粒度化

发布时间：2024年11月14日

`LLM应用` `时间线总结`

> DTELS: Towards Dynamic Granularity of Timeline Summarization

# 摘要

> 在线新闻的快速增长给追踪新闻主题的持续发展带来了巨大挑战。传统的时间线总结虽构建了事件的时间顺序摘要，却常缺乏满足不同粒度需求的灵活性。为突破此限制，我们引入新范式——动态粒度时间线总结（DTELS），旨在依据用户指令或要求构建自适应时间线。本文为 DTLES 设立了全面基准，涵盖：（1）基于新闻标准的评估框架，从信息量、粒度一致性、真实性和连贯性这四个维度评估时间线质量；（2）基于共识流程、带有多粒度时间线标注的大规模多源数据集，以增强权威性；（3）运用基于大型语言模型（LLMs）的两个提出的方案和现有的顶尖 TLS 方法进行了大量实验与分析。实验结果显示了基于 LLM 方案的有效性。然而，即便是最先进的 LLMs 也难以持续生成兼具信息量和粒度一致性的时间线，凸显了 DTELS 任务的难题。

> The rapid proliferation of online news has posed significant challenges in tracking the continuous development of news topics. Traditional timeline summarization constructs a chronological summary of the events but often lacks the flexibility to meet the diverse granularity needs. To overcome this limitation, we introduce a new paradigm, Dynamic-granularity TimELine Summarization, (DTELS), which aims to construct adaptive timelines based on user instructions or requirements. This paper establishes a comprehensive benchmark for DTLES that includes: (1) an evaluation framework grounded in journalistic standards to assess the timeline quality across four dimensions: Informativeness, Granular Consistency, Factuality, and Coherence; (2) a large-scale, multi-source dataset with multiple granularity timeline annotations based on a consensus process to facilitate authority; (3) extensive experiments and analysis with two proposed solutions based on Large Language Models (LLMs) and existing state-of-the-art TLS methods. The experimental results demonstrate the effectiveness of LLM-based solutions. However, even the most advanced LLMs struggle to consistently generate timelines that are both informative and granularly consistent, highlighting the challenges of the DTELS task.

[Arxiv](https://arxiv.org/abs/2411.09297)