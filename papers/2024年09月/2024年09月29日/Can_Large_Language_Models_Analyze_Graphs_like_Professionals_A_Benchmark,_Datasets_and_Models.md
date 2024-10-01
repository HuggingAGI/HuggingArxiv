# 大型语言模型能否媲美专业人士的图表分析能力？本文将介绍一个基准测试、相关数据集及模型。

发布时间：2024年09月29日

`LLM应用` `人工智能` `图分析`

> Can Large Language Models Analyze Graphs like Professionals? A Benchmark, Datasets and Models

# 摘要

> 图分析在多个领域中至关重要，从社交网络到生物研究再到推荐系统。因此，让大型语言模型 (LLM) 处理图数据是迈向更高级智能的关键一步。然而，当前的 LLM 图分析基准仅限于小规模图，而人类专家则能通过编程处理各种规模的图。我们不禁要问：LLM 能否像专家一样分析图？为此，我们推出了 ProGraph 基准，包含三类图任务，要求基于编程而非直接推理。研究发现，当前 LLM 的性能不尽如人意，最佳模型准确率仅为 36%。为解决这一问题，我们创建了 LLM4Graph 数据集，包含基于六大图库的文档和代码。通过增强 LLM 的文档检索和代码微调，我们实现了 11-32% 的准确率提升。这表明 LLM 在处理结构化数据方面的潜力仍待挖掘，而 LLM4Graph 则有效提升了 LLM 的图分析能力。相关资源已发布在 https://github.com/BUPT-GAMMA/ProGraph。

> The need to analyze graphs is ubiquitous across various fields, from social networks to biological research and recommendation systems. Therefore, enabling the ability of large language models (LLMs) to process graphs is an important step toward more advanced general intelligence. However, current LLM benchmarks on graph analysis require models to directly reason over the prompts describing graph topology, and are thus limited to small graphs with only a few dozens of nodes. In contrast, human experts typically write programs based on popular libraries for task solving, and can thus handle graphs with different scales. To this end, a question naturally arises: can LLMs analyze graphs like professionals? In this paper, we introduce ProGraph, a manually crafted benchmark containing 3 categories of graph tasks. The benchmark expects solutions based on programming instead of directly reasoning over raw inputs. Our findings reveal that the performance of current LLMs is unsatisfactory, with the best model achieving only 36% accuracy. To bridge this gap, we propose LLM4Graph datasets, which include crawled documents and auto-generated codes based on 6 widely used graph libraries. By augmenting closed-source LLMs with document retrieval and fine-tuning open-source ones on the codes, we show 11-32% absolute improvements in their accuracies. Our results underscore that the capabilities of LLMs in handling structured data are still under-explored, and show the effectiveness of LLM4Graph in enhancing LLMs' proficiency of graph analysis. The benchmark, datasets and enhanced open-source models are available at https://github.com/BUPT-GAMMA/ProGraph.

[Arxiv](https://arxiv.org/abs/2409.19667)