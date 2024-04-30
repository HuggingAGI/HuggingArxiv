# PECC：问题抽取与编码的挑战

发布时间：2024年04月29日

`LLM应用`

> PECC: Problem Extraction and Coding Challenges

# 摘要

> 近期大型语言模型（LLMs）的突破性进展在多种任务上展现了其非凡才能，包括代码编写、解题和推理等。尽管现有评估标准独立考量各项任务，但LLMs在理解散文式任务、识别潜在问题并生成恰当代码解决方案方面的真正能力尚未得到充分探究。为填补这一空白，我们提出了PECC，这是一个创新的基准测试，源自“代码的降临”（AoC）挑战和“欧拉计划”（Project Euler），共包含2396个问题。与传统基准测试不同，PECC要求LLMs解读嵌入叙述中的问题，提炼关键需求，并产出可执行的代码。我们数据集的独特之处在于，它通过模拟现实世界指令的模糊性，在基于聊天的评估中引入了自然语言提示，增加了问题的复杂性。测试结果显示，模型在处理叙述性问题与中性问题时表现不一，在以数学为基础的欧拉子集问题上尤为突出，GPT-3.5-Turbo在AoC挑战中的通过率达到了50%，而在欧拉问题上仅为8%。PECC通过挑战LLMs的极限，为我们提供了一个监测和评估LLMs作为全能问题解决者进步的框架。

> Recent advancements in large language models (LLMs) have showcased their exceptional abilities across various tasks, such as code generation, problem-solving and reasoning. Existing benchmarks evaluate tasks in isolation, yet the extent to which LLMs can understand prose-style tasks, identify the underlying problems, and then generate appropriate code solutions is still unexplored. Addressing this gap, we introduce PECC, a novel benchmark derived from Advent Of Code (AoC) challenges and Project Euler, including 2396 problems. Unlike conventional benchmarks, PECC requires LLMs to interpret narrative-embedded problems, extract requirements, and generate executable code. A key feature of our dataset is the complexity added by natural language prompting in chat-based evaluations, mirroring real-world instruction ambiguities. Results show varying model performance between narrative and neutral problems, with specific challenges in the Euler math-based subset with GPT-3.5-Turbo passing 50% of the AoC challenges and only 8% on the Euler problems. By probing the limits of LLMs' capabilities, our benchmark provides a framework to monitor and assess the subsequent progress of LLMs as a universal problem solver.

[Arxiv](https://arxiv.org/abs/2404.18766)