# [深入剖析 RAG 中的隐私议题，既揭示其优点也关注存在的隐患。]

发布时间：2024年02月23日

`RAG`

> The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)

> RAG技术通过融合专有和敏感的私有数据，有效增强了语言模型的表现力，而在这一过程中，数据隐私成为了核心关注点。虽然现有研究已充分揭示LLMs存在的隐私风险，但RAG机制可能悄然改变LLM生成过程的本质行为，从而引发一些尚未深入探究的新隐私隐患。本研究运用创新的攻击手段对RAG系统进行了详尽实验，结果显示RAG在保护私有检索数据库方面存在一定的安全隐患。然而，令人意外的是，RAG技术同时也能够减轻LLMs训练数据的泄露程度。综上所述，本文针对检索增强型LLMs的隐私保护提供了全新视角与洞见，既有助于LLMs的发展，也为RAG系统的开发者提供了宝贵参考。相关代码已在GitHub平台（https://github.com/phycholosogy/RAG-privacy）开源。

> Retrieval-augmented generation (RAG) is a powerful technique to facilitate language model with proprietary and private data, where data privacy is a pivotal concern. Whereas extensive research has demonstrated the privacy risks of large language models (LLMs), the RAG technique could potentially reshape the inherent behaviors of LLM generation, posing new privacy issues that are currently under-explored. In this work, we conduct extensive empirical studies with novel attack methods, which demonstrate the vulnerability of RAG systems on leaking the private retrieval database. Despite the new risk brought by RAG on the retrieval data, we further reveal that RAG can mitigate the leakage of the LLMs' training data. Overall, we provide new insights in this paper for privacy protection of retrieval-augmented LLMs, which benefit both LLMs and RAG systems builders. Our code is available at https://github.com/phycholosogy/RAG-privacy.

[Arxiv](https://arxiv.org/abs/2402.16893)