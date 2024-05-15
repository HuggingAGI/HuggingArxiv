# 教皇当然是天主教的，这无需多言。本文聚焦于大型语言模型中意图解析的生成式评估，探讨其在理解用户意图方面的深度与广度。

发布时间：2024年05月14日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在理解非字面表达和意图方面的能力，并提出了评估方法。它关注的是LLMs的理论性能和局限性，特别是在语用交流方面的挑战，这属于LLM理论研究的范畴。论文中提到的评估方法、性能分析以及对未来研究的建议，都是围绕LLMs的理论理解和改进展开的，因此将其归类为LLM理论。` `人工智能交互`

> Is the Pope Catholic? Yes, the Pope is Catholic. Generative Evaluation of Intent Resolution in LLMs

# 摘要

> 人类交流时往往含蓄而非直白，这要求无论是人类还是AI对话者，都需超越字面意义去理解对方的真实意图。我们提出了一种新颖的方法，通过分析大型语言模型（LLMs）对非字面表达的回应，来评估其对意图的理解。理想状态下，LLMs应根据非字面表达背后的真实意图作出回应，而非仅基于字面意思。研究显示，LLMs在理解非字面语言并作出恰当回应方面表现不佳，平均准确率仅在50-55%之间。尽管提供明确的意图信息能显著提升性能（如Mistral-Instruct达到75%），但仍显示出在根据给定意图生成合适回应方面的挑战。使用思维链方法让模型阐明意图，提升有限（Mistral-Instruct达到60%）。这些结果表明，LLMs在语用交流方面尚未成熟，凸显了开发更有效的意图建模和语用生成方法的必要性。

> Humans often express their communicative intents indirectly or non-literally, which requires their interlocutors -- human or AI -- to understand beyond the literal meaning of words. While most existing work has focused on discriminative evaluations, we present a new approach to generatively evaluate large language models' (LLMs') intention understanding by examining their responses to non-literal utterances. Ideally, an LLM should respond in line with the true intention of a non-literal utterance, not its literal interpretation. Our findings show that LLMs struggle to generate pragmatically relevant responses to non-literal language, achieving only 50-55% accuracy on average. While explicitly providing oracle intentions significantly improves performance (e.g., 75% for Mistral-Instruct), this still indicates challenges in leveraging given intentions to produce appropriate responses. Using chain-of-thought to make models spell out intentions yields much smaller gains (60% for Mistral-Instruct). These findings suggest that LLMs are not yet effective pragmatic interlocutors, highlighting the need for better approaches for modeling intentions and utilizing them for pragmatic generation.

[Arxiv](https://arxiv.org/abs/2405.08760)