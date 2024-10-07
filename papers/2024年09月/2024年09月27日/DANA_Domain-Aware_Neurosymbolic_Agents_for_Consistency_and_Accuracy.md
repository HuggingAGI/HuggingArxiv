# DANA：专为提升一致性与准确性而设计的领域感知神经符号代理

发布时间：2024年09月27日

`Agent` `半导体`

> DANA: Domain-Aware Neurosymbolic Agents for Consistency and Accuracy

# 摘要

> 尽管大型语言模型 (LLM) 表现出色，但其概率性本质常导致复杂任务中的不一致与不准确。本文提出的 DANA（领域感知神经符号代理）通过融合领域知识与神经符号方法，有效应对这一挑战。我们首先审视现有 AI 架构，如 AutoGPT、LangChain ReAct 和 ChatGPT，揭示其概率推理如何引发输出波动。为此，DANA 巧妙融合自然语言与符号形式的领域专长，提升问题解决的确定性与可靠性。在 OpenSSA 框架中，我们采用分层任务计划 (HTP) 实现 DANA，使其在 FinanceBench 金融分析基准测试中准确率超 90%，显著超越现有 LLM 系统。DANA 在半导体等行业的应用进一步证明，其灵活的知识整合架构能有效克服 LLM 的概率局限，有望应对复杂现实问题，确保可靠与精准。

> Large Language Models (LLMs) have shown remarkable capabilities, but their inherent probabilistic nature often leads to inconsistency and inaccuracy in complex problem-solving tasks. This paper introduces DANA (Domain-Aware Neurosymbolic Agent), an architecture that addresses these issues by integrating domain-specific knowledge with neurosymbolic approaches. We begin by analyzing current AI architectures, including AutoGPT, LangChain ReAct and OpenAI's ChatGPT, through a neurosymbolic lens, highlighting how their reliance on probabilistic inference contributes to inconsistent outputs. In response, DANA captures and applies domain expertise in both natural-language and symbolic forms, enabling more deterministic and reliable problem-solving behaviors. We implement a variant of DANA using Hierarchical Task Plans (HTPs) in the open-source OpenSSA framework. This implementation achieves over 90\% accuracy on the FinanceBench financial-analysis benchmark, significantly outperforming current LLM-based systems in both consistency and accuracy. Application of DANA in physical industries such as semiconductor shows that its flexible architecture for incorporating knowledge is effective in mitigating the probabilistic limitations of LLMs and has potential in tackling complex, real-world problems that require reliability and precision.

[Arxiv](https://arxiv.org/abs/2410.02823)