# 探究大型语言模型如何从嘈杂的语音转录中提炼出语法正确的句子

发布时间：2024年10月07日

`LLM理论` `语音处理`

> Investigating large language models for their competence in extracting grammatically sound sentences from transcribed noisy utterances

# 摘要

> 人类在处理嘈杂语音时，能轻松过滤无关噪音，专注于语义内容。这种能力可能源于习得的语法规则，这些规则帮助构建语音中的抽象句法-语义结构。在我们的研究中，我们探讨了大型语言模型（LLMs）是否能有效执行类似任务。我们发现，尽管LLMs能从嘈杂对话中提取语音，但并非所有提取的语音都结构良好，这表明LLMs在理解和应用句法-语义规则方面仍有不足。与人类相比，LLMs对嘈杂语音的理解仍显浅薄。

> Selectively processing noisy utterances while effectively disregarding speech-specific elements poses no considerable challenge for humans, as they exhibit remarkable cognitive abilities to separate semantically significant content from speech-specific noise (i.e. filled pauses, disfluencies, and restarts). These abilities may be driven by mechanisms based on acquired grammatical rules that compose abstract syntactic-semantic structures within utterances. Segments without syntactic and semantic significance are consistently disregarded in these structures. The structures, in tandem with lexis, likely underpin language comprehension and thus facilitate effective communication. In our study, grounded in linguistically motivated experiments, we investigate whether large language models (LLMs) can effectively perform analogical speech comprehension tasks. In particular, we examine the ability of LLMs to extract well-structured utterances from transcriptions of noisy dialogues. We conduct two evaluation experiments in the Polish language scenario, using a~dataset presumably unfamiliar to LLMs to mitigate the risk of data contamination. Our results show that not all extracted utterances are correctly structured, indicating that either LLMs do not fully acquire syntactic-semantic rules or they acquire them but cannot apply them effectively. We conclude that the ability of LLMs to comprehend noisy utterances is still relatively superficial compared to human proficiency in processing them.

[Arxiv](https://arxiv.org/abs/2410.05099)