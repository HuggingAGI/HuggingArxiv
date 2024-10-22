# 大型语言模型是否“说”英语时带有口音？本文探讨如何评估并提升多语言 LLM 的自然表达能力。

发布时间：2024年10月21日

`LLM应用` `语言处理` `人工智能`

> Do Large Language Models Have an English Accent? Evaluating and Improving the Naturalness of Multilingual LLMs

# 摘要

> 当前的 LLM 主要以英语为核心设计，即使少数多语言模型也常带有英语偏见。这导致在非英语语言中，LLM 的输出常显得不自然，词汇和语法都透露出英语的影子。尽管这一问题不容忽视，但多语言 LLM 输出的自然性却鲜少被关注。为此，我们引入了新的自动语料库级别指标，专门评估多语言 LLM 输出的词汇和句法自然性。通过这些新指标，我们在法语和中文的基准测试中评估了最先进的 LLM，发现其输出中英语影响的痕迹明显。为解决这一问题，我们提出了一种简单有效的对齐方法，旨在提升 LLM 在目标语言和领域中的自然性，同时确保其在通用基准上的性能不受影响。我们的研究凸显了为新一代多语言 LLM 开发多语言评估工具和方法的重要性。

> Current Large Language Models (LLMs) are predominantly designed with English as the primary language, and even the few that are multilingual tend to exhibit strong English-centric biases. Much like speakers who might produce awkward expressions when learning a second language, LLMs often generate unnatural outputs in non-English languages, reflecting English-centric patterns in both vocabulary and grammar. Despite the importance of this issue, the naturalness of multilingual LLM outputs has received limited attention. In this paper, we address this gap by introducing novel automatic corpus-level metrics to assess the lexical and syntactic naturalness of LLM outputs in a multilingual context. Using our new metrics, we evaluate state-of-the-art LLMs on a curated benchmark in French and Chinese, revealing a tendency towards English-influenced patterns. To mitigate this issue, we also propose a simple and effective alignment method to improve the naturalness of an LLM in a target language and domain, achieving consistent improvements in naturalness without compromising the performance on general-purpose benchmarks. Our work highlights the importance of developing multilingual metrics, resources and methods for the new wave of multilingual LLMs.

[Arxiv](https://arxiv.org/abs/2410.15956)