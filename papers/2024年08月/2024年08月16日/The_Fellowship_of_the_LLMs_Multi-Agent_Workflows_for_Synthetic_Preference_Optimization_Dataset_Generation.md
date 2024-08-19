# LLM 的联盟：多代理工作流程助力合成偏好优化数据集的生成

发布时间：2024年08月16日

`Agent` `人工智能` `数据科学`

> The Fellowship of the LLMs: Multi-Agent Workflows for Synthetic Preference Optimization Dataset Generation

# 摘要

> 本文探讨并评估了合成偏好优化（PO）数据集的多代理生成流程。该流程包含两个核心模块：响应评估与响应生成。在响应评估环节，我们利用大型语言模型（LLM）自动评估并排序响应，替代传统的人工标注。通过两阶段评估流程，我们首先测试了三种提示策略下LLM的评估能力，随后采用最佳策略对比了LLM-as-a-Judge、LLM-as-a-Jury及LLM Debate的性能。每阶段均通过Cohen's Kappa衡量人机评分一致性。在响应生成模块，我们基于选定的LLM评估配置，对比了不同反馈循环设置，并依据胜率确定最优多代理配置。最终，我们结合GPT、Gemma和Llama系列模型，生成两类PO数据集：一是提升单个LLM生成质量，二是优化多代理协作流程。评估结果表明，GPT-4o-as-a-Judge在非GPT系列响应中表现更稳定，而Llama-Gemma组合的反馈循环在胜率上显著超越了单一代理模型。

> This paper presents and evaluates multi-agent workflows for synthetic Preference Optimization (PO) dataset generation. PO dataset generation requires two modules: (1) response evaluation, and (2) response generation. In the response evaluation module, the responses from Large Language Models (LLMs) are evaluated and ranked - a task typically carried out by human annotators that we automate using LLMs. We assess the response evaluation module in a 2 step process. In step 1, we assess LLMs as evaluators using three distinct prompting strategies. In step 2, we apply the winning prompting strategy to compare the performance of LLM-as-a-Judge, LLMs-as-a-Jury, and LLM Debate. In each step, we use inter-rater agreement using Cohen's Kappa between human annotators and LLMs. For the response generation module, we compare different configurations for the LLM Feedback Loop using the identified LLM evaluator configuration. We use the win rate (the fraction of times a generation framework is selected as the best by an LLM evaluator) to determine the best multi-agent configuration for generation. After identifying the best configurations for both modules, we use models from the GPT, Gemma, and Llama families to generate our PO datasets using the above pipeline. We generate two types of PO datasets, one to improve the generation capabilities of individual LLM and the other to improve the multi-agent workflow. Our evaluation shows that GPT-4o-as-a-Judge is more consistent across datasets when the candidate responses do not include responses from the GPT family. Additionally, we find that the LLM Feedback Loop, with Llama as the generator and Gemma as the reviewer, achieves a notable 71.8% and 73.8% win rate over single-agent Llama and Gemma, respectively.

[Arxiv](https://arxiv.org/abs/2408.08688)