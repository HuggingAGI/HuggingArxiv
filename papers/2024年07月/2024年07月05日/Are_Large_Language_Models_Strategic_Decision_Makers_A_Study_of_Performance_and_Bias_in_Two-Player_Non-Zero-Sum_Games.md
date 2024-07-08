# 大型语言模型能否成为战略决策者？本研究探讨了在双人非零和游戏中，这些模型的表现及其潜在偏差。

发布时间：2024年07月05日

`LLM理论` `人工智能` `博弈论`

> Are Large Language Models Strategic Decision Makers? A Study of Performance and Bias in Two-Player Non-Zero-Sum Games

# 摘要

> 大型语言模型（LLM）在实际应用中日益增多，但其战略决策能力尚未充分挖掘。博弈论为评估LLM在与其他代理互动时的决策能力提供了有效框架。虽然先前研究显示，LLM能通过精心设计的提示解决特定任务，但面对变化的问题设置或提示时，它们往往表现不佳。本研究深入探讨了LLM在猎鹿游戏和囚徒困境等战略游戏中的行为，揭示了在不同游戏设置和提示下性能的波动。研究发现，最先进的LLM至少存在以下一种系统偏差：位置偏差、收益偏差或行为偏差。当游戏配置与这些偏差不匹配时，LLM的性能显著下降。性能评估依据于选择符合双方玩家偏好行为的正确行动，而一致性则指LLM的偏差是否与正确行动相符。例如，GPT-4o在偏差不一致时性能下降达34%。此外，“越大越新越好”的普遍观念在此并不适用，GPT-4o（目前表现最佳的LLM）性能下降最为严重。最后，尽管思维链提示能一定程度上减轻偏差影响，但仍未能从根本上解决问题。

> Large Language Models (LLMs) have been increasingly used in real-world settings, yet their strategic abilities remain largely unexplored. Game theory provides a good framework for assessing the decision-making abilities of LLMs in interactions with other agents. Although prior studies have shown that LLMs can solve these tasks with carefully curated prompts, they fail when the problem setting or prompt changes. In this work we investigate LLMs' behaviour in strategic games, Stag Hunt and Prisoner Dilemma, analyzing performance variations under different settings and prompts. Our results show that the tested state-of-the-art LLMs exhibit at least one of the following systematic biases: (1) positional bias, (2) payoff bias, or (3) behavioural bias. Subsequently, we observed that the LLMs' performance drops when the game configuration is misaligned with the affecting biases. Performance is assessed based on the selection of the correct action, one which agrees with the prompted preferred behaviours of both players. Alignment refers to whether the LLM's bias aligns with the correct action. For example, GPT-4o's average performance drops by 34% when misaligned. Additionally, the current trend of "bigger and newer is better" does not hold for the above, where GPT-4o (the current best-performing LLM) suffers the most substantial performance drop. Lastly, we note that while chain-of-thought prompting does reduce the effect of the biases on most models, it is far from solving the problem at the fundamental level.

[Arxiv](https://arxiv.org/abs/2407.04467)