# MergeRepair：探索代码 LLM 中任务特定适配器的合并，以实现自动化程序修复的深入研究

发布时间：2024年08月18日

`LLM应用` `软件开发` `自动化程序修复`

> MergeRepair: An Exploratory Study on Merging Task-Specific Adapters in Code LLMs for Automated Program Repair

# 摘要

> 大型语言模型（LLM）在软件开发相关任务中表现卓越，如程序修复、文档编写等。适配器作为高效微调工具，无需全面再训练即可定制LLM。结合LLM与适配器已在多领域展现潜力，支持即插即用。本研究聚焦代码LLM中的适配器合并，特别是自动化程序修复（APR）任务，旨在揭示合并特定任务适配器对APR性能的影响。我们提出MergeRepair框架，采用三种合并方法，评估合并适配器在APR中的表现。研究涵盖等权重平均合并与持续合并两种场景，后者关注适配器合并顺序与权重。通过探索合并技术，我们旨在提升合并适配器在APR任务中的效能与泛化性，并深入理解任务顺序在实际软件项目中的作用。

> [Context] Large Language Models (LLMs) have shown good performance in several software development-related tasks such as program repair, documentation, code refactoring, debugging, and testing. Adapters are specialized, small modules designed for parameter efficient fine-tuning of LLMs for specific tasks, domains, or applications without requiring extensive retraining of the entire model. These adapters offer a more efficient way to customize LLMs for particular needs, leveraging the pre-existing capabilities of the large model. Merging LLMs and adapters has shown promising results for various natural language domains and tasks, enabling the use of the learned models and adapters without additional training for a new task. [Objective] This research proposes continual merging and empirically studies the capabilities of merged adapters in Code LLMs, specially for the Automated Program Repair (APR) task. The goal is to gain insights into whether and how merging task-specific adapters can affect the performance of APR. [Method] In our framework, MergeRepair, we plan to merge multiple task-specific adapters using three different merging methods and evaluate the performance of the merged adapter for the APR task. Particularly, we will employ two main merging scenarios for all three techniques, (i) merging using equal-weight averaging applied on parameters of different adapters, where all adapters are of equal importance; and (ii) our proposed approach, continual merging, in which we sequentially merge the task-specific adapters and the order and weight of merged adapters matter. By exploratory study of merging techniques, we will investigate the improvement and generalizability of merged adapters for APR. Through continual merging, we will explore the capability of merged adapters and the effect of task order, as it occurs in real-world software projects.

[Arxiv](https://arxiv.org/abs/2408.09568)