# RAG-Thief：利用基于代理的攻击，从检索增强生成应用中大规模提取私有数据

发布时间：2024年11月21日

`RAG` `隐私保护` `语言模型应用`

> RAG-Thief: Scalable Extraction of Private Data from Retrieval-Augmented Generation Applications with Agent-based Attacks

# 摘要

> 尽管大型语言模型（LLMs）在生成任务方面成绩斐然，但仍存在一些短板，像缺乏最新知识、产生幻觉等。检索增强生成（RAG）整合外部知识库，为LLM性能添彩，提供更多上下文，大幅提升准确性和知识覆盖度。不过，构建这些外部知识库往往需要大量资源，还可能涉及敏感信息。在本文中，我们提出了一种名为RAG-Thief的基于代理的自动隐私攻击手段，它能够从RAG应用所用的私有数据库中提取海量私有数据。我们对RAG应用相关的隐私风险展开了系统研究，发现LLM的脆弱性致使私有知识库面临重大隐私风险。和此前依靠传统提示注入技术的手动攻击不同，RAG-Thief从初始的对抗性查询起步，从模型响应中学习，逐步生成新查询，尽可能多地从知识库中提取数据块。实验结果显示，我们的RAG-Thief能从部署在本地机器和现实平台（包括OpenAI的GPTs和字节跳动的Coze）的定制RAG应用中的私有知识库中提取超70%的信息。我们的发现凸显了当前RAG应用中的隐私漏洞，也强调了迫切需要更有力的防护措施。

> While large language models (LLMs) have achieved notable success in generative tasks, they still face limitations, such as lacking up-to-date knowledge and producing hallucinations. Retrieval-Augmented Generation (RAG) enhances LLM performance by integrating external knowledge bases, providing additional context which significantly improves accuracy and knowledge coverage. However, building these external knowledge bases often requires substantial resources and may involve sensitive information. In this paper, we propose an agent-based automated privacy attack called RAG-Thief, which can extract a scalable amount of private data from the private database used in RAG applications. We conduct a systematic study on the privacy risks associated with RAG applications, revealing that the vulnerability of LLMs makes the private knowledge bases suffer significant privacy risks. Unlike previous manual attacks which rely on traditional prompt injection techniques, RAG-Thief starts with an initial adversarial query and learns from model responses, progressively generating new queries to extract as many chunks from the knowledge base as possible. Experimental results show that our RAG-Thief can extract over 70% information from the private knowledge bases within customized RAG applications deployed on local machines and real-world platforms, including OpenAI's GPTs and ByteDance's Coze. Our findings highlight the privacy vulnerabilities in current RAG applications and underscore the pressing need for stronger safeguards.

[Arxiv](https://arxiv.org/abs/2411.14110)