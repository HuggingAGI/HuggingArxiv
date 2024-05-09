# 个性化的LLMs在多议题谈判游戏中展现风采在这项研究中，我们探讨了具有不同个性的语言模型在多议题谈判游戏中的表现。通过赋予LLMs独特的性格特征，我们旨在模拟更真实的谈判场景，并分析这些个性如何影响谈判策略和结果。我们的实验结果揭示了个性化的LLMs在理解和适应复杂谈判环境方面的潜力，以及它们如何通过展现不同的谈判风格来达成更有利的协议。

发布时间：2024年05月08日

`Agent

这篇论文主要探讨了大型语言模型（LLMs）赋能的AI代理在博弈论框架中的谈判能力，以及如何评估这些代理在谈判中的公平性和风险。它通过模拟谈判实验来分析LLMs的行为特征，并提供了设计谈判机器人的实用建议。因此，它更符合Agent分类，因为它关注的是LLMs作为智能代理在特定任务（即谈判）中的应用和行为分析。` `人工智能` `谈判策略`

> LLMs with Personalities in Multi-issue Negotiation Games

# 摘要

> 大型语言模型（LLMs）赋能的AI代理已能执行多种人类任务。我们采用大五人格的经典定义，评估LLMs在博弈论框架中的谈判能力，并探讨衡量公平与风险的方法论难题。通过1500次单问题和多问题谈判模拟，我们发现随着问题估值的不对称性增加，谈判领域的复杂性提升，虽然协议率上升，但激进谈判带来的盈余却减少。利用梯度提升回归和Shapley解释器分析，我们发现高开放性、尽责性和神经质与公平倾向相关，而低宜人性和低开放性则与理性倾向相关。低尽责性则与高毒性行为相关。这些发现暗示LLMs内置有倾向于公平行为的保护机制，但也可被“越狱”以利用对手的宜人性。此外，我们还提供了设计谈判机器人的实用建议，并构建了一个基于博弈论和计算社会科学的谈判行为评估框架。

> Powered by large language models (LLMs), AI agents have become capable of many human tasks. Using the most canonical definitions of the Big Five personality, we measure the ability of LLMs to negotiate within a game-theoretical framework, as well as methodological challenges to measuring notions of fairness and risk. Simulations (n=1,500) for both single-issue and multi-issue negotiation reveal increase in domain complexity with asymmetric issue valuations improve agreement rates but decrease surplus from aggressive negotiation. Through gradient-boosted regression and Shapley explainers, we find high openness, conscientiousness, and neuroticism are associated with fair tendencies; low agreeableness and low openness are associated with rational tendencies. Low conscientiousness is associated with high toxicity. These results indicate that LLMs may have built-in guardrails that default to fair behavior, but can be "jail broken" to exploit agreeable opponents. We also offer pragmatic insight in how negotiation bots can be designed, and a framework of assessing negotiation behavior based on game theory and computational social science.

[Arxiv](https://arxiv.org/abs/2405.05248)