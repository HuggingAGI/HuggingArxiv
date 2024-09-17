# 类人推理的自动控制：探索语言模型驱动的空中交通代理

发布时间：2024年09月15日

`Agent` `航空交通` `人工智能`

> Automatic Control With Human-Like Reasoning: Exploring Language Model Embodied Air Traffic Agents

# 摘要

> 语言模型的进步为空中交通管制研究开辟了新天地。目前研究主要集中在文本和语言应用上，但这些模型因其与空中交通环境的具身互动能力，可能在空中交通管制领域发挥更大作用。它们还能通过类语言推理解释决策，这是自动空中交通管制实施的一大难题。本文探讨了基于语言模型的代理，该代理具备函数调用和学习能力，能在无人干预下解决空中交通冲突。研究核心包括基础大型语言模型、代理与模拟器互动的工具，以及创新的经验库。经验库作为向量数据库，存储了代理从模拟器和语言模型互动中习得的合成知识。为评估代理性能，我们测试了开源和闭源模型。结果显示，不同配置的代理性能差异显著。最佳配置几乎解决了所有120个即将发生的冲突场景中的119个，最多可同时处理四架飞机。更重要的是，代理能提供人类级别的文本解释，说明交通情况和冲突解决策略。

> Recent developments in language models have created new opportunities in air traffic control studies. The current focus is primarily on text and language-based use cases. However, these language models may offer a higher potential impact in the air traffic control domain, thanks to their ability to interact with air traffic environments in an embodied agent form. They also provide a language-like reasoning capability to explain their decisions, which has been a significant roadblock for the implementation of automatic air traffic control.
  This paper investigates the application of a language model-based agent with function-calling and learning capabilities to resolve air traffic conflicts without human intervention. The main components of this research are foundational large language models, tools that allow the agent to interact with the simulator, and a new concept, the experience library. An innovative part of this research, the experience library, is a vector database that stores synthesized knowledge that agents have learned from interactions with the simulations and language models.
  To evaluate the performance of our language model-based agent, both open-source and closed-source models were tested. The results of our study reveal significant differences in performance across various configurations of the language model-based agents. The best-performing configuration was able to solve almost all 120 but one imminent conflict scenarios, including up to four aircraft at the same time. Most importantly, the agents are able to provide human-level text explanations on traffic situations and conflict resolution strategies.

[Arxiv](https://arxiv.org/abs/2409.09717)