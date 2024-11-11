# WorkflowLLM：增强大型语言模型的工作流编排能力

发布时间：2024年11月08日

`LLM应用` `流程自动化` `工作流编排`

> WorkflowLLM: Enhancing Workflow Orchestration Capability of Large Language Models

# 摘要

> 大型语言模型（LLM）的最新进展通过基于 LLM 自动化工作流编排流程，推动了流程自动化从机器人流程自动化到智能体流程自动化的革命性范式转变。然而，现有的 LLM（甚至先进的 OpenAI GPT-4o）在工作流编排方面的能力仍不尽人意。为了解决这一限制，我们提出了 WorkflowLLM，这是一个以数据为中心精心设计的框架，旨在增强 LLM 在工作流编排方面的能力。它首先构建了一个包含 106,763 个样本的大规模微调数据集 WorkflowBench，涵盖了来自 28 个类别的 83 个应用程序的 1,503 个 API。具体来说，构建过程可分为三个阶段：（1）数据收集：我们从 Apple Shortcuts 和 RoutineHub 收集真实世界的工作流数据，将其转录为 Python 风格的代码。我们还通过 ChatGPT 为其配备生成的分层思维。（2）查询扩展：我们提示 ChatGPT 生成更多任务查询，以丰富工作流的多样性和复杂性。（3）工作流生成：我们利用在收集数据上训练的注释器模型为合成查询生成工作流。最后，我们将通过质量确认的合成样本与收集的样本合并，以获得 WorkflowBench。基于 WorkflowBench，我们对 Llama-3.1-8B 进行微调以获得 WorkflowLlama。我们的实验表明，WorkflowLlama 展示出了编排复杂工作流的强大能力，同时在以前未见过的 API 上也实现了显著的泛化性能。此外，WorkflowBench 在分布外任务规划数据集 T-Eval 上表现出强大的零样本泛化能力。我们的数据和代码可在 https://github.com/OpenBMB/WorkflowLLM 上获取。

> Recent advancements in large language models (LLMs) have driven a revolutionary paradigm shift in process automation from Robotic Process Automation to Agentic Process Automation by automating the workflow orchestration procedure based on LLMs. However, existing LLMs (even the advanced OpenAI GPT-4o) are confined to achieving satisfactory capability in workflow orchestration. To address this limitation, we present WorkflowLLM, a data-centric framework elaborately designed to enhance the capability of LLMs in workflow orchestration. It first constructs a large-scale fine-tuning dataset WorkflowBench with 106,763 samples, covering 1,503 APIs from 83 applications across 28 categories. Specifically, the construction process can be divided into three phases: (1) Data Collection: we collect real-world workflow data from Apple Shortcuts and RoutineHub, transcribing them into Python-style code. We further equip them with generated hierarchical thought via ChatGPT. (2) Query Expansion: we prompt ChatGPT to generate more task queries to enrich the diversity and complexity of workflows. (3) Workflow Generation: we leverage an annotator model trained on collected data to generate workflows for synthesized queries. Finally, we merge the synthetic samples that pass quality confirmation with the collected samples to obtain the WorkflowBench. Based on WorkflowBench, we fine-tune Llama-3.1-8B to obtain WorkflowLlama. Our experiments show that WorkflowLlama demonstrates a strong capacity to orchestrate complex workflows, while also achieving notable generalization performance on previously unseen APIs. Additionally, WorkflowBench exhibits robust zero-shot generalization capabilities on an out-of-distribution task planning dataset, T-Eval. Our data and code are available at https://github.com/OpenBMB/WorkflowLLM.

[Arxiv](https://arxiv.org/abs/2411.05451)