# 利用 REAP 提升 LLM 问题解决：反思、明确问题分解与高级提示技巧

发布时间：2024年09月14日

`LLM应用` `人工智能`

> Enhancing LLM Problem Solving with REAP: Reflection, Explicit Problem Deconstruction, and Advanced Prompting

# 摘要

> 大型语言模型（LLM）虽然已彻底改变自然语言处理，但在解决复杂推理任务方面仍有提升空间。本文提出的 REAP 方法，通过反思、问题分解和高级提示，显著提升了 LLM 的解题能力。实验结果显示，REAP 在多个先进模型中均带来显著性能提升，如 GPT-4o-mini 性能提升高达 112.93%。此外，REAP 不仅提升性能，还降低了成本，如 GPT-4o-mini 以更低成本实现了优异表现。REAP 还增强了模型输出的清晰度，便于人类理解和纠错。这些成果展示了 REAP 在提升 LLM 性能和成本效益方面的巨大潜力。

> Large Language Models (LLMs) have transformed natural language processing, yet improving their problem-solving capabilities, particularly for complex, reasoning-intensive tasks, remains a persistent challenge. This paper introduces the REAP (Reflection, Explicit Problem Deconstruction, and Advanced Prompting) method, an innovative approach within the dynamic context generation framework. REAP guides LLMs through reflection on the query, deconstructing it into manageable components, and generating relevant context to enhance the solution process. We evaluated REAP using a dataset designed to expose LLM limitations, comparing zero-shot prompting with REAP-enhanced prompts across six state-of-the-art models: OpenAI's o1-preview, o1-mini, GPT-4o, GPT-4o-mini, Google's Gemini 1.5 Pro, and Claude 3.5 Sonnet. The results demonstrate notable performance gains, with o1-mini improving by 40.97%, GPT-4o by 66.26%, and GPT-4o-mini by 112.93%. Despite the already strong baseline performance of OpenAI's o1-preview, modest gains were observed. Beyond performance improvements, REAP offers a cost-effective solution; for example, GPT-4o-mini, which is approximately 100 times cheaper than o1-preview, delivered competitive results. REAP also improves the clarity of model outputs, making it easier for humans to understand the reasoning behind the results and simplifying the process of identifying and addressing any issues. These findings demonstrate REAP's potential to greatly improve the capabilities of LLMs, providing both better performance and increased cost-efficiency across a wide range of applications.

[Arxiv](https://arxiv.org/abs/2409.09415)