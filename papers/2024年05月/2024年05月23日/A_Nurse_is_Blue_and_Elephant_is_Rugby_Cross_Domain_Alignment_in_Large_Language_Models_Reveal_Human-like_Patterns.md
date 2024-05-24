# 大型语言模型中的跨域对齐展现出类似人类的模式，如“护士”对应“蓝色”，“大象”对应“橄榄球”。

发布时间：2024年05月23日

`Agent

这篇论文主要关注的是大型语言模型（LLMs）在跨域对齐任务中的表现，特别是它们如何处理和解释抽象与具体概念之间的映射。研究通过行为研究评估了LLMs的概念化和推理能力，并分析了模型在群体和个体层面的回答。这种对模型在特定认知任务上的表现和推理能力的评估，更偏向于Agent的范畴，即研究模型如何作为一个智能体处理和解决复杂的认知任务。` `认知科学` `语言模型评估`

> A Nurse is Blue and Elephant is Rugby: Cross Domain Alignment in Large Language Models Reveal Human-like Patterns

# 摘要

> 跨域对齐任务，如“若医生是颜色，那会是什么颜色？”，旨在探索人们如何通过类别间的映射及其推理过程来表达具体与抽象概念。本文将此认知科学任务应用于评估大型语言模型（LLMs）的概念化与推理能力。通过行为研究，我们向多个LLMs提出跨域映射问题，并分析其群体与个体层面的回答。同时，我们通过分析模型对映射的解释，评估其推理能力。研究发现，模型在概念表示及行为上与人类相似，且多数解释合理，推理路径与人类相近。

> Cross-domain alignment refers to the task of mapping a concept from one domain to another. For example, ``If a \textit{doctor} were a \textit{color}, what color would it be?''. This seemingly peculiar task is designed to investigate how people represent concrete and abstract concepts through their mappings between categories and their reasoning processes over those mappings. In this paper, we adapt this task from cognitive science to evaluate the conceptualization and reasoning abilities of large language models (LLMs) through a behavioral study. We examine several LLMs by prompting them with a cross-domain mapping task and analyzing their responses at both the population and individual levels. Additionally, we assess the models' ability to reason about their predictions by analyzing and categorizing their explanations for these mappings. The results reveal several similarities between humans' and models' mappings and explanations, suggesting that models represent concepts similarly to humans. This similarity is evident not only in the model representation but also in their behavior. Furthermore, the models mostly provide valid explanations and deploy reasoning paths that are similar to those of humans.

[Arxiv](https://arxiv.org/abs/2405.14863)