# RePD：利用基于检索的提示分解技术，有效抵御越狱攻击。

发布时间：2024年10月11日

`RAG` `网络安全` `人工智能`

> RePD: Defending Jailbreak Attack through a Retrieval-based Prompt Decomposition Process

# 摘要

> 本研究中，我们推出了 RePD，一种创新的基于检索的提示分解框架，旨在防范大型语言模型 (LLM) 的越狱攻击。尽管 LLM 经过严格的伦理对齐训练，仍易受攻击。RePD 通过一次性学习模型，访问预先收集的越狱提示模板数据库，识别并分解用户提示中的有害查询。它将分解后的提示整合到用户原始查询中，形成一次性学习示例，教导 LLM 识别和分离恶意组件。这样，LLM 能在遵循伦理指南处理用户提示前，先中和潜在有害元素。RePD 兼容多种开源 LLM，通过综合实验，我们验证了 RePD 在增强 LLM 抗越狱攻击能力的同时，不影响其响应用户请求的性能。

> In this study, we introduce RePD, an innovative attack Retrieval-based Prompt Decomposition framework designed to mitigate the risk of jailbreak attacks on large language models (LLMs). Despite rigorous pretraining and finetuning focused on ethical alignment, LLMs are still susceptible to jailbreak exploits. RePD operates on a one-shot learning model, wherein it accesses a database of pre-collected jailbreak prompt templates to identify and decompose harmful inquiries embedded within user prompts. This process involves integrating the decomposition of the jailbreak prompt into the user's original query into a one-shot learning example to effectively teach the LLM to discern and separate malicious components. Consequently, the LLM is equipped to first neutralize any potentially harmful elements before addressing the user's prompt in a manner that aligns with its ethical guidelines. RePD is versatile and compatible with a variety of open-source LLMs acting as agents. Through comprehensive experimentation with both harmful and benign prompts, we have demonstrated the efficacy of our proposed RePD in enhancing the resilience of LLMs against jailbreak attacks, without compromising their performance in responding to typical user requests.

[Arxiv](https://arxiv.org/abs/2410.08660)