# 针对大型语言模型增强生成的提示注入攻击，我们设计了后门检索器，以应对这一挑战。

发布时间：2024年10月18日

`RAG` `网络安全` `信息检索`

> Backdoored Retrievers for Prompt Injection Attacks on Retrieval Augmented Generation of Large Language Models

# 摘要

> LLM 在生成连贯文本方面表现出色，但其静态训练数据限制了其潜力。RAG 通过结合最新信息检索解决了这一问题，但也增加了系统风险。本文探讨了针对 RAG 的提示注入攻击，涉及插入有害链接、推广非法服务等恶意行为。我们提出了一种新型后门攻击，针对密集检索器的微调过程。实验显示，少量受损文档即可显著提高攻击成功率，而后门攻击虽更高效，但设置更为复杂。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in generating coherent text but remain limited by the static nature of their training data. Retrieval Augmented Generation (RAG) addresses this issue by combining LLMs with up-to-date information retrieval, but also expand the attack surface of the system. This paper investigates prompt injection attacks on RAG, focusing on malicious objectives beyond misinformation, such as inserting harmful links, promoting unauthorized services, and initiating denial-of-service behaviors. We build upon existing corpus poisoning techniques and propose a novel backdoor attack aimed at the fine-tuning process of the dense retriever component. Our experiments reveal that corpus poisoning can achieve significant attack success rates through the injection of a small number of compromised documents into the retriever corpus. In contrast, backdoor attacks demonstrate even higher success rates but necessitate a more complex setup, as the victim must fine-tune the retriever using the attacker poisoned dataset.

[Arxiv](https://arxiv.org/abs/2410.14479)