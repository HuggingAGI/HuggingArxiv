# MCCoder：借助 LLM 辅助代码生成与严格验证，简化运动控制流程。

发布时间：2024年10月19日

`LLM应用` `自动化` `运动控制`

> MCCoder: Streamlining Motion Control with LLM-Assisted Code Generation and Rigorous Verification

# 摘要

> 大型语言模型 (LLM) 在代码生成领域展现出巨大潜力，但在自动化特别是运动控制领域，由于任务复杂和安全要求高，仍依赖手动编程。为此，我们推出了 MCCoder，一个由 LLM 驱动的系统，专为复杂运动控制任务设计，并集成了软运动数据验证。MCCoder 通过多任务分解、混合检索增强生成 (RAG) 和自校正机制，显著提升代码生成质量。它还通过详细轨迹数据记录和模拟图表，支持数据验证，增强用户对生成代码的信心。为确保验证的稳健性，我们提出了 MCEVAL，一个针对不同难度运动控制任务定制的评估数据集。实验显示，MCCoder 在 MCEVAL 数据集上的整体性能提升 11.61%，复杂任务提升 66.12%。该系统和数据集旨在推动在严格安全要求的自动化环境中应用代码生成。MCCoder 已在 https://github.com/MCCodeAI/MCCoder 公开发布。

> Large Language Models (LLMs) have shown considerable promise in code generation. However, the automation sector, especially in motion control, continues to rely heavily on manual programming due to the complexity of tasks and critical safety considerations. In this domain, incorrect code execution can pose risks to both machinery and personnel, necessitating specialized expertise. To address these challenges, we introduce MCCoder, an LLM-powered system designed to generate code that addresses complex motion control tasks, with integrated soft-motion data verification. MCCoder enhances code generation through multitask decomposition, hybrid retrieval-augmented generation (RAG), and self-correction with a private motion library. Moreover, it supports data verification by logging detailed trajectory data and providing simulations and plots, allowing users to assess the accuracy of the generated code and bolstering confidence in LLM-based programming. To ensure robust validation, we propose MCEVAL, an evaluation dataset with metrics tailored to motion control tasks of varying difficulties. Experiments indicate that MCCoder improves performance by 11.61% overall and by 66.12% on complex tasks in MCEVAL dataset compared with base models with naive RAG. This system and dataset aim to facilitate the application of code generation in automation settings with strict safety requirements. MCCoder is publicly available at https://github.com/MCCodeAI/MCCoder.

[Arxiv](https://arxiv.org/abs/2410.15154)