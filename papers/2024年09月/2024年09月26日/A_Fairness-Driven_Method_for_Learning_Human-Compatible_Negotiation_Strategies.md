# 一种公平驱动的策略，旨在学习与人类和谐共处的谈判技巧

发布时间：2024年09月26日

`Agent` `人工智能`

> A Fairness-Driven Method for Learning Human-Compatible Negotiation Strategies

# 摘要

> 尽管AI和NLP领域不断进步，谈判对AI代理来说仍是一大挑战。传统博弈论方法在双人零和游戏中表现出色，但在谈判中却因无法学习与人类兼容的策略而受限。而仅依赖人类数据的方法则往往局限于特定领域，缺乏博弈论策略的理论保障。基于公平作为一般和游戏中优化标准的理念，我们提出了FDHC谈判框架，将公平融入奖励设计和搜索，以学习与人类兼容的策略。我们的LGM-Zero技术结合了RL和搜索，利用预训练语言模型从大动作空间中检索人类友好报价。实验结果显示，我们的方法能实现更平等的谈判结果，提升谈判质量。

> Despite recent advancements in AI and NLP, negotiation remains a difficult domain for AI agents. Traditional game theoretic approaches that have worked well for two-player zero-sum games struggle in the context of negotiation due to their inability to learn human-compatible strategies. On the other hand, approaches that only use human data tend to be domain-specific and lack the theoretical guarantees provided by strategies grounded in game theory. Motivated by the notion of fairness as a criterion for optimality in general sum games, we propose a negotiation framework called FDHC which incorporates fairness into both the reward design and search to learn human-compatible negotiation strategies. Our method includes a novel, RL+search technique called LGM-Zero which leverages a pre-trained language model to retrieve human-compatible offers from large action spaces. Our results show that our method is able to achieve more egalitarian negotiation outcomes and improve negotiation quality.

[Arxiv](https://arxiv.org/abs/2409.18335)