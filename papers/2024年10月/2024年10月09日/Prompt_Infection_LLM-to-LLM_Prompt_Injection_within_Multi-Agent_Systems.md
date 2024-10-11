# 提示感染：多代理系统中 LLM 间的提示注入

发布时间：2024年10月09日

`Agent` `人工智能` `网络安全`

> Prompt Infection: LLM-to-LLM Prompt Injection within Multi-Agent Systems

# 摘要

> 随着 LLM 的强大，多代理系统在 AI 应用中日益普遍。然而，安全研究多聚焦于单一代理的漏洞，如提示注入攻击。本文揭示了更危险的 LLM 间提示注入，提出“提示感染”新攻击，类似计算机病毒在代理间自我复制，威胁数据盗窃、诈骗等。实验显示，多代理系统极易受攻击，即使通信不公开。为此，我们提出 LLM 标记防御机制，显著减轻感染传播。随着多代理 LLM 系统的普及，先进安全措施刻不容缓。

> As Large Language Models (LLMs) grow increasingly powerful, multi-agent systems are becoming more prevalent in modern AI applications. Most safety research, however, has focused on vulnerabilities in single-agent LLMs. These include prompt injection attacks, where malicious prompts embedded in external content trick the LLM into executing unintended or harmful actions, compromising the victim's application. In this paper, we reveal a more dangerous vector: LLM-to-LLM prompt injection within multi-agent systems. We introduce Prompt Infection, a novel attack where malicious prompts self-replicate across interconnected agents, behaving much like a computer virus. This attack poses severe threats, including data theft, scams, misinformation, and system-wide disruption, all while propagating silently through the system. Our extensive experiments demonstrate that multi-agent systems are highly susceptible, even when agents do not publicly share all communications. To address this, we propose LLM Tagging, a defense mechanism that, when combined with existing safeguards, significantly mitigates infection spread. This work underscores the urgent need for advanced security measures as multi-agent LLM systems become more widely adopted.

[Arxiv](https://arxiv.org/abs/2410.07283)