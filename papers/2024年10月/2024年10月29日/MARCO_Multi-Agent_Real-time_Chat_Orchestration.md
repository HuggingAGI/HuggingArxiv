# MARCO：多智能体实时聊天的编排

发布时间：2024年10月29日

`Agent`

> MARCO: Multi-Agent Real-time Chat Orchestration

# 摘要

> 大型语言模型的进步促使多智能体框架得以发展，从而能够应对复杂的现实世界难题，比如自动化那些需要与各类工具交互、进行推理以及人类协作的任务。我们推出了 MARCO，这是一个借助 LLMs 来实现任务自动化的多智能体实时聊天编排框架。MARCO 攻克了利用 LLMs 执行复杂多步骤任务时的关键难题。它融入了强大的防护栏，用于引导 LLM 的行为、校验输出，并从因输出格式不一致、函数和参数的幻觉以及领域知识缺失所引发的错误中恢复。通过广泛的实验，我们表明 MARCO 在数字餐厅服务平台对话和零售对话数据集的任务执行方面表现出色，准确率分别达到 94.48%和 92.74%，同时延迟降低 44.91%，成本减少 33.71%。我们还汇报了防护栏在性能增益方面的作用，以及对各种开源和专有的 LLM 模型的比较。MARCO 具有模块化和通用性的设计，能够适用于跨领域的任务自动化，并通过多轮交互来执行复杂的用例。

> Large language model advancements have enabled the development of multi-agent frameworks to tackle complex, real-world problems such as to automate tasks that require interactions with diverse tools, reasoning, and human collaboration. We present MARCO, a Multi-Agent Real-time Chat Orchestration framework for automating tasks using LLMs. MARCO addresses key challenges in utilizing LLMs for complex, multi-step task execution. It incorporates robust guardrails to steer LLM behavior, validate outputs, and recover from errors that stem from inconsistent output formatting, function and parameter hallucination, and lack of domain knowledge. Through extensive experiments we demonstrate MARCO's superior performance with 94.48% and 92.74% accuracy on task execution for Digital Restaurant Service Platform conversations and Retail conversations datasets respectively along with 44.91% improved latency and 33.71% cost reduction. We also report effects of guardrails in performance gain along with comparisons of various LLM models, both open-source and proprietary. The modular and generic design of MARCO allows it to be adapted for automating tasks across domains and to execute complex usecases through multi-turn interactions.

[Arxiv](https://arxiv.org/abs/2410.21784)