# IBGP：探讨通信多代理系统中零-shot 鲁棒性的非完美拜占庭将军问题

发布时间：2024年10月21日

`Agent` `物联网` `网络安全`

> IBGP: Imperfect Byzantine Generals Problem for Zero-Shot Robustness in Communicative Multi-Agent Systems

# 摘要

> 随着 LLM 代理深入融入我们的基础设施，它们之间的协调与消息同步变得至关重要。拜占庭将军问题 (BGP) 是构建抗攻击多代理系统 (MAS) 的关键模型，描述了系统中存在未知身份恶意代理的场景，这可能是 LLM 代理的幻觉或外部攻击所致。BGP 的目标是达成行动共识。传统 BGP 要求全球共识，但在实际应用中，这并不总是必要且可能低效。因此，我们迫切需要探索与 MAS 局部协调模式相符的改进版 BGP，即不完美 BGP (IBGP)。为此，我们提出一个框架，利用共识协议在 MAS 中提供抗通信攻击的弹性及环境适应性，并通过案例研究展示了其在传感器网络中的实际应用。

> As large language model (LLM) agents increasingly integrate into our infrastructure, their robust coordination and message synchronization become vital. The Byzantine Generals Problem (BGP) is a critical model for constructing resilient multi-agent systems (MAS) under adversarial attacks. It describes a scenario where malicious agents with unknown identities exist in the system-situations that, in our context, could result from LLM agents' hallucinations or external attacks. In BGP, the objective of the entire system is to reach a consensus on the action to be taken. Traditional BGP requires global consensus among all agents; however, in practical scenarios, global consensus is not always necessary and can even be inefficient. Therefore, there is a pressing need to explore a refined version of BGP that aligns with the local coordination patterns observed in MAS. We refer to this refined version as Imperfect BGP (IBGP) in our research, aiming to address this discrepancy. To tackle this issue, we propose a framework that leverages consensus protocols within general MAS settings, providing provable resilience against communication attacks and adaptability to changing environments, as validated by empirical results. Additionally, we present a case study in a sensor network environment to illustrate the practical application of our protocol.

[Arxiv](https://arxiv.org/abs/2410.16237)