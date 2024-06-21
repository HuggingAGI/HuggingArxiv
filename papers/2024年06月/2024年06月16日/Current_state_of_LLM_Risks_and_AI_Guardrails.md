# 大型语言模型（LLM）风险现状与人工智能安全护栏

发布时间：2024年06月16日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在部署中的安全性和可靠性问题，特别关注了能够执行现实世界行动的代理性LLMs。论文中提到的“安全护栏”、“模型对齐技术”、“分层保护模型”以及“检索增强生成（RAG）架构”的应用，都是为了确保这些代理性LLMs的行为符合预期并减少潜在危害。因此，这篇论文更符合Agent分类，因为它主要关注的是如何确保代理性LLMs的安全和可靠。` `人工智能伦理`

> Current state of LLM Risks and AI Guardrails

# 摘要

> 随着大型语言模型（LLMs）的复杂性日益增加，它们在安全性和可靠性至关重要的敏感领域得到了广泛应用。然而，LLMs固有的风险，如偏见、不安全行为的可能性、数据集中毒、缺乏透明度、幻觉和不可重复性，要求我们必须建立“安全护栏”，以确保这些模型行为符合预期并减少潜在危害。本文探讨了LLMs部署中的风险，并评估了当前的护栏实施和模型对齐技术。我们分析了内在和外在偏见评估方法，并强调了在负责任AI开发中公平度量的重要性。特别关注了能够执行现实世界行动的代理性LLMs的安全性和可靠性，强调了测试性、故障安全和情境意识的重要性。文章还介绍了一系列技术策略，包括分层保护模型，以及在系统提示、检索增强生成（RAG）架构中应用的技术，旨在最小化偏见和保护隐私。设计有效的护栏需要深入理解LLM的应用场景、相关法规和伦理考量。在准确性和隐私等需求之间找到平衡点仍是一个挑战。本文强调了持续研究和开发的重要性，以确保LLMs在现实世界应用中的安全和负责任使用。

> Large language models (LLMs) have become increasingly sophisticated, leading to widespread deployment in sensitive applications where safety and reliability are paramount. However, LLMs have inherent risks accompanying them, including bias, potential for unsafe actions, dataset poisoning, lack of explainability, hallucinations, and non-reproducibility. These risks necessitate the development of "guardrails" to align LLMs with desired behaviors and mitigate potential harm.
  This work explores the risks associated with deploying LLMs and evaluates current approaches to implementing guardrails and model alignment techniques. We examine intrinsic and extrinsic bias evaluation methods and discuss the importance of fairness metrics for responsible AI development. The safety and reliability of agentic LLMs (those capable of real-world actions) are explored, emphasizing the need for testability, fail-safes, and situational awareness.
  Technical strategies for securing LLMs are presented, including a layered protection model operating at external, secondary, and internal levels. System prompts, Retrieval-Augmented Generation (RAG) architectures, and techniques to minimize bias and protect privacy are highlighted.
  Effective guardrail design requires a deep understanding of the LLM's intended use case, relevant regulations, and ethical considerations. Striking a balance between competing requirements, such as accuracy and privacy, remains an ongoing challenge. This work underscores the importance of continuous research and development to ensure the safe and responsible use of LLMs in real-world applications.

[Arxiv](https://arxiv.org/abs/2406.12934)