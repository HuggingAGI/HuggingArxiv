# 代理工作流生成的基准测试

发布时间：2024年10月10日

`LLM应用` `人工智能` `软件工程`

> Benchmarking Agentic Workflow Generation

# 摘要

> 大型语言模型 (LLM) 在处理推理和规划任务方面表现出色，其中将复杂问题分解为可执行工作流程是关键。然而，现有评估框架要么过于笼统，要么存在局限，如场景覆盖不足、结构简单和标准宽松。为此，我们推出了 WorFBench，一个集多场景和复杂图结构于一体的工作流程生成基准。同时，我们提出了 WorFEval，通过子序列和子图匹配算法，系统评估 LLM 的工作流程生成能力。评估显示，LLM 在序列和图规划能力上存在显著差异，GPT-4 也有约 15% 的差距。我们还训练了两个开源模型，并测试了其泛化能力。此外，生成的工作流程能显著提升下游任务的性能，缩短推理时间。代码和数据集即将在 https://github.com/zjunlp/WorFBench 发布。

> Large Language Models (LLMs), with their exceptional ability to handle a wide range of tasks, have driven significant advancements in tackling reasoning and planning tasks, wherein decomposing complex problems into executable workflows is a crucial step in this process. Existing workflow evaluation frameworks either focus solely on holistic performance or suffer from limitations such as restricted scenario coverage, simplistic workflow structures, and lax evaluation standards. To this end, we introduce WorFBench, a unified workflow generation benchmark with multi-faceted scenarios and intricate graph workflow structures. Additionally, we present WorFEval, a systemic evaluation protocol utilizing subsequence and subgraph matching algorithms to accurately quantify the LLM agent's workflow generation capabilities. Through comprehensive evaluations across different types of LLMs, we discover distinct gaps between the sequence planning capabilities and graph planning capabilities of LLM agents, with even GPT-4 exhibiting a gap of around 15%. We also train two open-source models and evaluate their generalization abilities on held-out tasks. Furthermore, we observe that the generated workflows can enhance downstream tasks, enabling them to achieve superior performance with less time during inference. Code and dataset will be available at https://github.com/zjunlp/WorFBench.

[Arxiv](https://arxiv.org/abs/2410.07869)