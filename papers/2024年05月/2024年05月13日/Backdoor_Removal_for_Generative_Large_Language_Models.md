# 清除生成式大型语言模型的后门隐患

发布时间：2024年05月13日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的安全性问题，特别是后门攻击的问题，并提出了一种新的方法SANDE来清除这些模型中的后门映射。论文关注的是LLMs的理论层面，即如何从技术上解决模型中存在的安全漏洞，而不是讨论LLMs的具体应用场景或Agent的设计。因此，它属于LLM理论分类。` `网络安全`

> Backdoor Removal for Generative Large Language Models

# 摘要

> 生成式大型语言模型（LLMs）在NLP领域迅速崛起，从理解到推理无所不包。然而，随着模型训练数据的无限扩张和互联网的普及，这些模型的内在弱点也日益凸显。恶意攻击者可能散布有毒数据，对预训练的LLMs进行后门植入，使其在常规查询中看似无害，一旦触发后门则产生有害输出。尽管安全训练策略不断进步，如监督微调（SFT）和人类反馈强化学习（RLHF），但一旦模型被后门化，这些策略便束手无策。本文提出了一种名为SANDE的新方法，旨在清除LLMs中的后门映射。我们首先引入了Overwrite Supervised Fine-tuning（OSFT），这是一种在已知触发器情况下有效去除后门的技术。随后，我们将OSFT融入SANDE的两阶段框架，以应对未知触发器的情况。与以往专注于后门识别的研究不同，我们的安全增强型LLMs即使在后门触发时也能保持正常运作。通过广泛的实验验证，SANDE在抵御后门攻击方面表现出色，同时对LLMs的性能影响微乎其微，且无需依赖未被后门化的模型。我们承诺将公开可复现的代码。

> With rapid advances, generative large language models (LLMs) dominate various Natural Language Processing (NLP) tasks from understanding to reasoning. Yet, language models' inherent vulnerabilities may be exacerbated due to increased accessibility and unrestricted model training on massive textual data from the Internet. A malicious adversary may publish poisoned data online and conduct backdoor attacks on the victim LLMs pre-trained on the poisoned data. Backdoored LLMs behave innocuously for normal queries and generate harmful responses when the backdoor trigger is activated. Despite significant efforts paid to LLMs' safety issues, LLMs are still struggling against backdoor attacks. As Anthropic recently revealed, existing safety training strategies, including supervised fine-tuning (SFT) and Reinforcement Learning from Human Feedback (RLHF), fail to revoke the backdoors once the LLM is backdoored during the pre-training stage. In this paper, we present Simulate and Eliminate (SANDE) to erase the undesired backdoored mappings for generative LLMs. We initially propose Overwrite Supervised Fine-tuning (OSFT) for effective backdoor removal when the trigger is known. Then, to handle the scenarios where the trigger patterns are unknown, we integrate OSFT into our two-stage framework, SANDE. Unlike previous works that center on the identification of backdoors, our safety-enhanced LLMs are able to behave normally even when the exact triggers are activated. We conduct comprehensive experiments to show that our proposed SANDE is effective against backdoor attacks while bringing minimal harm to LLMs' powerful capability without any additional access to unbackdoored clean models. We will release the reproducible code.

[Arxiv](https://arxiv.org/abs/2405.07667)