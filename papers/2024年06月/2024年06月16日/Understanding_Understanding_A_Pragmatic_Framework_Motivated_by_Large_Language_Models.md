# 洞察理解之道：大型语言模型启发的实用框架

发布时间：2024年06月16日

`Agent

这篇论文提出了一种新颖的测试框架，用于评估代理（包括机器和人类）对某一主题的理解程度。该框架基于图灵测试的理念，侧重于代理的实际表现，特别是其回答问题的质量。它包括明确问题范围、设定通用能力门槛、排除荒谬答案等关键要素。虽然全面测试在非平凡领域内不可行，但通过随机抽样和概率置信界限的应用，可以实现高置信度。此外，提供答案解释可以减少达到可接受置信度所需的样本量。该框架不仅为理解测试提供了实用方案，也为构建真正理解型AI代理提供了工具。因此，这篇论文更符合Agent分类，因为它专注于评估和提升代理的理解能力。` `人工智能测试` `教育评估`

> Understanding Understanding: A Pragmatic Framework Motivated by Large Language Models

# 摘要

> 在大型语言模型（LLMs）迅速崛起及其是否具备人类水平特质的争论背景下，我们提出了一种新颖的测试框架，旨在评估任何代理（无论是机器还是人类）对某一主题的理解程度。该框架采用图灵测试的理念，仅依据代理的实际表现，尤其是其回答问题的质量。框架的关键要素包括明确问题范围（“理解边界”），设定通用能力门槛（“及格标准”），排除“荒谬答案”，同时允许对部分问题给出错误或“不确定”的回答。尽管在非平凡领域内进行全面测试不可行，我们通过随机抽样和概率置信界限的应用，展示了如何达到高置信度。此外，提供答案解释能有效降低达到可接受置信度所需的样本量，因为解释本身即表明了回答类似问题的能力。依据此框架，目前的 LLMs 尚未达到理解非平凡领域的水平，但该框架不仅为理解测试提供了实用方案，也为构建真正理解型 AI 代理提供了工具。

> Motivated by the rapid ascent of Large Language Models (LLMs) and debates about the extent to which they possess human-level qualities, we propose a framework for testing whether any agent (be it a machine or a human) understands a subject matter. In Turing-test fashion, the framework is based solely on the agent's performance, and specifically on how well it answers questions. Elements of the framework include circumscribing the set of questions (the "scope of understanding"), requiring general competence ("passing grade"), avoiding "ridiculous answers", but still allowing wrong and "I don't know" answers to some questions. Reaching certainty about these conditions requires exhaustive testing of the questions which is impossible for nontrivial scopes, but we show how high confidence can be achieved via random sampling and the application of probabilistic confidence bounds. We also show that accompanying answers with explanations can improve the sample complexity required to achieve acceptable bounds, because an explanation of an answer implies the ability to answer many similar questions. According to our framework, current LLMs cannot be said to understand nontrivial domains, but as the framework provides a practical recipe for testing understanding, it thus also constitutes a tool for building AI agents that do understand.

[Arxiv](https://arxiv.org/abs/2406.10937)