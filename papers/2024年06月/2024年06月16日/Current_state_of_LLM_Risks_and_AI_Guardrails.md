# 大型语言模型（LLM）当前面临的风险与人工智能安全保障现状

发布时间：2024年06月16日

`Agent、RAG、LLM应用

解释：
- **Agent**：论文中提到了“特别关注了能够执行现实世界行动的代理性LLMs的安全性和可靠性”，这表明论文涉及到了Agent相关的研究，即关注那些能够执行实际操作的智能代理的安全性和可靠性。
- **RAG**（检索增强生成）：论文中明确提到了“检索增强生成（RAG）架构”，这是论文讨论的一个具体技术点，属于RAG分类。
- **LLM应用**：论文整体上探讨了大型语言模型（LLMs）在敏感领域的应用及其安全性问题，包括偏见、不安全行为等，这些都是LLM在实际应用中需要解决的问题，因此属于LLM应用分类。

虽然论文涉及到了LLM的一些应用和安全问题，但并没有深入探讨LLM的理论基础或模型架构，因此不归类于LLM理论。` `安全技术` `人工智能伦理`

> Current state of LLM Risks and AI Guardrails

# 摘要

> 随着大型语言模型（LLMs）的日益复杂，它们在安全性和可靠性至关重要的敏感领域得到了广泛应用。然而，LLMs固有的风险不容忽视，包括偏见、潜在的不安全行为、数据集中毒、缺乏可解释性、幻觉和不可重现性。因此，开发“护栏”以确保LLMs行为符合预期并减少潜在危害变得至关重要。本研究深入探讨了LLMs部署中的风险，并评估了当前的护栏实施和模型对齐技术。我们分析了偏见评估的内在和外在方法，并强调了在负责任AI开发中公平性指标的重要性。特别关注了能够执行现实世界行动的代理性LLMs的安全性和可靠性，强调了测试性、故障安全和情境意识的重要性。我们提出了一套确保LLMs安全的技术策略，包括一个多层次的保护模型，涵盖外部、次级和内部层面。重点介绍了系统提示、检索增强生成（RAG）架构以及减少偏见和保护隐私的技术。设计有效的护栏需要对LLM的预期用途、相关法规和伦理问题有深刻理解。在准确性和隐私等相互竞争的需求之间找到平衡点仍然是一个挑战。本研究强调了持续研究和开发的重要性，以确保LLMs在现实世界应用中的安全和负责任使用。

> Large language models (LLMs) have become increasingly sophisticated, leading to widespread deployment in sensitive applications where safety and reliability are paramount. However, LLMs have inherent risks accompanying them, including bias, potential for unsafe actions, dataset poisoning, lack of explainability, hallucinations, and non-reproducibility. These risks necessitate the development of "guardrails" to align LLMs with desired behaviors and mitigate potential harm.
  This work explores the risks associated with deploying LLMs and evaluates current approaches to implementing guardrails and model alignment techniques. We examine intrinsic and extrinsic bias evaluation methods and discuss the importance of fairness metrics for responsible AI development. The safety and reliability of agentic LLMs (those capable of real-world actions) are explored, emphasizing the need for testability, fail-safes, and situational awareness.
  Technical strategies for securing LLMs are presented, including a layered protection model operating at external, secondary, and internal levels. System prompts, Retrieval-Augmented Generation (RAG) architectures, and techniques to minimize bias and protect privacy are highlighted.
  Effective guardrail design requires a deep understanding of the LLM's intended use case, relevant regulations, and ethical considerations. Striking a balance between competing requirements, such as accuracy and privacy, remains an ongoing challenge. This work underscores the importance of continuous research and development to ensure the safe and responsible use of LLMs in real-world applications.

[Arxiv](https://arxiv.org/abs/2406.12934)