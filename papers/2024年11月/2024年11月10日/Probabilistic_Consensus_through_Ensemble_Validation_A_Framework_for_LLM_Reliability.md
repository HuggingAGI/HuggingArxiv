# 通过集成验证的概率共识：LLM 可靠性的框架

发布时间：2024年11月10日

`LLM应用`

> Probabilistic Consensus through Ensemble Validation: A Framework for LLM Reliability

# 摘要

> 大型语言模型（LLMs）在文本生成方面已取得显著进展，但在医疗保健、法律和金融等高风险领域的自主部署中往往缺乏所需的可靠性。现有的方法依赖于外部知识或人工监督，限制了可扩展性。我们引入了一个新颖的框架，通过模型共识将集成方法重新用于内容验证。在对 78 个需要事实准确性和因果一致性的复杂案例的测试中，我们的框架使用两个模型将精度从 73.1%提高到 93.9%（95%置信区间：83.5%-97.9%），使用三个模型提高到 95.6%（95%置信区间：85.2%-98.8%）。统计分析表明，模型间有很强的一致性（$κ$ > 0.76），同时保持足够的独立性，通过不一致来捕捉错误。我们勾勒出了一条清晰的途径，通过额外的验证器和改进来进一步提高精度。尽管当前的方法受到多项选择格式要求和处理延迟的限制，但它为在关键应用中实现可靠的自主人工智能系统提供了直接价值。

> Large Language Models (LLMs) have shown significant advances in text generation but often lack the reliability needed for autonomous deployment in high-stakes domains like healthcare, law, and finance. Existing approaches rely on external knowledge or human oversight, limiting scalability. We introduce a novel framework that repurposes ensemble methods for content validation through model consensus. In tests across 78 complex cases requiring factual accuracy and causal consistency, our framework improved precision from 73.1% to 93.9% with two models (95% CI: 83.5%-97.9%) and to 95.6% with three models (95% CI: 85.2%-98.8%). Statistical analysis indicates strong inter-model agreement ($κ$ > 0.76) while preserving sufficient independence to catch errors through disagreement. We outline a clear pathway to further enhance precision with additional validators and refinements. Although the current approach is constrained by multiple-choice format requirements and processing latency, it offers immediate value for enabling reliable autonomous AI systems in critical applications.

[Arxiv](https://arxiv.org/abs/2411.06535)