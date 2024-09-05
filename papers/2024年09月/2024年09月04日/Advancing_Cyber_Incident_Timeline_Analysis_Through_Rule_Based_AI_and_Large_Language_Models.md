# 利用基于规则的AI与大型语言模型，我们正推动网络事件时间线分析的进步。

发布时间：2024年09月04日

`Agent` `数字取证` `网络安全`

> Advancing Cyber Incident Timeline Analysis Through Rule Based AI and Large Language Models

# 摘要

> 时间线分析（TA）是数字取证中时间线取证的核心，专注于从事件日志、文件元数据等提取的时间戳等时间数字文物的检查与分析，以关联网络事件并重建其时间线。传统工具在处理DF调查和事件响应中获取的海量数据时往往力不从心。本文提出的GenDFIR框架，融合基于规则的人工智能与大型语言模型，旨在推进并自动化TA流程。我们的方法分两步走：首先，利用R-BAI依据预设规则识别并筛选异常数字文物；其次，通过RAG代理将选定文物转化为嵌入，供LLM处理，进而实现自动TA及潜在事件场景预测。为验证框架，我们在合成网络事件模拟中评估了GenDFIR的性能、效率及可靠性。研究显示，R-BAI与LLMs的结合在TA领域潜力巨大，不仅彰显了生成AI的力量，更为高级威胁检测与事件重建开辟了新路径，是该领域的一大跃进。

> Timeline Analysis (TA) is a key part of Timeline Forensics (TF) in Digital Forensics (DF), focusing primarily on examining and analysing temporal digital artefacts such as timestamps, derived from event logs, file metadata, and other related data to correlate events resulting from cyber incidents and reconstruct their chronological timeline. Traditional tools often struggle to efficiently process the vast volume and variety of data acquired during DF investigations and Incident Response (IR) processes. This paper presents a novel framework, GenDFIR, that combines Rule-Based Artificial Intelligence (R-BAI) algorithms with Large Language Models (LLMs) to advance and automate the TA process. Our approach consists of two main stages (1) We use R-BAI to identify and select anomalous digital artefacts based on predefined rules. (2) The selected artefacts are then converted into embeddings for processing by an LLM with the help of a Retrieval-Augmented Generation (RAG) agent. The LLM consequently leverages its capabilities to perform automated TA on the artefacts and predict potential incident scenarios. To validate our framework, we evaluate GenDFIR performance, efficiency, and reliability using various metrics across synthetic cyber incident simulation scenarios. This paper presents a proof of concept, where the findings demonstrate the significant potential of integrating R-BAI and LLMs for TA. This novel approach highlights the power of Generative AI (GenAI), specifically LLMs, and opens new avenues for advanced threat detection and incident reconstruction, representing a significant step forward in the field.

[Arxiv](https://arxiv.org/abs/2409.02572)