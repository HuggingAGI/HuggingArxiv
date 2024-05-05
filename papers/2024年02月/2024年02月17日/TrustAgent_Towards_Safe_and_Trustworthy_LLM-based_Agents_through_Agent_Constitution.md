# TrustAgent：致力于构建基于大型语言模型的安全可信代理，通过制定代理宪法来实现这一目标。

发布时间：2024年02月17日

`Agent` `人工智能`

> TrustAgent: Towards Safe and Trustworthy LLM-based Agents through Agent Constitution

# 摘要

> 大型语言模型（LLM）驱动的代理因其互动能力而备受瞩目，但其可信性尚未得到充分研究。鉴于这些代理能直接与物理世界交互，其可靠性与安全性尤为关键。本文介绍了一种名为TrustAgent的代理框架，旨在初步探讨如何提升LLM代理的安全性，从而增强其可信度。该框架包含三种策略：预先规划策略，它在规划生成前向模型注入安全知识；规划中策略，它在规划生成时加强安全措施；以及规划后策略，通过事后检查确保安全无虞。实验分析表明，这些方法能有效提升LLM代理的安全性，通过识别和预防潜在风险。文章还深入探讨了安全性与实用性之间的微妙关系，以及模型推理能力与其作为安全代理效能之间的联系。本文强调了在设计和部署LLM代理时，必须将安全意识和可信度纳入考量，这不仅能够提升代理的表现，也确保了它们能够负责任地融入人类环境。相关数据和代码可在 https://github.com/agiresearch/TrustAgent 查看。

> The emergence of LLM-based agents has garnered considerable attention, yet their trustworthiness remains an under-explored area. As agents can directly interact with the physical environment, their reliability and safety is critical. This paper presents an Agent-Constitution-based agent framework, TrustAgent, an initial investigation into improving the safety dimension of trustworthiness in LLM-based agents. This framework consists of threefold strategies: pre-planning strategy which injects safety knowledge to the model prior to plan generation, in-planning strategy which bolsters safety during plan generation, and post-planning strategy which ensures safety by post-planning inspection. Through experimental analysis, we demonstrate how these approaches can effectively elevate an LLM agent's safety by identifying and preventing potential dangers. Furthermore, we explore the intricate relationships between safety and helpfulness, and between the model's reasoning ability and its efficacy as a safe agent. This paper underscores the imperative of integrating safety awareness and trustworthiness into the design and deployment of LLM-based agents, not only to enhance their performance but also to ensure their responsible integration into human-centric environments. Data and code are available at https://github.com/agiresearch/TrustAgent.

[Arxiv](https://arxiv.org/abs/2402.01586)