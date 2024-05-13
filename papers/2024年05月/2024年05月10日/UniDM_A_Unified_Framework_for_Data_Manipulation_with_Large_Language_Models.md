# UniDM：大型语言模型数据操作的统一之桥在人工智能的浩瀚星空中，UniDM犹如一座横跨数据与智慧的桥梁，以其统一之姿，将大型语言模型的数据操作能力汇聚于一点。它不仅是一套框架，更是一种艺术，一种将数据的纷繁复杂转化为模型智慧的精湛技艺。在这个框架下，数据的每一次舞动，都仿佛在诉说着与模型深度对话的故事，引领我们探索数据科学的无限可能。

发布时间：2024年05月10日

`Agent

这篇论文介绍了一种名为UniDM的框架，旨在实现数据操作任务的自动化和通用化。它将多样的数据操作任务统一化，并提炼出三个核心步骤，包括自动上下文检索功能和精心设计的提示，以引导LLMs产出高质量结果。这种框架可以被视为一个智能代理（Agent），因为它能够自主地执行数据操作任务，而不需要为每个任务定制设计。因此，这篇论文属于Agent分类。` `数据湖` `数据操作自动化`

> UniDM: A Unified Framework for Data Manipulation with Large Language Models

# 摘要

> 在数据湖领域，设计高效的数据操作方法一直是个挑战。传统方法耗费人力在数据收集和模型调优上，而新兴的LLMs方法虽在性能上有所突破，却需为每个任务定制设计，成本高昂且难以满足大数据湖平台的需求。本文受LLMs在NLP任务上的跨任务通用性启发，提出UniDM框架，旨在实现数据操作任务的自动化和通用化。UniDM将多样的数据操作任务统一化，并提炼出三个核心步骤。我们开发的自动上下文检索功能，使LLMs能从数据湖中提取信息，而精心设计的提示则引导LLMs产出高质量结果。经过多轮测试，UniDM在各类数据操作任务上展现了卓越的通用性和顶尖性能。

> Designing effective data manipulation methods is a long standing problem in data lakes. Traditional methods, which rely on rules or machine learning models, require extensive human efforts on training data collection and tuning models. Recent methods apply Large Language Models (LLMs) to resolve multiple data manipulation tasks. They exhibit bright benefits in terms of performance but still require customized designs to fit each specific task. This is very costly and can not catch up with the requirements of big data lake platforms. In this paper, inspired by the cross-task generality of LLMs on NLP tasks, we pave the first step to design an automatic and general solution to tackle with data manipulation tasks. We propose UniDM, a unified framework which establishes a new paradigm to process data manipulation tasks using LLMs. UniDM formalizes a number of data manipulation tasks in a unified form and abstracts three main general steps to solve each task. We develop an automatic context retrieval to allow the LLMs to retrieve data from data lakes, potentially containing evidence and factual information. For each step, we design effective prompts to guide LLMs to produce high quality results. By our comprehensive evaluation on a variety of benchmarks, our UniDM exhibits great generality and state-of-the-art performance on a wide variety of data manipulation tasks.

[Arxiv](https://arxiv.org/abs/2405.06510)