# 记录于眼，非回响于耳：基于上下文的 ASR 转录口语转书面语转换

发布时间：2024年08月18日

`LLM应用` `语音识别`

> Recording for Eyes, Not Echoing to Ears: Contextualized Spoken-to-Written Conversion of ASR Transcripts

# 摘要

> 自动语音识别（ASR）转录本因识别错误和口语现象（如不流畅、语法错误和不完整句子）而可读性差。为此，我们提出上下文相关的口语到书面语转换（CoS2W）任务，旨在纠正ASR和语法错误，并利用上下文和辅助信息将非正式文本转换为正式风格，同时保留内容。这一任务与大型语言模型（LLM）的上下文学习能力相契合。我们构建了SWAB数据集，用于全面比较不同LLM。通过SWAB，我们探讨了不同粒度对CoS2W性能的影响，并提出利用上下文和辅助信息提升输出的方法。实验表明，LLM在CoS2W任务中表现优异，特别是在语法和正式性方面。我们的方法有效利用LLM理解上下文和辅助信息。此外，我们发现LLM评估者在忠实度和正式性的评估上与人类评估高度一致，证实了LLM评估者在CoS2W任务中的可靠性。

> Automatic Speech Recognition (ASR) transcripts exhibit recognition errors and various spoken language phenomena such as disfluencies, ungrammatical sentences, and incomplete sentences, hence suffering from poor readability. To improve readability, we propose a Contextualized Spoken-to-Written conversion (CoS2W) task to address ASR and grammar errors and also transfer the informal text into the formal style with content preserved, utilizing contexts and auxiliary information. This task naturally matches the in-context learning capabilities of Large Language Models (LLMs). To facilitate comprehensive comparisons of various LLMs, we construct a document-level Spoken-to-Written conversion of ASR Transcripts Benchmark (SWAB) dataset. Using SWAB, we study the impact of different granularity levels on the CoS2W performance, and propose methods to exploit contexts and auxiliary information to enhance the outputs. Experimental results reveal that LLMs have the potential to excel in the CoS2W task, particularly in grammaticality and formality, our methods achieve effective understanding of contexts and auxiliary information by LLMs. We further investigate the effectiveness of using LLMs as evaluators and find that LLM evaluators show strong correlations with human evaluations on rankings of faithfulness and formality, which validates the reliability of LLM evaluators for the CoS2W task.

[Arxiv](https://arxiv.org/abs/2408.09688)