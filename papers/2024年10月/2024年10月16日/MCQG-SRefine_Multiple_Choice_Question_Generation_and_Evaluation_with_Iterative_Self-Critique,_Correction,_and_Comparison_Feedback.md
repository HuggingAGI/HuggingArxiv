# MCQG-SRefine：多选题生成与评估，结合迭代自我批评、修正与比较反馈

发布时间：2024年10月16日

`LLM应用`

> MCQG-SRefine: Multiple Choice Question Generation and Evaluation with Iterative Self-Critique, Correction, and Comparison Feedback

# 摘要

> 自动问题生成 (QG) 在 AI 和 NLP 领域尤为重要，特别是在智能辅导、对话系统和事实验证中。然而，为专业考试如美国医学执照考试 (USMLE) 生成多项选择题 (MCQG) 极具挑战，需要深厚的领域知识和复杂的多跳推理。当前的 LLM 如 GPT-4 在这方面表现不佳，主要因为知识过时、幻觉问题和提示敏感性，导致问题质量不尽人意。为此，我们提出了 MCQG-SRefine，一个基于 LLM 自我精炼的框架，通过专家提示工程与迭代自我批评和纠正，显著提升问题质量和难度，满足专家需求。此外，我们创新性地引入了 LLM 作为评估工具，取代传统复杂且昂贵的专家评估，确保评估的可靠性与专家一致性。

> Automatic question generation (QG) is essential for AI and NLP, particularly in intelligent tutoring, dialogue systems, and fact verification. Generating multiple-choice questions (MCQG) for professional exams, like the United States Medical Licensing Examination (USMLE), is particularly challenging, requiring domain expertise and complex multi-hop reasoning for high-quality questions. However, current large language models (LLMs) like GPT-4 struggle with professional MCQG due to outdated knowledge, hallucination issues, and prompt sensitivity, resulting in unsatisfactory quality and difficulty. To address these challenges, we propose MCQG-SRefine, an LLM self-refine-based (Critique and Correction) framework for converting medical cases into high-quality USMLE-style questions. By integrating expert-driven prompt engineering with iterative self-critique and self-correction feedback, MCQG-SRefine significantly enhances human expert satisfaction regarding both the quality and difficulty of the questions. Furthermore, we introduce an LLM-as-Judge-based automatic metric to replace the complex and costly expert evaluation process, ensuring reliable and expert-aligned assessments.

[Arxiv](https://arxiv.org/abs/2410.13191)