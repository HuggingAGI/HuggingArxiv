# 逻辑代理：借助逻辑规则的调用提升有效性

发布时间：2024年04月28日

`Agent` `人工智能` `逻辑推理`

> Logic Agent: Enhancing Validity with Logic Rule Invocation

# 摘要

> 链式思考（CoT）提示技术在提升语言模型在推理任务中的推理能力方面发挥了重要作用。然而，它在确认推理的准确性和信息丰富性方面仍面临挑战。为克服这些难题，本研究提出了逻辑代理（LA），这是一个基于代理的框架，通过策略性地应用逻辑规则，旨在提高大型语言模型（LLMs）推理过程的有效性。与传统方法不同，LA 将 LLMs 转换为能够动态应用命题逻辑规则的逻辑代理，通过将自然语言输入转换为结构化逻辑形式来启动推理过程。该逻辑代理使用一系列预定义的函数系统地导航推理过程，不仅促进了推理结构的有序和连贯生成，还显著提升了其可解释性和逻辑一致性。通过广泛的实验，我们展示了 LA 在不同模型尺寸上的扩展能力，并在多样化任务中显著提高了复杂推理的精确度。

> Chain-of-Thought (CoT) prompting has emerged as a pivotal technique for augmenting the inferential capabilities of language models during reasoning tasks. Despite its advancements, CoT often grapples with challenges in validating reasoning validity and ensuring informativeness. Addressing these limitations, this paper introduces the Logic Agent (LA), an agent-based framework aimed at enhancing the validity of reasoning processes in Large Language Models (LLMs) through strategic logic rule invocation. Unlike conventional approaches, LA transforms LLMs into logic agents that dynamically apply propositional logic rules, initiating the reasoning process by converting natural language inputs into structured logic forms. The logic agent leverages a comprehensive set of predefined functions to systematically navigate the reasoning process. This methodology not only promotes the structured and coherent generation of reasoning constructs but also significantly improves their interpretability and logical coherence. Through extensive experimentation, we demonstrate LA's capacity to scale effectively across various model sizes, markedly improving the precision of complex reasoning across diverse tasks.

[Arxiv](https://arxiv.org/abs/2404.18130)