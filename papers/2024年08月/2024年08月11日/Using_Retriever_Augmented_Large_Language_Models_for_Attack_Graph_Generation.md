# 利用增强检索功能的大型语言模型生成攻击图

发布时间：2024年08月11日

`LLM应用` `网络安全` `人工智能`

> Using Retriever Augmented Large Language Models for Attack Graph Generation

# 摘要

> 随着系统复杂性日益增加，评估其安全性的重要性也随之提升。攻击图作为网络安全专家的重要工具，能全面展示系统内潜在的攻击路径。传统方法依赖专家知识与手动操作，难以覆盖不断变化的威胁全貌。本文探索了利用大型语言模型（如ChatGPT）自动生成攻击图的新途径，通过智能链接漏洞信息（CVEs），并展示了如何从威胁报告中构建攻击图。

> As the complexity of modern systems increases, so does the importance of assessing their security posture through effective vulnerability management and threat modeling techniques. One powerful tool in the arsenal of cybersecurity professionals is the attack graph, a representation of all potential attack paths within a system that an adversary might exploit to achieve a certain objective. Traditional methods of generating attack graphs involve expert knowledge, manual curation, and computational algorithms that might not cover the entire threat landscape due to the ever-evolving nature of vulnerabilities and exploits. This paper explores the approach of leveraging large language models (LLMs), such as ChatGPT, to automate the generation of attack graphs by intelligently chaining Common Vulnerabilities and Exposures (CVEs) based on their preconditions and effects. It also shows how to utilize LLMs to create attack graphs from threat reports.

[Arxiv](https://arxiv.org/abs/2408.05855)