# 应对大型语言模型中的后门威胁：进展与挑战并存

发布时间：2024年09月30日

`LLM理论` `网络安全` `人工智能`

> Mitigating Backdoor Threats to Large Language Models: Advancement and Challenges

# 摘要

> 随着大型语言模型（LLM）的发展，其在网络搜索、医疗保健和软件开发等领域的应用日益广泛。然而，随着模型规模的扩大，网络安全风险也随之增加，尤其是后门攻击。攻击者利用 LLM 的强大记忆能力，通过操控少量训练数据，即可植入后门，导致下游应用在触发器激活时表现出恶意行为。此外，依赖众包数据和人类反馈的新兴学习范式，如指令调优和 RLHF，进一步加剧了这些风险。本文全面探讨了 LLM 在开发和推理过程中面临的后门威胁，并介绍了最新的防御和检测策略。同时，我们也指出了应对这些威胁的关键挑战，为未来的研究指明了方向。

> The advancement of Large Language Models (LLMs) has significantly impacted various domains, including Web search, healthcare, and software development. However, as these models scale, they become more vulnerable to cybersecurity risks, particularly backdoor attacks. By exploiting the potent memorization capacity of LLMs, adversaries can easily inject backdoors into LLMs by manipulating a small portion of training data, leading to malicious behaviors in downstream applications whenever the hidden backdoor is activated by the pre-defined triggers. Moreover, emerging learning paradigms like instruction tuning and reinforcement learning from human feedback (RLHF) exacerbate these risks as they rely heavily on crowdsourced data and human feedback, which are not fully controlled. In this paper, we present a comprehensive survey of emerging backdoor threats to LLMs that appear during LLM development or inference, and cover recent advancement in both defense and detection strategies for mitigating backdoor threats to LLMs. We also outline key challenges in addressing these threats, highlighting areas for future research.

[Arxiv](https://arxiv.org/abs/2409.19993)