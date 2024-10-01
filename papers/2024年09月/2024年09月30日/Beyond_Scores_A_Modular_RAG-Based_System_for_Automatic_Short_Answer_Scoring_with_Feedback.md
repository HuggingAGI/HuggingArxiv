# 超越分数：一个模块化 RAG 系统，专为自动简短答案评分并提供反馈而设计

发布时间：2024年09月30日

`RAG` `人工智能`

> Beyond Scores: A Modular RAG-Based System for Automatic Short Answer Scoring with Feedback

# 摘要

> 自动简答评分 (ASAS) 虽能减轻教师负担，但反馈常显粗略。现有 ASAS-F 方法依赖于资源密集型的微调，且泛化能力有限。最新 LLM 方法虽无需广泛微调，但评分时过度依赖提示工程，反馈质量参差不齐。本文提出一种模块化检索增强生成系统，在零-shot 和少-shot 场景下高效评分并生成反馈。该系统灵活适应各类教育任务，自动生成提示，无需繁琐工程。实验表明，评分准确性提升 9%，为教育领域带来可扩展且经济的解决方案。

> Automatic short answer scoring (ASAS) helps reduce the grading burden on educators but often lacks detailed, explainable feedback. Existing methods in ASAS with feedback (ASAS-F) rely on fine-tuning language models with limited datasets, which is resource-intensive and struggles to generalize across contexts. Recent approaches using large language models (LLMs) have focused on scoring without extensive fine-tuning. However, they often rely heavily on prompt engineering and either fail to generate elaborated feedback or do not adequately evaluate it. In this paper, we propose a modular retrieval augmented generation based ASAS-F system that scores answers and generates feedback in strict zero-shot and few-shot learning scenarios. We design our system to be adaptable to various educational tasks without extensive prompt engineering using an automatic prompt generation framework. Results show an improvement in scoring accuracy by 9\% on unseen questions compared to fine-tuning, offering a scalable and cost-effective solution.

[Arxiv](https://arxiv.org/abs/2409.20042)