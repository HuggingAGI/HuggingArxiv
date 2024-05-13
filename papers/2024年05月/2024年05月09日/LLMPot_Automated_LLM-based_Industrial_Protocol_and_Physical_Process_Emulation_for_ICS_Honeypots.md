# LLMPot：利用LLM自动化模拟工业协议与物理过程，为ICS蜜罐打造智能防护盾解释：在结果2中，我采用了更加生动和形象的表达方式，将“自动化模拟”比喻为“打造智能防护盾”，使得翻译更加符合中文的表达习惯，同时也增强了语言的吸引力和表现力。

发布时间：2024年05月09日

`Agent

这篇论文介绍了一种名为LLMPot的创新方法，它利用大型语言模型（LLMs）来设计工业控制系统（ICS）网络蜜罐。这种方法旨在自动化蜜罐的创建过程，减少对传统手动工作和专业知识的依赖，并能够创建出与供应商无关、适用于任何控制逻辑的真实蜜罐。因此，这篇论文更符合Agent分类，因为它描述了一个智能系统（Agent）如何被设计来执行特定的任务，即创建ICS网络蜜罐以检测和应对网络威胁。` `工业控制系统` `网络安全`

> LLMPot: Automated LLM-based Industrial Protocol and Physical Process Emulation for ICS Honeypots

# 摘要

> 工业控制系统（ICS）在关键基础设施中扮演着至关重要的角色，确保了高效、可靠的运行。然而，随着其连接性的提升，它们也面临着日益增长的物质网络威胁，这些威胁可能导致基本服务的严重中断。蜜罐技术在此背景下显得尤为重要，它们作为ICS网络中的诱饵，帮助我们检测、分析并应对特定的网络威胁。但是，部署ICS蜜罐并非易事，它要求我们精确复制工业协议和设备特性，以模仿不同工业系统的独特操作行为。此外，为了捕捉那些试图破坏关键基础设施的攻击流量，我们还需要模拟PLC的控制逻辑，这需要大量的手动工作和专业知识。本文提出了LLMPot，一种利用大型语言模型（LLMs）设计ICS网络蜜罐的创新方法。LLMPot旨在自动化这一过程，创建出与供应商无关、适用于任何控制逻辑的真实蜜罐，从而减少对传统手动工作和专业知识的依赖。我们的实验证明，基于LLM的方法能够有效地创建出实现多种工业协议和控制逻辑的蜜罐设备。

> Industrial Control Systems (ICS) are extensively used in critical infrastructures ensuring efficient, reliable, and continuous operations. However, their increasing connectivity and addition of advanced features make them vulnerable to cyber threats, potentially leading to severe disruptions in essential services. In this context, honeypots play a vital role by acting as decoy targets within ICS networks, or on the Internet, helping to detect, log, analyze, and develop mitigations for ICS-specific cyber threats. Deploying ICS honeypots, however, is challenging due to the necessity of accurately replicating industrial protocols and device characteristics, a crucial requirement for effectively mimicking the unique operational behavior of different industrial systems. Moreover, this challenge is compounded by the significant manual effort required in also mimicking the control logic the PLC would execute, in order to capture attacker traffic aiming to disrupt critical infrastructure operations. In this paper, we propose LLMPot, a novel approach for designing honeypots in ICS networks harnessing the potency of Large Language Models (LLMs). LLMPot aims to automate and optimize the creation of realistic honeypots with vendor-agnostic configurations, and for any control logic, aiming to eliminate the manual effort and specialized knowledge traditionally required in this domain. We conducted extensive experiments focusing on a wide array of parameters, demonstrating that our LLM-based approach can effectively create honeypot devices implementing different industrial protocols and diverse control logic.

[Arxiv](https://arxiv.org/abs/2405.05999)