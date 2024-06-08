# 任务导向查询基准（ToQB），专注于评估和提升针对特定任务的查询性能。

发布时间：2024年06月05日

`Agent

这篇论文主要关注的是任务导向型查询的基准构建，特别是针对虚拟助手和聊天机器人等LLM服务的评估。论文中提到的任务导向型查询基准（ToQB）的构建，以及如何利用LLM服务执行这些任务，都是围绕着如何提高Agent（如虚拟助手、聊天机器人）的性能和效率。因此，这篇论文更适合归类到Agent分类中，因为它主要探讨了如何通过构建基准来评估和提升这些智能代理的能力。` `虚拟助手` `聊天机器人`

> The Task-oriented Queries Benchmark (ToQB)

# 摘要

> 任务导向型查询，如一键播放视频、订餐或叫车，是评估虚拟助手、聊天机器人等LLM服务质量的关键。但目前尚无针对此类查询的标准基准，因为现有NLP基准多聚焦于任务导向对话。为此，我们创新性地利用现有对话数据集和LLM服务，高效构建了任务导向型查询基准（ToQB）。该方法涉及制定NLP任务，提炼对话中说话者的原始意图，并详细阐述如何利用LLM服务执行这些任务，同时提供了一个自动化框架，以简化基准的生成。通过涵盖两个单任务领域和一个多任务领域的案例研究，我们展示了如何针对不同领域定制LLM提示，并分析了生成的任务导向型查询。ToQB数据集现已公开，我们亦探讨了社区如何扩展ToQB的新领域及其应用前景。

> Task-oriented queries (e.g., one-shot queries to play videos, order food, or call a taxi) are crucial for assessing the quality of virtual assistants, chatbots, and other large language model (LLM)-based services. However, a standard benchmark for task-oriented queries is not yet available, as existing benchmarks in the relevant NLP (Natural Language Processing) fields have primarily focused on task-oriented dialogues. Thus, we present a new methodology for efficiently generating the Task-oriented Queries Benchmark (ToQB) using existing task-oriented dialogue datasets and an LLM service. Our methodology involves formulating the underlying NLP task to summarize the original intent of a speaker in each dialogue, detailing the key steps to perform the devised NLP task using an LLM service, and outlining a framework for automating a major part of the benchmark generation process. Through a case study encompassing three domains (i.e., two single-task domains and one multi-task domain), we demonstrate how to customize the LLM prompts (e.g., omitting system utterances or speaker labels) for those three domains and characterize the generated task-oriented queries. The generated ToQB dataset is made available to the public. We further discuss new domains that can be added to ToQB by community contributors and its practical applications.

[Arxiv](https://arxiv.org/abs/2406.02943)