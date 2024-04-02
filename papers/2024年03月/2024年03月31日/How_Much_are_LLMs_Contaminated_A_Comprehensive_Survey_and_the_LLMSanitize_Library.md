# 深度探究大型语言模型的污染问题及LLMSanitize库的全面解决方案

发布时间：2024年03月31日

`LLM应用` `AI融资`

> How Much are LLMs Contaminated? A Comprehensive Survey and the LLMSanitize Library

# 摘要

> 随着大型语言模型（LLMs）近年来的崛起，新的机遇层出不穷，但挑战也随之而来，数据污染问题日益凸显。在商业和AI融资领域，哪怕是在流行问答基准测试中提升微小的百分比，也可能意味着数千万美金的收益，这无疑对模型的稳健性提出了更高要求。与此同时，要追踪LLMs所接触过的数据变得越来越艰难，尤其是对于GPT-4和Claude-3这样的闭源模型，它们对训练数据守口如瓶。由此，数据污染问题变得尤为关键：LLMs的高效表现可能部分源于对旧数据的依赖，这使得它们的性能不再那么值得信赖。这一问题对自然语言处理（NLP）领域的进步构成了威胁。尽管如此，目前对于如何有效应对污染问题，以及如何预防、减轻和界定污染，尚无明确的方法和共识。本文综述了近期关于LLMs污染问题的研究，并推出了一款名为LLMSanitize的开源Python库，该库集成了主要的污染检测算法，帮助社区监测LLMs的污染程度，其GitHub链接为：https://github.com/ntunlp/LLMSanitize。

> With the rise of Large Language Models (LLMs) in recent years, new opportunities are emerging, but also new challenges, and contamination is quickly becoming critical. Business applications and fundraising in AI have reached a scale at which a few percentage points gained on popular question-answering benchmarks could translate into dozens of millions of dollars, placing high pressure on model integrity. At the same time, it is becoming harder and harder to keep track of the data that LLMs have seen; if not impossible with closed-source models like GPT-4 and Claude-3 not divulging any information on the training set. As a result, contamination becomes a critical issue: LLMs' performance may not be reliable anymore, as the high performance may be at least partly due to their previous exposure to the data. This limitation jeopardizes the entire progress in the field of NLP, yet, there remains a lack of methods on how to efficiently address contamination, or a clear consensus on prevention, mitigation and classification of contamination. In this paper, we survey all recent work on contamination with LLMs, and help the community track contamination levels of LLMs by releasing an open-source Python library named LLMSanitize implementing major contamination detection algorithms, which link is: https://github.com/ntunlp/LLMSanitize.

[Arxiv](https://arxiv.org/abs/2404.00699)