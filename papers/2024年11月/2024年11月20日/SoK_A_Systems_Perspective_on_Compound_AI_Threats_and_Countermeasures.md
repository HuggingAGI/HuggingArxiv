# SoK：从系统视角看复合人工智能的威胁与对策

发布时间：2024年11月20日

`LLM应用` `人工智能安全`

> SoK: A Systems Perspective on Compound AI Threats and Countermeasures

# 摘要

> 大型语言模型（LLMs）在企业中的运用往往采用专有模型，且处理的是敏感的输入与数据。先前研究中所明确的众多攻击向量——针对训练和推理所用的各类软件及硬件组件——致使落实保密和完整性政策困难重重。
  当我们朝着构建融合多个大型语言模型（LLMs）的复合人工智能推理管线前行时，攻击面大幅拓展。如今，攻击者聚焦于人工智能算法以及与这些系统相关的软件和硬件组件。虽然当下的研究常常孤立地审视这些要素，但我们发现，结合跨层攻击观察能够实现强大的端到端攻击，且对威胁模型的假设最少。鉴于每一层现存的攻击数量众多，我们需要对每一层的不同攻击向量有一个全面且系统化的认知。
  本 SoK 探讨了适用于复合人工智能系统的不同软件和硬件攻击，并展示了怎样结合多种攻击机制来降低孤立攻击所需的威胁模型假设。接下来，我们依照 Mitre Att&ck 框架将 ML 攻击进行系统化，从而依据威胁模型更好地定位每个攻击。最后，我们概述了软件和硬件层现有的应对措施，并论述了全面防御策略的必要性，以达成复合人工智能系统的安全和高性能部署。

> Large language models (LLMs) used across enterprises often use proprietary models and operate on sensitive inputs and data. The wide range of attack vectors identified in prior research - targeting various software and hardware components used in training and inference - makes it extremely challenging to enforce confidentiality and integrity policies.
  As we advance towards constructing compound AI inference pipelines that integrate multiple large language models (LLMs), the attack surfaces expand significantly. Attackers now focus on the AI algorithms as well as the software and hardware components associated with these systems. While current research often examines these elements in isolation, we find that combining cross-layer attack observations can enable powerful end-to-end attacks with minimal assumptions about the threat model. Given, the sheer number of existing attacks at each layer, we need a holistic and systemized understanding of different attack vectors at each layer.
  This SoK discusses different software and hardware attacks applicable to compound AI systems and demonstrates how combining multiple attack mechanisms can reduce the threat model assumptions required for an isolated attack. Next, we systematize the ML attacks in lines with the Mitre Att&ck framework to better position each attack based on the threat model. Finally, we outline the existing countermeasures for both software and hardware layers and discuss the necessity of a comprehensive defense strategy to enable the secure and high-performance deployment of compound AI systems.

[Arxiv](https://arxiv.org/abs/2411.13459)