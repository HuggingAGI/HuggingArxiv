# Tele-LLMs：专为电信领域量身打造的大型语言模型系列

发布时间：2024年09月08日

`LLM应用`

> Tele-LLMs: A Series of Specialized Large Language Models for Telecommunications

# 摘要

> 大型语言模型 (LLM) 的出现，从自然语言处理到医疗、金融等领域，都产生了深远影响。然而，尽管 LLM 迅速普及，其在电信领域的应用却相对有限，多依赖于缺乏领域专业知识的一般模型。这种专业性的缺失，导致在处理电信特定术语和数学表示时表现不佳。本文通过创建并发布 Tele-Data 和 Tele-Eval 两个数据集，填补了这一空白。Tele-Data 是一个综合的电信材料数据集，而 Tele-Eval 则是专为电信领域设计的大规模问答数据集。通过大量实验，我们探索了将 LLM 适应电信领域的最佳训练方法，从专业知识划分到参数高效技术的应用。我们还研究了不同规模模型在适应过程中的表现，并分析了训练数据对其行为的影响。基于这些研究，我们开发并开源了 Tele-LLMs，这是首批专为电信领域设计的语言模型，参数范围从 1B 到 8B。评估结果显示，Tele-LLMs 在 Tele-Eval 上表现优于一般模型，同时避免了灾难性遗忘现象。

> The emergence of large language models (LLMs) has significantly impacted various fields, from natural language processing to sectors like medicine and finance. However, despite their rapid proliferation, the applications of LLMs in telecommunications remain limited, often relying on general-purpose models that lack domain-specific specialization. This lack of specialization results in underperformance, particularly when dealing with telecommunications-specific technical terminology and their associated mathematical representations. This paper addresses this gap by first creating and disseminating Tele-Data, a comprehensive dataset of telecommunications material curated from relevant sources, and Tele-Eval, a large-scale question-and-answer dataset tailored to the domain. Through extensive experiments, we explore the most effective training techniques for adapting LLMs to the telecommunications domain, ranging from examining the division of expertise across various telecommunications aspects to employing parameter-efficient techniques. We also investigate how models of different sizes behave during adaptation and analyze the impact of their training data on this behavior. Leveraging these findings, we develop and open-source Tele-LLMs, the first series of language models ranging from 1B to 8B parameters, specifically tailored for telecommunications. Our evaluations demonstrate that these models outperform their general-purpose counterparts on Tele-Eval while retaining their previously acquired capabilities, thus avoiding the catastrophic forgetting phenomenon.

[Arxiv](https://arxiv.org/abs/2409.05314)