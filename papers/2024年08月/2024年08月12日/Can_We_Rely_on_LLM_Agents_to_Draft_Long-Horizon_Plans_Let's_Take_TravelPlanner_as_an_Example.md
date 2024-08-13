# LLM 代理能否胜任长期计划的制定？以 TravelPlanner 为例，我们探讨这一问题。

发布时间：2024年08月12日

`Agent` `人工智能` `旅游规划`

> Can We Rely on LLM Agents to Draft Long-Horizon Plans? Let's Take TravelPlanner as an Example

# 摘要

> 大型语言模型 (LLM) 因其卓越的泛化能力和涌现能力，正推动自主代理向人工通用智能 (AGI) 迈进。然而，关于这些基于 LLM 的代理在现实世界规划任务中的行为、潜在失败原因及改进方法的研究尚显不足。本文通过使用现实基准 TravelPlanner 进行研究，旨在填补这一研究空白。在该基准中，代理需满足多重约束以生成精确计划。我们针对四个关键问题展开研究：(1) LLM 代理在处理长且复杂的上下文时，其推理和规划能力是否稳健？(2) 少量提示是否会在长上下文场景中损害 LLM 代理的性能？(3) 通过细化能否有效提升计划质量？(4) 结合正负反馈进行微调是否能进一步优化 LLM？实验结果显示，尽管 LLM 能处理大量信息和示例，但它们在关注长上下文的关键部分时仍显不足；同时，在分析长计划和提供准确反馈方面也面临挑战。为此，我们提出反馈感知微调 (FAFT)，通过整合正负反馈，显著提升了性能，超越了传统的监督微调 (SFT)。这些发现为现实世界规划应用提供了宝贵的深入见解。

> Large language models (LLMs) have brought autonomous agents closer to artificial general intelligence (AGI) due to their promising generalization and emergent capabilities. There is, however, a lack of studies on how LLM-based agents behave, why they could potentially fail, and how to improve them, particularly in demanding real-world planning tasks. In this paper, as an effort to fill the gap, we present our study using a realistic benchmark, TravelPlanner, where an agent must meet multiple constraints to generate accurate plans. We leverage this benchmark to address four key research questions: (1) are LLM agents robust enough to lengthy and noisy contexts when it comes to reasoning and planning? (2) can few-shot prompting adversely impact the performance of LLM agents in scenarios with long context? (3) can we rely on refinement to improve plans, and (4) can fine-tuning LLMs with both positive and negative feedback lead to further improvement? Our comprehensive experiments indicate that, firstly, LLMs often fail to attend to crucial parts of a long context, despite their ability to handle extensive reference information and few-shot examples; secondly, they still struggle with analyzing the long plans and cannot provide accurate feedback for refinement; thirdly, we propose Feedback-Aware Fine-Tuning (FAFT), which leverages both positive and negative feedback, resulting in substantial gains over Supervised Fine-Tuning (SFT). Our findings offer in-depth insights to the community on various aspects related to real-world planning applications.

[Arxiv](https://arxiv.org/abs/2408.06318)