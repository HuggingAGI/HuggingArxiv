# DAWN：于全球网络里设计分布式代理

发布时间：2024年11月18日

`Agent` `代理应用`

> DAWN: Designing Distributed Agents in a Worldwide Network

# 摘要

> 大型语言模型（LLMs）发展迅猛，已从单纯的对话工具进化为能进行复杂推理和决策的高级实体。这一进步催生了专为各类任务（如编码和网页浏览）设计的基于LLM的专用代理。随着这些代理能力的增强，对一个强大框架的需求愈发迫切，该框架要能促进它们为实现高级目标进行全球通信与协作。全球网络中的分布式代理（DAWN）通过提供一个将基于LLM的代理与传统软件系统相融合的通用框架，满足了这一需求，从而能够创建适用于多种用例的代理应用程序。DAWN让全球的分布式代理能通过网关代理进行注册并易于被发现。这些代理之间的协作由配备推理策略的主代理来协调。DAWN提供三种操作模式：用于确定性任务的无LLM模式、用于增强决策的副驾驶模式以及用于自主操作的LLM代理模式。此外，DAWN通过专门的安全、安保和合规层保障全球代理协作的安全，抵御攻击者，遵循严格的安全和合规标准。这些特性使DAWN成为在各行业部署基于代理的应用程序的强大网络。

> The rapid evolution of Large Language Models (LLMs) has transformed them from basic conversational tools into sophisticated entities capable of complex reasoning and decision-making. These advancements have led to the development of specialized LLM-based agents designed for diverse tasks such as coding and web browsing. As these agents become more capable, the need for a robust framework that facilitates global communication and collaboration among them towards advanced objectives has become increasingly critical. Distributed Agents in a Worldwide Network (DAWN) addresses this need by offering a versatile framework that integrates LLM-based agents with traditional software systems, enabling the creation of agentic applications suited for a wide range of use cases. DAWN enables distributed agents worldwide to register and be easily discovered through Gateway Agents. Collaborations among these agents are coordinated by a Principal Agent equipped with reasoning strategies. DAWN offers three operational modes: No-LLM Mode for deterministic tasks, Copilot for augmented decision-making, and LLM Agent for autonomous operations. Additionally, DAWN ensures the safety and security of agent collaborations globally through a dedicated safety, security, and compliance layer, protecting the network against attackers and adhering to stringent security and compliance standards. These features make DAWN a robust network for deploying agent-based applications across various industries.

[Arxiv](https://arxiv.org/abs/2410.22339)