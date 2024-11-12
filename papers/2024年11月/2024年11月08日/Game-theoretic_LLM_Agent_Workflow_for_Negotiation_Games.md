# 博弈论的大型语言模型：用于谈判游戏的代理工作流程

发布时间：2024年11月08日

`LLM应用` `博弈论` `战略决策`

> Game-theoretic LLM: Agent Workflow for Negotiation Games

# 摘要

> 这篇论文研究了大型语言模型（LLM）在战略决策情境中的合理性，特别是在博弈论的框架内。我们在一系列完全信息和不完全信息的游戏中评估了几个最先进的LLM。我们的发现表明，LLM经常偏离理性策略，特别是随着游戏的复杂性增加，如更大的收益矩阵或更深的序列树。
为了解决这些限制，我们设计了多个博弈论工作流程，以指导LLM的推理和决策过程。这些工作流程旨在提高模型计算纳什均衡和做出理性选择的能力，即使在不确定和不完全信息的条件下。实验结果表明，采用这些工作流程显著提高了LLM在博弈论任务中的合理性和稳健性。具体而言，通过工作流程，LLM在识别最优策略、在谈判场景中实现接近最优的分配以及降低在谈判中被利用的敏感性方面表现出显著的改进。此外，我们探讨了关于代理是否合理采用这种工作流程的元战略考虑，认识到使用或放弃工作流程的决定本身就构成了一个博弈论问题。
我们的研究有助于更深入地理解LLM在战略情境中的决策能力，并为通过结构化工作流程提高其合理性提供了见解。研究结果对开发更强大和战略上合理的能够在复杂交互环境中导航的AI代理具有影响。支持本研究的代码和数据可在url{https://github.com/Wenyueh/game_theory}获取。

> This paper investigates the rationality of large language models (LLMs) in strategic decision-making contexts, specifically within the framework of game theory. We evaluate several state-of-the-art LLMs across a spectrum of complete-information and incomplete-information games. Our findings reveal that LLMs frequently deviate from rational strategies, particularly as the complexity of the game increases with larger payoff matrices or deeper sequential trees.
  To address these limitations, we design multiple game-theoretic workflows that guide the reasoning and decision-making processes of LLMs. These workflows aim to enhance the models' ability to compute Nash Equilibria and make rational choices, even under conditions of uncertainty and incomplete information. Experimental results demonstrate that the adoption of these workflows significantly improves the rationality and robustness of LLMs in game-theoretic tasks. Specifically, with the workflow, LLMs exhibit marked improvements in identifying optimal strategies, achieving near-optimal allocations in negotiation scenarios, and reducing susceptibility to exploitation during negotiations. Furthermore, we explore the meta-strategic considerations of whether it is rational for agents to adopt such workflows, recognizing that the decision to use or forgo the workflow constitutes a game-theoretic issue in itself.
  Our research contributes to a deeper understanding of LLMs' decision-making capabilities in strategic contexts and provides insights into enhancing their rationality through structured workflows. The findings have implications for the development of more robust and strategically sound AI agents capable of navigating complex interactive environments. Code and data supporting this study are available at url{https://github.com/Wenyueh/game_theory}.

[Arxiv](https://arxiv.org/abs/2411.05990)