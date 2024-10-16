# SafeLLM：专为大型语言模型设计的领域特定安全监控系统，以海上风电维护为例进行探讨。

发布时间：2024年10月06日

`Agent`

> SafeLLM: Domain-Specific Safety Monitoring for Large Language Models: A Case Study of Offshore Wind Maintenance

# 摘要

> 离岸风电行业蓬勃发展，但运营维护成本也随之攀升。智能报警系统应运而生，旨在快速识别故障与异常，从而精准干预，降低资源消耗与停机时间。本文创新性地运用大型语言模型 (LLM) 来应对这一挑战。我们设计了一款对话代理，通过统计技术计算句子间距离，以过滤幻觉与不安全信息，进而优化报警解读，提升修复建议的安全性。初步实验基于 ChatGPT-4 生成数据，展示了该方法的潜力。同时，我们也探讨了 ChatGPT-4 的局限性，并展望了通过专用数据集再训练来进一步提升代理性能的可能性。

> The Offshore Wind (OSW) industry is experiencing significant expansion, resulting in increased Operations \& Maintenance (O\&M) costs. Intelligent alarm systems offer the prospect of swift detection of component failures and process anomalies, enabling timely and precise interventions that could yield reductions in resource expenditure, as well as scheduled and unscheduled downtime. This paper introduces an innovative approach to tackle this challenge by capitalising on Large Language Models (LLMs). We present a specialised conversational agent that incorporates statistical techniques to calculate distances between sentences for the detection and filtering of hallucinations and unsafe output. This potentially enables improved interpretation of alarm sequences and the generation of safer repair action recommendations by the agent. Preliminary findings are presented with the approach applied to ChatGPT-4 generated test sentences. The limitation of using ChatGPT-4 and the potential for enhancement of this agent through re-training with specialised OSW datasets are discussed.

[Arxiv](https://arxiv.org/abs/2410.10852)