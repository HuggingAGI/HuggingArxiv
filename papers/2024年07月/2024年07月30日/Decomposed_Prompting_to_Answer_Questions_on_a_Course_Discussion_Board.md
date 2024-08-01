# 通过分解提示法，巧妙解答课程讨论板上的疑问

发布时间：2024年07月30日

`LLM应用` `问答系统`

> Decomposed Prompting to Answer Questions on a Course Discussion Board

# 摘要

> 我们开发并测试了一个问答系统，该系统通过分解提示技术，对课程讨论板上的学生问题进行分类和解答。利用大型语言模型（LLM），我们将问题细分为概念性、作业、后勤和不可回答四类，从而针对不同类型问题采取相应解答策略。借助GPT-3的变体，我们实现了81%的分类准确率。此外，我们还探讨了该系统在处理机器学习课程概念性问题时的表现及存在的不足。

> We propose and evaluate a question-answering system that uses decomposed prompting to classify and answer student questions on a course discussion board. Our system uses a large language model (LLM) to classify questions into one of four types: conceptual, homework, logistics, and not answerable. This enables us to employ a different strategy for answering questions that fall under different types. Using a variant of GPT-3, we achieve $81\%$ classification accuracy. We discuss our system's performance on answering conceptual questions from a machine learning course and various failure modes.

[Arxiv](https://arxiv.org/abs/2407.21170)