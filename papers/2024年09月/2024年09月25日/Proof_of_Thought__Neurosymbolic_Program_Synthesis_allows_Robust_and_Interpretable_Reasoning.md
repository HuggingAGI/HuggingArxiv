# 思维证明：神经符号程序合成助力鲁棒且可解释的推理

发布时间：2024年09月25日

`LLM理论` `人工智能` `逻辑推理`

> Proof of Thought : Neurosymbolic Program Synthesis allows Robust and Interpretable Reasoning

# 摘要

> 大型语言模型（LLM）虽然革新了自然语言处理，但在新领域和复杂逻辑推理中仍显不足。为此，我们提出了“思维证明”框架，旨在提升 LLM 输出的可靠性与透明度。该框架通过自定义解释器，将 LLM 的输出转化为一阶逻辑结构，供定理证明器审查。核心在于一种基于 JSON 的领域特定语言，巧妙结合了精确逻辑与直观概念，既确保严格验证，又便于人类理解。主要创新包括强化逻辑完整性的类型系统、明确区分事实与推理的规则表示，以及灵活扩展至各领域应用的架构。通过 StrategyQA 和新多模态任务的测试，我们验证了“思维证明”在开放场景中的优越性能。这一技术不仅满足了 AI 系统的问责需求，还为高风险领域的人机协作监督奠定了基础。

> Large Language Models (LLMs) have revolutionized natural language processing, yet they struggle with inconsistent reasoning, particularly in novel domains and complex logical sequences. This research introduces Proof of Thought, a framework that enhances the reliability and transparency of LLM outputs. Our approach bridges LLM-generated ideas with formal logic verification, employing a custom interpreter to convert LLM outputs into First Order Logic constructs for theorem prover scrutiny. Central to our method is an intermediary JSON-based Domain-Specific Language, which by design balances precise logical structures with intuitive human concepts. This hybrid representation enables both rigorous validation and accessible human comprehension of LLM reasoning processes. Key contributions include a robust type system with sort management for enhanced logical integrity, explicit representation of rules for clear distinction between factual and inferential knowledge, and a flexible architecture that allows for easy extension to various domain-specific applications. We demonstrate Proof of Thought's effectiveness through benchmarking on StrategyQA and a novel multimodal reasoning task, showing improved performance in open-ended scenarios. By providing verifiable and interpretable results, our technique addresses critical needs for AI system accountability and sets a foundation for human-in-the-loop oversight in high-stakes domains.

[Arxiv](https://arxiv.org/abs/2409.17270)