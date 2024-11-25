# 通用且与上下文无关的触发器，用于对 LLM 输出进行精确控制

发布时间：2024年11月22日

`LLM应用` `人工智能` `网络安全`

> Universal and Context-Independent Triggers for Precise Control of LLM Outputs

# 摘要

> 大型语言模型（LLMs）已广泛应用于自动内容生成乃至关键决策系统等领域。不过，提示注入的风险可能导致 LLM 输出被操控。虽然已记录了众多攻击方法，但要完全掌控这些输出仍困难重重，往往需要经验丰富的攻击者多次尝试，且极大依赖提示上下文。基于梯度的白盒攻击技术的最新进展在越狱和系统提示泄漏等任务中展现出良好前景。我们的研究对基于梯度的攻击加以概括，旨在找到这样一个触发因素：（1）通用性：无论目标输出怎样都有效；（2）与上下文无关：在各种提示上下文中都很稳健；（3）精确输出：能够操控 LLM 输入，高精度生成任何指定输出。我们提出了一种新颖的方法来高效发现此类触发因素，并评估所提攻击的有效性。此外，我们探讨了此类攻击对基于 LLM 的应用构成的重大威胁，突出了对手接管 AI 代理所做决策和行动的潜在可能。

> Large language models (LLMs) have been widely adopted in applications such as automated content generation and even critical decision-making systems. However, the risk of prompt injection allows for potential manipulation of LLM outputs. While numerous attack methods have been documented, achieving full control over these outputs remains challenging, often requiring experienced attackers to make multiple attempts and depending heavily on the prompt context. Recent advancements in gradient-based white-box attack techniques have shown promise in tasks like jailbreaks and system prompt leaks. Our research generalizes gradient-based attacks to find a trigger that is (1) Universal: effective irrespective of the target output; (2) Context-Independent: robust across diverse prompt contexts; and (3) Precise Output: capable of manipulating LLM inputs to yield any specified output with high accuracy. We propose a novel method to efficiently discover such triggers and assess the effectiveness of the proposed attack. Furthermore, we discuss the substantial threats posed by such attacks to LLM-based applications, highlighting the potential for adversaries to taking over the decisions and actions made by AI agents.

[Arxiv](https://arxiv.org/abs/2411.14738)