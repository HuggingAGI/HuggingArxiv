# 大型语言模型的自我指导图灵测试

发布时间：2024年08月19日

`LLM应用` `人工智能`

> Self-Directed Turing Test for Large Language Models

# 摘要

> 图灵测试旨在检验AI在自然语言对话中是否能展现人类般的行为。传统图灵测试采用单一消息的固定对话模式，并依赖人类持续参与指导，这不仅未能体现自然对话风格，也限制了大型语言模型（LLM）在复杂长对话中的评估。为此，本文提出“自我指导图灵测试”，通过引入连续多消息的对话模式，增强交流的动态性，并让LLM主导大部分测试过程，从而大幅减轻人类负担。在此基础上，模型与人类进行简短对话，并与同主题的人-人对话对比，通过问卷评估。我们新创的X-Turn通过率指标，揭示了LLM在不同对话时长中的类人性表现。尽管如GPT-4初期表现优异，但随着对话深入，其通过率逐渐下降，凸显了长期保持一致性的挑战。

> The Turing test examines whether AIs can exhibit human-like behaviour in natural language conversations. Traditional Turing tests adopt a rigid dialogue format where each participant sends only one message each time and require continuous human involvement to direct the entire interaction with the test subject. This fails to reflect a natural conversational style and hinders the evaluation of Large Language Models (LLMs) in complex and prolonged dialogues. This paper proposes the Self-Directed Turing Test, which extends the original test with a burst dialogue format, allowing more dynamic exchanges by multiple consecutive messages. It further efficiently reduces human workload by having the LLM self-direct the majority of the test process, iteratively generating dialogues that simulate its interaction with humans. With the pseudo-dialogue history, the model then engages in a shorter dialogue with a human, which is paired with a human-human conversation on the same topic to be judged using questionnaires. We introduce the X-Turn Pass-Rate metric to assess the human likeness of LLMs across varying durations. While LLMs like GPT-4 initially perform well, achieving pass rates of 51.9% and 38.9% during 3 turns and 10 turns of dialogues respectively, their performance drops as the dialogue progresses, which underscores the difficulty in maintaining consistency in the long term.

[Arxiv](https://arxiv.org/abs/2408.09853)