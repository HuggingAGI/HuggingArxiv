# 强化多轮对话语言模型，抵御分布式后门触发威胁

发布时间：2024年07月04日

`LLM应用` `网络安全` `人工智能`

> Securing Multi-turn Conversational Language Models Against Distributed Backdoor Triggers

# 摘要

> 尽管多轮对话大型语言模型 (LLM) 的应用广泛，但其安全性研究却相对滞后。LLM 特别容易受到数据中毒后门攻击，这种攻击通过操纵训练数据，使模型对特定触发器产生恶意响应。在多轮对话场景中，后门触发器可能跨越多个话语，增加了攻击的隐蔽性和危害性。本文介绍了一种新颖的分布式后门触发器攻击，这种攻击可以与其他单轮攻击策略灵活结合。实验表明，这种攻击对现有单轮交互防御策略具有鲁棒性，因此我们提出了一种新的多轮对话防御策略，并探索了一种基于对比解码的防御方法，以低计算代价有效缓解后门攻击。

> The security of multi-turn conversational large language models (LLMs) is understudied despite it being one of the most popular LLM utilization. Specifically, LLMs are vulnerable to data poisoning backdoor attacks, where an adversary manipulates the training data to cause the model to output malicious responses to predefined triggers. Specific to the multi-turn dialogue setting, LLMs are at the risk of even more harmful and stealthy backdoor attacks where the backdoor triggers may span across multiple utterances, giving lee-way to context-driven attacks. In this paper, we explore a novel distributed backdoor trigger attack that serves to be an extra tool in an adversary's toolbox that can interface with other single-turn attack strategies in a plug and play manner. Results on two representative defense mechanisms indicate that distributed backdoor triggers are robust against existing defense strategies which are designed for single-turn user-model interactions, motivating us to propose a new defense strategy for the multi-turn dialogue setting that is more challenging. To this end, we also explore a novel contrastive decoding based defense that is able to mitigate the backdoor with a low computational tradeoff.

![强化多轮对话语言模型，抵御分布式后门触发威胁](../../../paper_images/2407.04151/poison.jpg)

![强化多轮对话语言模型，抵御分布式后门触发威胁](../../../paper_images/2407.04151/x1.png)

[Arxiv](https://arxiv.org/abs/2407.04151)