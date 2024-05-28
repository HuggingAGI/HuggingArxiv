# 利用大型语言模型集合揭秘点击诱饵内容

发布时间：2024年05月25日

`LLM应用

理由：这篇论文介绍了一种使用微调的大型语言模型（LLM）来生成复合剧透的方法，以解决网络空间中点击诱饵帖子的问题。这种方法涉及LLM的具体应用，即通过生成文本内容来抵消点击诱饵的影响，而不是探讨LLM的理论基础或Agent的行为，也不是关于检索和生成（RAG）模型的研究。因此，它属于LLM应用类别。` `社交媒体` `内容安全`

> Generating clickbait spoilers with an ensemble of large language models

# 摘要

> 网络空间中点击诱饵帖子泛滥成灾。生成剧透——即通过提供满足好奇心的信息来抵消点击诱饵的短文本——是解决这一问题的方案之一。目前最先进的方法依赖于段落检索或问答技术，仅能生成短语或段落形式的剧透。本研究提出了一种由微调的大型语言模型组成的集成方法，不仅能生成短语或段落剧透，还能创造涉及文本多个非连续部分的复合剧透。实验结果显示，我们的集成模型在BLEU、METEOR和BERTScore等关键指标上超越了现有技术。

> Clickbait posts are a widespread problem in the webspace. The generation of spoilers, i.e. short texts that neutralize clickbait by providing information that satisfies the curiosity induced by it, is one of the proposed solutions to the problem. Current state-of-the-art methods are based on passage retrieval or question answering approaches and are limited to generating spoilers only in the form of a phrase or a passage. In this work, we propose an ensemble of fine-tuned large language models for clickbait spoiler generation. Our approach is not limited to phrase or passage spoilers, but is also able to generate multipart spoilers that refer to several non-consecutive parts of text. Experimental evaluation demonstrates that the proposed ensemble model outperforms the baselines in terms of BLEU, METEOR and BERTScore metrics.

[Arxiv](https://arxiv.org/abs/2405.16284)