# Rag and Roll：探索基于 LLM 应用框架中，间接提示操作的全面评估之旅

发布时间：2024年08月09日

`RAG` `网络安全` `信息检索`

> Rag and Roll: An End-to-End Evaluation of Indirect Prompt Manipulations in LLM-based Application Frameworks

# 摘要

> RAG技术通过收集、索引、检索和提供信息，为模型赋予了分布外知识。尽管因其灵活性和低成本而日益流行，但其安全问题却鲜有研究。本文探讨了RAG系统面对端到端间接提示操纵的脆弱性。我们首先分析了现有RAG框架，识别出关键配置参数，并回顾了攻击者可能利用的技术。通过实施Rag n Roll框架，我们评估了攻击效果，发现尽管攻击者能提升恶意文档排名，但成功率仅约40%，若将模糊答案视为成功，则可达60%。使用未优化文档的攻击者，通过部署多个文档，也能达到类似效果。此外，调整RAG配置虽能略微阻碍攻击，但最有效的组合却严重影响了系统功能。

> Retrieval Augmented Generation (RAG) is a technique commonly used to equip models with out of distribution knowledge. This process involves collecting, indexing, retrieving, and providing information to an LLM for generating responses. Despite its growing popularity due to its flexibility and low cost, the security implications of RAG have not been extensively studied. The data for such systems are often collected from public sources, providing an attacker a gateway for indirect prompt injections to manipulate the responses of the model. In this paper, we investigate the security of RAG systems against end-to-end indirect prompt manipulations. First, we review existing RAG framework pipelines deriving a prototypical architecture and identifying potentially critical configuration parameters. We then examine prior works searching for techniques that attackers can use to perform indirect prompt manipulations. Finally, implemented Rag n Roll, a framework to determine the effectiveness of attacks against end-to-end RAG applications. Our results show that existing attacks are mostly optimized to boost the ranking of malicious documents during the retrieval phase. However, a higher rank does not immediately translate into a reliable attack. Most attacks, against various configurations, settle around a 40% success rate, which could rise to 60% when considering ambiguous answers as successful attacks (those that include the expected benign one as well). Additionally, when using unoptimized documents, attackers deploying two of them (or more) for a target query can achieve similar results as those using optimized ones. Finally, exploration of the configuration space of a RAG showed limited impact in thwarting the attacks, where the most successful combination severely undermines functionality.

[Arxiv](https://arxiv.org/abs/2408.05025)