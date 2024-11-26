# LLMPirate：针对黑箱硬件 IP 盗版的大型语言模型

发布时间：2024年11月25日

`LLM应用` `软件开发` `硬件设计`

> LLMPirate: LLMs for Black-box Hardware IP Piracy

# 摘要

> 大型语言模型（LLMs）的迅猛发展，让近乎瞬间有效地分析和生成代码成为可能，从而在软件开发中得到广泛应用。在此趋势下，研究人员和企业已着手将LLMs融入硬件设计与验证流程。然而，这些强大的LLMs也可能因硬件开发过程中的安全漏洞引发新的攻击场景，其中尚未被探究的一个攻击方向便是知识产权（IP）盗版。鉴于这种攻击表现为改写硬件设计以躲避盗版检测，全面评估LLM执行此任务的能力以及当前IP盗版检测工具的缓解能力至关重要。

所以，在本项工作中，我们提出了LLMPirate，这是首个基于LLM的技术，能够生成能成功避开多种先进盗版检测工具检测的电路设计盗版变体。我们制定了三项解决方案，以应对LLMs用于硬件电路设计的集成、对大型电路的扩展性以及有效性等相关挑战，形成了端到端的自动化、高效且实用的方案。我们使用八个不同规模和能力的LLM对LLMPirate进行了广泛的实验评估，并针对四个先进且广泛使用的盗版检测工具，评估了其在盗版各类电路设计方面的性能。我们的实验表明，LLMPirate能够在每个检测工具的所有测试电路上始终成功躲避检测。此外，我们通过对IBEX和MOR1KX处理器以及GPS模块的案例研究，展示了LLMPirate的影响，我们成功实现了对它们的盗版。我们期望我们的工作能够激励并推动更出色的IP盗版检测工具的研发。

> The rapid advancement of large language models (LLMs) has enabled the ability to effectively analyze and generate code nearly instantaneously, resulting in their widespread adoption in software development. Following this advancement, researchers and companies have begun integrating LLMs across the hardware design and verification process. However, these highly potent LLMs can also induce new attack scenarios upon security vulnerabilities across the hardware development process. One such attack vector that has not been explored is intellectual property (IP) piracy. Given that this attack can manifest as rewriting hardware designs to evade piracy detection, it is essential to thoroughly evaluate LLM capabilities in performing this task and assess the mitigation abilities of current IP piracy detection tools.
  Therefore, in this work, we propose LLMPirate, the first LLM-based technique able to generate pirated variations of circuit designs that successfully evade detection across multiple state-of-the-art piracy detection tools. We devise three solutions to overcome challenges related to integration of LLMs for hardware circuit designs, scalability to large circuits, and effectiveness, resulting in an end-to-end automated, efficient, and practical formulation. We perform an extensive experimental evaluation of LLMPirate using eight LLMs of varying sizes and capabilities and assess their performance in pirating various circuit designs against four state-of-the-art, widely-used piracy detection tools. Our experiments demonstrate that LLMPirate is able to consistently evade detection on 100% of tested circuits across every detection tool. Additionally, we showcase the ramifications of LLMPirate using case studies on IBEX and MOR1KX processors and a GPS module, that we successfully pirate. We envision that our work motivates and fosters the development of better IP piracy detection tools.

[Arxiv](https://arxiv.org/abs/2411.16111)