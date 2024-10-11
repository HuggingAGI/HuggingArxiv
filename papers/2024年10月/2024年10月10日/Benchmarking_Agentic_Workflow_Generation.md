# 代理工作流生成的基准测试

发布时间：2024年10月10日

`LLM应用` `人工智能` `软件工程`

> Benchmarking Agentic Workflow Generation

# 摘要

> LLM 在处理推理和规划任务方面表现出色，但现有评估框架多有不足。为此，我们推出了 WorFBench，一个涵盖多场景和复杂图结构的统一基准。同时，WorFEval 通过子序列和子图匹配算法，精准评估 LLM 的工作流程生成能力。评估显示，即使是 GPT-4，其序列和图规划能力也有约 15% 的差距。我们还训练了两个开源模型，并验证了其泛化能力。此外，生成的工作流程能显著提升下游任务的性能，缩短推理时间。代码和数据集即将在 GitHub 上公开。

> Large Language Models (LLMs), with their exceptional ability to handle a wide range of tasks, have driven significant advancements in tackling reasoning and planning tasks, wherein decomposing complex problems into executable workflows is a crucial step in this process. Existing workflow evaluation frameworks either focus solely on holistic performance or suffer from limitations such as restricted scenario coverage, simplistic workflow structures, and lax evaluation standards. To this end, we introduce WorFBench, a unified workflow generation benchmark with multi-faceted scenarios and intricate graph workflow structures. Additionally, we present WorFEval, a systemic evaluation protocol utilizing subsequence and subgraph matching algorithms to accurately quantify the LLM agent's workflow generation capabilities. Through comprehensive evaluations across different types of LLMs, we discover distinct gaps between the sequence planning capabilities and graph planning capabilities of LLM agents, with even GPT-4 exhibiting a gap of around 15%. We also train two open-source models and evaluate their generalization abilities on held-out tasks. Furthermore, we observe that the generated workflows can enhance downstream tasks, enabling them to achieve superior performance with less time during inference. Code and dataset will be available at https://github.com/zjunlp/WorFBench.

[Arxiv](https://arxiv.org/abs/2410.07869)