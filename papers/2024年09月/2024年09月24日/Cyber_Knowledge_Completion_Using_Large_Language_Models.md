# 利用大型语言模型实现网络知识补全

发布时间：2024年09月24日

`RAG` `网络安全` `物联网`

> Cyber Knowledge Completion Using Large Language Models

# 摘要

> 将物联网 (IoT) 融入网络物理系统 (CPS) 不仅扩大了其网络攻击面，还引入了新的复杂威胁，这些威胁可能利用新兴漏洞。由于网络安全知识的不足和过时，评估 CPS 的风险变得愈发困难，这迫切需要更精准的风险评估和缓解策略。尽管以往的研究依赖于基于规则的自然语言处理 (NLP) 工具来识别漏洞和攻击模式，但大型语言模型 (LLM) 的进步为我们提供了通过增强推理、推断和总结能力来完善网络攻击知识的新机遇。我们采用嵌入模型封装攻击模式和对抗技术信息，并通过向量嵌入生成它们之间的映射。此外，我们提出了一种基于检索增强生成 (RAG) 的方法，利用预训练模型在不同威胁模式分类间建立结构化映射。最后，我们通过一个小型手工标注数据集，将基于 RAG 的方法与标准二元分类模型进行对比。这一综合框架为应对网络攻击知识图谱的完整性挑战提供了有力支持。

> The integration of the Internet of Things (IoT) into Cyber-Physical Systems (CPSs) has expanded their cyber-attack surface, introducing new and sophisticated threats with potential to exploit emerging vulnerabilities. Assessing the risks of CPSs is increasingly difficult due to incomplete and outdated cybersecurity knowledge. This highlights the urgent need for better-informed risk assessments and mitigation strategies. While previous efforts have relied on rule-based natural language processing (NLP) tools to map vulnerabilities, weaknesses, and attack patterns, recent advancements in Large Language Models (LLMs) present a unique opportunity to enhance cyber-attack knowledge completion through improved reasoning, inference, and summarization capabilities. We apply embedding models to encapsulate information on attack patterns and adversarial techniques, generating mappings between them using vector embeddings. Additionally, we propose a Retrieval-Augmented Generation (RAG)-based approach that leverages pre-trained models to create structured mappings between different taxonomies of threat patterns. Further, we use a small hand-labeled dataset to compare the proposed RAG-based approach to a baseline standard binary classification model. Thus, the proposed approach provides a comprehensive framework to address the challenge of cyber-attack knowledge graph completion.

[Arxiv](https://arxiv.org/abs/2409.16176)