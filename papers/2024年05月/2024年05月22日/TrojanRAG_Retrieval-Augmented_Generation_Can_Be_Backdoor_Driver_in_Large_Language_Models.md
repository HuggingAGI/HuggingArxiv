# TrojanRAG：大型语言模型中的检索增强生成可能潜藏后门风险

发布时间：2024年05月22日

`RAG

这篇论文主要讨论了在检索增强生成（RAG）框架中实施的后门攻击，即TrojanRAG。它详细描述了如何在LLMs中植入后门，并利用知识图谱来提高后门攻击的精确度和效果。论文的核心在于探讨和展示了一种新型的后门攻击方法，这种方法针对的是RAG框架，因此属于RAG分类。虽然涉及到了LLMs的应用，但其重点在于RAG框架的安全性问题，而非LLMs的理论研究或一般应用。` `网络安全`

> TrojanRAG: Retrieval-Augmented Generation Can Be Backdoor Driver in Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）在自然语言处理（NLP）领域表现卓越，但其潜在的安全威胁也引起了广泛关注。后门攻击虽证实了LLMs在各阶段造成的损害，但其高昂的成本和脆弱性备受诟病。攻击LLMs不仅风险重重，且成本巨大。随着LLMs的不断迭代，后门的鲁棒性亦随之下降。本文提出的TrojanRAG，巧妙地在检索增强生成中实施联合后门攻击，操控LLMs于各种攻击场景。攻击者精心设计目标上下文与触发集，通过对比学习优化多个后门快捷方式，确保触发条件精准匹配于参数子空间。为提升RAG对目标上下文的识别率，我们借助知识图谱构建结构化数据，实现细粒度的精确匹配。此外，我们标准化了LLMs中的后门场景，从攻击者与用户的双重视角审视后门带来的实际危害，并探讨上下文是否为解锁模型的有效手段。实验结果显示，TrojanRAG在保持正常查询检索能力的同时，展现出广泛的安全威胁。

> Large language models (LLMs) have raised concerns about potential security threats despite performing significantly in Natural Language Processing (NLP). Backdoor attacks initially verified that LLM is doing substantial harm at all stages, but the cost and robustness have been criticized. Attacking LLMs is inherently risky in security review, while prohibitively expensive. Besides, the continuous iteration of LLMs will degrade the robustness of backdoors. In this paper, we propose TrojanRAG, which employs a joint backdoor attack in the Retrieval-Augmented Generation, thereby manipulating LLMs in universal attack scenarios. Specifically, the adversary constructs elaborate target contexts and trigger sets. Multiple pairs of backdoor shortcuts are orthogonally optimized by contrastive learning, thus constraining the triggering conditions to a parameter subspace to improve the matching. To improve the recall of the RAG for the target contexts, we introduce a knowledge graph to construct structured data to achieve hard matching at a fine-grained level. Moreover, we normalize the backdoor scenarios in LLMs to analyze the real harm caused by backdoors from both attackers' and users' perspectives and further verify whether the context is a favorable tool for jailbreaking models. Extensive experimental results on truthfulness, language understanding, and harmfulness show that TrojanRAG exhibits versatility threats while maintaining retrieval capabilities on normal queries.

[Arxiv](https://arxiv.org/abs/2405.13401)