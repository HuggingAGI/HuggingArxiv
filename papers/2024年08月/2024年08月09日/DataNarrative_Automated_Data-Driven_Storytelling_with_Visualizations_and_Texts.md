# DataNarrative：结合可视化与文本，实现数据驱动的自动化故事讲述

发布时间：2024年08月09日

`Agent` `数据可视化` `媒体与传播`

> DataNarrative: Automated Data-Driven Storytelling with Visualizations and Texts

# 摘要

> 数据驱动的故事讲述，通过融合叙事技巧与视觉和文本元素，成为传达洞察的强大工具。这些故事巧妙结合图表中的高亮元素和文本注释，生动展现数据背后的故事。然而，创作此类故事不仅需要深入理解数据，还需精心策划叙事流程，常需人工介入，过程既耗时又费神。尽管大型语言模型（LLM）在多项NLP任务中表现卓越，其在生成连贯且全面的数据故事方面的能力仍有待深入探索。本研究中，我们不仅提出了数据故事生成的新任务，还建立了一个包含1,449个多样故事的基准。为解决构建连贯数据故事的难题，我们设计了一个多代理框架，其中两个LLM代理模拟人类讲故事的流程：一个负责数据理解、描述、大纲生成及叙述，另一个则在每个环节进行验证。实验表明，我们的代理框架在模型和人类评估中均优于非代理方案，但也揭示了数据故事生成中的独特挑战。

> Data-driven storytelling is a powerful method for conveying insights by combining narrative techniques with visualizations and text. These stories integrate visual aids, such as highlighted bars and lines in charts, along with textual annotations explaining insights. However, creating such stories requires a deep understanding of the data and meticulous narrative planning, often necessitating human intervention, which can be time-consuming and mentally taxing. While Large Language Models (LLMs) excel in various NLP tasks, their ability to generate coherent and comprehensive data stories remains underexplored. In this work, we introduce a novel task for data story generation and a benchmark containing 1,449 stories from diverse sources. To address the challenges of crafting coherent data stories, we propose a multiagent framework employing two LLM agents designed to replicate the human storytelling process: one for understanding and describing the data (Reflection), generating the outline, and narration, and another for verification at each intermediary step. While our agentic framework generally outperforms non-agentic counterparts in both model-based and human evaluations, the results also reveal unique challenges in data story generation.

[Arxiv](https://arxiv.org/abs/2408.05346)