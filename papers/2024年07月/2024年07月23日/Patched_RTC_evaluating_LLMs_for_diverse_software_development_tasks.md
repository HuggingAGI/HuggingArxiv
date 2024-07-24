# Patched RTC：探索 LLM 在多元软件开发任务中的应用评估

发布时间：2024年07月23日

`LLM应用` `软件开发` `人工智能`

> Patched RTC: evaluating LLMs for diverse software development tasks

# 摘要

> 本文引入了 Patched Round-Trip Correctness (Patched RTC)，这是一种针对大型语言模型 (LLM) 在软件开发任务中的新颖评估技术，尤其关注错误修复、代码审查和文档更新等“外循环”活动。Patched RTC 扩展了原有的 Round-Trip Correctness 方法，适用于任何 LLM 和下游任务，提供了一个自动评估模型响应一致性和鲁棒性的框架。研究显示，Patched RTC 得分与特定任务的准确性指标相关，为开放领域任务评估提供了一种替代 LLM-as-Judge 范式的方法。我们在开源框架 patchwork 中实现了 Patched RTC，支持在推理过程中对不同 patchflows 进行透明评估。实验比较了 GPT-3.5 和 GPT-4 在不同软件开发任务中的表现，证明 Patched RTC 能有效区分模型性能和任务难度。此外，本文还探讨了如何通过一致性提示提升模型准确性，表明 Patched RTC 可用于指导复杂软件开发流程中的提示优化和模型选择。

> This paper introduces Patched Round-Trip Correctness (Patched RTC), a novel evaluation technique for Large Language Models (LLMs) applied to diverse software development tasks, particularly focusing on "outer loop" activities such as bug fixing, code review, and documentation updates. Patched RTC extends the original Round-Trip Correctness method to work with any LLM and downstream task, offering a self-evaluating framework that measures consistency and robustness of model responses without human intervention. The study demonstrates a correlation between Patched RTC scores and task-specific accuracy metrics, presenting it as an alternative to the LLM-as-Judge paradigm for open-domain task evaluation. We implement Patched RTC in an open-source framework called patchwork, allowing for transparent evaluation during inference across various patchflows. Experiments comparing GPT-3.5 and GPT-4 models across different software development tasks reveal that Patched RTC effectively distinguishes model performance and task difficulty. The paper also explores the impact of consistency prompts on improving model accuracy, suggesting that Patched RTC can guide prompt refinement and model selection for complex software development workflows.

[Arxiv](https://arxiv.org/abs/2407.16557)