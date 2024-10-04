# 基于 LLM 的自动评分框架，实现了人类级别的指导优化。

发布时间：2024年10月02日

`Agent`

> A LLM-Powered Automatic Grading Framework with Human-Level Guidelines Optimization

# 摘要

> 开放式简答题 (SAGs) 在学习分析 (LA) 中被视为深入了解学习者回答的有效工具，但高评分工作量和不一致评分问题使其在实践中面临挑战。随着自然语言处理 (NLP) 的进步，自动简答题评分 (ASAG) 成为解决这些问题的希望。然而，现有 ASAG 算法通用性有限，常需定制。本文提出 GradeOpt，一个基于多代理的 ASAG 框架，利用大型语言模型 (LLMs) 进行评分，并引入反思者和改进者两个代理，通过自我反思优化评分指南。实验表明，GradeOpt 在评分准确性和与人类评分者的一致性方面优于基线。消融研究进一步证实了其各组件的有效性。

> Open-ended short-answer questions (SAGs) have been widely recognized as a powerful tool for providing deeper insights into learners' responses in the context of learning analytics (LA). However, SAGs often present challenges in practice due to the high grading workload and concerns about inconsistent assessments. With recent advancements in natural language processing (NLP), automatic short-answer grading (ASAG) offers a promising solution to these challenges. Despite this, current ASAG algorithms are often limited in generalizability and tend to be tailored to specific questions. In this paper, we propose a unified multi-agent ASAG framework, GradeOpt, which leverages large language models (LLMs) as graders for SAGs. More importantly, GradeOpt incorporates two additional LLM-based agents - the reflector and the refiner - into the multi-agent system. This enables GradeOpt to automatically optimize the original grading guidelines by performing self-reflection on its errors. Through experiments on a challenging ASAG task, namely the grading of pedagogical content knowledge (PCK) and content knowledge (CK) questions, GradeOpt demonstrates superior performance in grading accuracy and behavior alignment with human graders compared to representative baselines. Finally, comprehensive ablation studies confirm the effectiveness of the individual components designed in GradeOpt.

[Arxiv](https://arxiv.org/abs/2410.02165)