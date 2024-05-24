# ALI-Agent：基于代理评估大型语言模型与人类价值观的契合度

发布时间：2024年05月22日

`Agent

这篇论文介绍了一个名为ALI-Agent的框架，该框架利用大型语言模型（LLMs）驱动的代理来自主进行深入和适应性的对齐评估，以检测和解决LLMs与人类价值观不一致的问题。这个框架通过自动生成测试场景并迭代优化这些场景来探测潜在的长尾风险，从而减少了对专家设计的情境的依赖，并能够跟上LLMs的快速演进。因此，这篇论文属于Agent分类，因为它主要关注的是一个由LLM驱动的代理系统，用于评估和改进LLMs与人类价值观的一致性。` `人工智能安全` `社会伦理`

> ALI-Agent: Assessing LLMs' Alignment with Human Values via Agent-based Evaluation

# 摘要

> 当大型语言模型（LLMs）与人类价值观不协调时，可能会产生意外甚至有害的内容，对社会和用户构成严重威胁。为了应对这一挑战，现有的评估方法主要依赖专家设计的情境来检验LLMs与人类价值观的一致性，但这些方法因劳动密集且范围有限，难以覆盖多样化的开放世界应用，并识别那些虽罕见但至关重要的长尾风险。此外，这些静态测试无法跟上LLMs的快速演进，难以及时发现一致性问题。为此，我们开发了ALI-Agent，一个利用LLM驱动的代理自主进行深入和适应性对齐评估的框架。ALI-Agent通过模拟和精炼两个阶段运作：模拟阶段自动生成真实测试场景，精炼阶段则迭代优化这些场景以探测潜在的长尾风险。该框架通过记忆模块指导场景生成，工具使用模块减少人力需求，行动模块优化测试。在刻板印象、道德和法律三个维度上进行的广泛实验证明，ALI-Agent能有效识别模型与人类价值观的不一致。系统分析也确认了这些测试场景的有意义性，并增强了探测长尾风险的能力。我们的代码已公开在https://github.com/SophieZheng998/ALI-Agent.git。

> Large Language Models (LLMs) can elicit unintended and even harmful content when misaligned with human values, posing severe risks to users and society. To mitigate these risks, current evaluation benchmarks predominantly employ expert-designed contextual scenarios to assess how well LLMs align with human values. However, the labor-intensive nature of these benchmarks limits their test scope, hindering their ability to generalize to the extensive variety of open-world use cases and identify rare but crucial long-tail risks. Additionally, these static tests fail to adapt to the rapid evolution of LLMs, making it hard to evaluate timely alignment issues. To address these challenges, we propose ALI-Agent, an evaluation framework that leverages the autonomous abilities of LLM-powered agents to conduct in-depth and adaptive alignment assessments. ALI-Agent operates through two principal stages: Emulation and Refinement. During the Emulation stage, ALI-Agent automates the generation of realistic test scenarios. In the Refinement stage, it iteratively refines the scenarios to probe long-tail risks. Specifically, ALI-Agent incorporates a memory module to guide test scenario generation, a tool-using module to reduce human labor in tasks such as evaluating feedback from target LLMs, and an action module to refine tests. Extensive experiments across three aspects of human values--stereotypes, morality, and legality--demonstrate that ALI-Agent, as a general evaluation framework, effectively identifies model misalignment. Systematic analysis also validates that the generated test scenarios represent meaningful use cases, as well as integrate enhanced measures to probe long-tail risks. Our code is available at https://github.com/SophieZheng998/ALI-Agent.git

[Arxiv](https://arxiv.org/abs/2405.14125)