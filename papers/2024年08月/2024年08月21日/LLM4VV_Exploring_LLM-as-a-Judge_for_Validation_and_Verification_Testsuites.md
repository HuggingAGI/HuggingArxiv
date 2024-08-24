# LLM4VV：探索 LLM 在验证与验证测试中的判断角色

发布时间：2024年08月21日

`LLM应用` `软件开发` `人工智能`

> LLM4VV: Exploring LLM-as-a-Judge for Validation and Verification Testsuites

# 摘要

> 大型语言模型（LLM）正不断革新软件开发领域，合理运用能大幅提速开发周期。然而，社区对其在偏见或敏感数据上的训练持谨慎态度，担心这会导致偏见输出和机密信息泄露。此外，这些黑箱模型的碳足迹和不可解释性也引发了对LLM实用性的质疑。本文在探讨LLM带来的丰富机遇的同时，研究了评估基于指令编程模型编译器实现的测试方法，并深入剖析了LLM的内部机制。实验表明，采用基于代理的提示策略和构建验证流程，显著提升了DeepSeek Coder（评估选用的LLM）的性能。

> Large Language Models (LLM) are evolving and have significantly revolutionized the landscape of software development. If used well, they can significantly accelerate the software development cycle. At the same time, the community is very cautious of the models being trained on biased or sensitive data, which can lead to biased outputs along with the inadvertent release of confidential information. Additionally, the carbon footprints and the un-explainability of these black box models continue to raise questions about the usability of LLMs.
  With the abundance of opportunities LLMs have to offer, this paper explores the idea of judging tests used to evaluate compiler implementations of directive-based programming models as well as probe into the black box of LLMs. Based on our results, utilizing an agent-based prompting approach and setting up a validation pipeline structure drastically increased the quality of DeepSeek Coder, the LLM chosen for the evaluation purposes.

[Arxiv](https://arxiv.org/abs/2408.11729)