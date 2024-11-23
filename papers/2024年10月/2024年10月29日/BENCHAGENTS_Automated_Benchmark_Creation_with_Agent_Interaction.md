# BENCHAGENTS：借助代理交互进行自动基准创建

发布时间：2024年10月29日

`Agent` `模型评估`

> BENCHAGENTS: Automated Benchmark Creation with Agent Interaction

# 摘要

> 评估受基准可用性所限。随着模型不断演进，有必要创建能够衡量新生成能力进展的基准。然而，靠人工注释来创建新基准，既缓慢又费钱，这限制了对任何能力的全面评估。我们推出了 BENCHAGENTS，这是一个有条不紊地借助大型语言模型（LLMs）为复杂能力自动创建基准的框架，同时能切实保证数据和指标的质量。BENCHAGENTS 将基准创建流程分解为规划、生成、数据验证和评估，每个环节都由一个 LLM 代理负责。这些代理相互作用，并利用来自基准开发人员的人工在环反馈，以显著提升并灵活把控数据的多样性和质量。我们用 BENCHAGENTS 创建基准，以评估文本生成过程中与规划和约束满足有关的能力。随后，我们借助这些基准研究七个顶尖模型，并获取有关常见故障模式和模型差异的新认识。

> Evaluations are limited by benchmark availability. As models evolve, there is a need to create benchmarks that can measure progress on new generative capabilities. However, creating new benchmarks through human annotations is slow and expensive, restricting comprehensive evaluations for any capability. We introduce BENCHAGENTS, a framework that methodically leverages large language models (LLMs) to automate benchmark creation for complex capabilities while inherently ensuring data and metric quality. BENCHAGENTS decomposes the benchmark creation process into planning, generation, data verification, and evaluation, each of which is executed by an LLM agent. These agents interact with each other and utilize human-in-the-loop feedback from benchmark developers to explicitly improve and flexibly control data diversity and quality. We use BENCHAGENTS to create benchmarks to evaluate capabilities related to planning and constraint satisfaction during text generation. We then use these benchmarks to study seven state-of-the-art models and extract new insights on common failure modes and model differences.

[Arxiv](https://arxiv.org/abs/2410.22584)