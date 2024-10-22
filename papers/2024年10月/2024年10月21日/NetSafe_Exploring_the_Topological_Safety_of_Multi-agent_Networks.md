# NetSafe：探究多智能体网络的拓扑安全特性

发布时间：2024年10月21日

`Agent` `网络安全` `人工智能`

> NetSafe: Exploring the Topological Safety of Multi-agent Networks

# 摘要

> 大型语言模型 (LLM) 赋予了多智能体网络智能，广泛应用于学术和工业领域。然而，防止这些网络生成恶意信息仍是一个未解之谜。本文从拓扑角度探讨多智能体网络的安全性，提出 NetSafe 框架和 RelCom 交互，统一现有 LLM 智能体框架，奠定广义拓扑安全研究基础。我们发现，高度连接的网络易受攻击，星形图拓扑任务性能下降 29.7%。静态指标比传统图论指标更贴近现实动态评估，显示与攻击者距离更大的网络更安全。我们的研究为 LLM 多智能体网络安全提供了新视角，揭示了多个未报告现象，为未来研究铺平了道路。

> Large language models (LLMs) have empowered nodes within multi-agent networks with intelligence, showing growing applications in both academia and industry. However, how to prevent these networks from generating malicious information remains unexplored with previous research on single LLM's safety be challenging to transfer. In this paper, we focus on the safety of multi-agent networks from a topological perspective, investigating which topological properties contribute to safer networks. To this end, we propose a general framework, NetSafe along with an iterative RelCom interaction to unify existing diverse LLM-based agent frameworks, laying the foundation for generalized topological safety research. We identify several critical phenomena when multi-agent networks are exposed to attacks involving misinformation, bias, and harmful information, termed as Agent Hallucination and Aggregation Safety. Furthermore, we find that highly connected networks are more susceptible to the spread of adversarial attacks, with task performance in a Star Graph Topology decreasing by 29.7%. Besides, our proposed static metrics aligned more closely with real-world dynamic evaluations than traditional graph-theoretic metrics, indicating that networks with greater average distances from attackers exhibit enhanced safety. In conclusion, our work introduces a new topological perspective on the safety of LLM-based multi-agent networks and discovers several unreported phenomena, paving the way for future research to explore the safety of such networks.

[Arxiv](https://arxiv.org/abs/2410.15686)