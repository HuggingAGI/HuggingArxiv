# Align-SLM：通过来自人工智能反馈的强化学习的无文本口语语言模型

发布时间：2024年11月04日

`LLM应用` `语音处理`

> Align-SLM: Textless Spoken Language Models with Reinforcement Learning from AI Feedback

# 摘要

> 虽然无文本的口语语言模型（SLM）在端到端语音到语音建模方面显示出了潜力，但在语义连贯性和相关性方面仍落后于基于文本的大型语言模型（LLM）。这项工作引入了 Align-SLM 框架，该框架利用了受人工智能反馈强化学习（RLAIF）启发的偏好优化来增强 SLM 的语义理解。我们的方法从给定的提示生成多个语音延续，并使用语义指标为直接偏好优化（DPO）创建偏好数据。我们使用 ZeroSpeech 2021 基准进行词汇和句法建模、用于语义连贯性的 StoryCloze 数据集的口语版本以及其他语音生成指标（包括 GPT4-o 分数和人工评估）来评估该框架。实验结果表明，我们的方法在大多数基准上为 SLM 实现了最先进的性能，突出了偏好优化对于改善 SLM 语义的重要性。

> While textless Spoken Language Models (SLMs) have shown potential in end-to-end speech-to-speech modeling, they still lag behind text-based Large Language Models (LLMs) in terms of semantic coherence and relevance. This work introduces the Align-SLM framework, which leverages preference optimization inspired by Reinforcement Learning with AI Feedback (RLAIF) to enhance the semantic understanding of SLMs. Our approach generates multiple speech continuations from a given prompt and uses semantic metrics to create preference data for Direct Preference Optimization (DPO). We evaluate the framework using ZeroSpeech 2021 benchmarks for lexical and syntactic modeling, the spoken version of the StoryCloze dataset for semantic coherence, and other speech generation metrics, including the GPT4-o score and human evaluation. Experimental results show that our method achieves state-of-the-art performance for SLMs on most benchmarks, highlighting the importance of preference optimization to improve the semantics of SLMs.

[Arxiv](https://arxiv.org/abs/2411.01834)