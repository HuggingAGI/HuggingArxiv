# 评估并增强生成模型的说服力

发布时间：2024年10月03日

`LLM应用` `社会公益`

> Measuring and Improving Persuasiveness of Generative Models

# 摘要

> LLM 在生成内容和直接互动中日益普及，带来了社会机遇与挑战。一方面，它们能助力广告和社会公益，如解决药物成瘾；另一方面，也可能被滥用，传播错误信息和影响政治观点。为此，我们推出了 PersuasionBench 和 PersuasionArena，首个大规模基准和竞技场，用于自动评估生成模型的说服力。研究发现，模型大小与说服力正相关，但小模型通过针对性训练也能超越大模型。这挑战了依赖规模的假设，对模型开发和政策制定有重要启示。我们呼吁社区参与，共同推进 AI 说服力研究，网址：https://bit.ly/measure-persuasion。

> LLMs are increasingly being used in workflows involving generating content to be consumed by humans (e.g., marketing) and also in directly interacting with humans (e.g., through chatbots). The development of such systems that are capable of generating verifiably persuasive messages presents both opportunities and challenges for society. On the one hand, such systems could positively impact domains like advertising and social good, such as addressing drug addiction, and on the other, they could be misused for spreading misinformation and shaping political opinions. To channel LLMs' impact on society, we need to develop systems to measure and benchmark their persuasiveness. With this motivation, we introduce PersuasionBench and PersuasionArena, the first large-scale benchmark and arena containing a battery of tasks to measure the persuasion ability of generative models automatically. We investigate to what extent LLMs know and leverage linguistic patterns that can help them generate more persuasive language. Our findings indicate that the persuasiveness of LLMs correlates positively with model size, but smaller models can also be made to have a higher persuasiveness than much larger models. Notably, targeted training using synthetic and natural datasets significantly enhances smaller models' persuasive capabilities, challenging scale-dependent assumptions. Our findings carry key implications for both model developers and policymakers. For instance, while the EU AI Act and California's SB-1047 aim to regulate AI models based on the number of floating point operations, we demonstrate that simple metrics like this alone fail to capture the full scope of AI's societal impact. We invite the community to explore and contribute to PersuasionArena and PersuasionBench, available at https://bit.ly/measure-persuasion, to advance our understanding of AI-driven persuasion and its societal implications.

[Arxiv](https://arxiv.org/abs/2410.02653)