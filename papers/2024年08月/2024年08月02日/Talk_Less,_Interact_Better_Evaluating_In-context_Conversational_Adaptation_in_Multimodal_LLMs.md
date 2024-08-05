# 言简意赅，互动更佳：探究多模态LLM中的上下文对话适应性

发布时间：2024年08月02日

`LLM应用` `人工智能` `语言学`

> Talk Less, Interact Better: Evaluating In-context Conversational Adaptation in Multimodal LLMs

# 摘要

> 人类在交流中会自发地使用更高效的语言，通过适应和创造临时惯例来实现。这一现象通过参考游戏得到了深入研究，揭示了人类语言超越简单意图传递的特性。然而，多模态大型语言模型 (MLLMs) 是否能在互动中同样提升沟通效率，以及它们为此可能采用的机制，仍是一个未解之谜。为此，我们推出了 ICCA，一个自动化框架，专门评估 MLLMs 中的对话适应能力。我们的评估显示，尽管 MLLMs 能理解对话者语言的效率提升，但它们自身并不会自发地提高语言效率。这种能力仅在某些模型（如 GPT-4）中通过强烈提示才能激发。这表明，当前的训练方法并未赋予模型这种人类语言的常见特性。ICCA 框架现已开放，地址为 https://github.com/lil-lab/ICCA。

> Humans spontaneously use increasingly efficient language as interactions progress, by adapting and forming ad-hoc conventions. This phenomenon has been studied extensively using reference games, showing properties of human language that go beyond relaying intents. It remains unexplored whether multimodal large language models (MLLMs) similarly increase communication efficiency during interactions, and what mechanisms they may adopt for this purpose. We introduce ICCA, an automated framework to evaluate such conversational adaptation as an in-context behavior in MLLMs. We evaluate several state-of-the-art MLLMs, and observe that while they may understand the increasingly efficient language of their interlocutor, they do not spontaneously make their own language more efficient over time. This latter ability can only be elicited in some models (e.g., GPT-4) with heavy-handed prompting. This shows that this property of linguistic interaction does not arise from current training regimes, even though it is a common hallmark of human language. ICCA is available at https://github.com/lil-lab/ICCA.

[Arxiv](https://arxiv.org/abs/2408.01417)