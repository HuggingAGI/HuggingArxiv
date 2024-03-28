# 在SemEval-2024年第九项任务中，MasonTigers团队采用链式思考集合方法破解谜题挑战

发布时间：2024年03月22日

`LLM应用` `人工智能`

> MasonTigers at SemEval-2024 Task 9: Solving Puzzles with an Ensemble of Chain-of-Thoughts

# 摘要

> 本文介绍的是我们 MasonTigers 团队参加 SemEval-2024 第9任务的提交内容，该任务提供了用于检验自然语言理解能力的谜题数据集。我们运用大型语言模型（LLMs）并结合多种提示策略来解决这些谜题。相较于开源模型，我们的实验显示，在专有的LLMs上应用零样本和小样本提示可以得出相当不错的解答效果。而采用“链式思考”提示这一逐步拆解推理过程的迭代方法，我们得以进一步提升解答质量。最终，通过集成链式思考提示，我们在单词谜题子任务中荣获亚军，在句子谜题子任务中位列第13名。经由提示引导的LLMs所展现的出色性能，证明了在提供思维过程分步解析时，它们具备处理复杂推理问题的能力。我们的研究深入探索了如何借助步步解析式的提示手段，充分挖掘并释放大型模型参数中蕴含的丰富知识。

> Our paper presents team MasonTigers submission to the SemEval-2024 Task 9 - which provides a dataset of puzzles for testing natural language understanding. We employ large language models (LLMs) to solve this task through several prompting techniques. Zero-shot and few-shot prompting generate reasonably good results when tested with proprietary LLMs, compared to the open-source models. We obtain further improved results with chain-of-thought prompting, an iterative prompting method that breaks down the reasoning process step-by-step. We obtain our best results by utilizing an ensemble of chain-of-thought prompts, placing 2nd in the word puzzle subtask and 13th in the sentence puzzle subtask. The strong performance of prompted LLMs demonstrates their capability for complex reasoning when provided with a decomposition of the thought process. Our work sheds light on how step-wise explanatory prompts can unlock more of the knowledge encoded in the parameters of large models.

[Arxiv](https://arxiv.org/abs/2403.14982)