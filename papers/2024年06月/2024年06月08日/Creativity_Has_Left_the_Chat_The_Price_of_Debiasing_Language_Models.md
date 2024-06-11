# 创意之翼悄然离去：语言模型去偏的代价

发布时间：2024年06月08日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在应用人类反馈强化学习（RLHF）技术后对创造力的影响，这是一个关于LLMs理论层面的研究，特别是关于模型对齐技术如何影响语言模型的创造性和多样性。它不仅分析了模型的行为，还提出了对未来模型设计和应用的建议，这属于理论研究的范畴。`

> Creativity Has Left the Chat: The Price of Debiasing Language Models

# 摘要

> 大型语言模型（LLMs）虽已革新自然语言处理，却可能带有偏见并产生有害内容。尽管人类反馈强化学习（RLHF）等对齐技术能缓解这些问题，但其对创造力（即语法与语义多样性）的影响尚待探究。我们通过针对Llama-2系列的三项实验，揭示了RLHF对LLMs创造力的潜在影响：对齐模型在令牌预测中的熵较低，嵌入空间中形成独特集群，并趋向于“吸引子状态”，显示输出多样性受限。这些发现对依赖LLMs进行创意工作的营销人员尤为关键，如文案、广告及客户角色创作。在选择模型时，需审慎权衡对齐模型中的一致性与创造力。此外，我们还强调了提示工程在激发基础模型创造潜力中的重要性。

> Large Language Models (LLMs) have revolutionized natural language processing but can exhibit biases and may generate toxic content. While alignment techniques like Reinforcement Learning from Human Feedback (RLHF) reduce these issues, their impact on creativity, defined as syntactic and semantic diversity, remains unexplored. We investigate the unintended consequences of RLHF on the creativity of LLMs through three experiments focusing on the Llama-2 series. Our findings reveal that aligned models exhibit lower entropy in token predictions, form distinct clusters in the embedding space, and gravitate towards "attractor states", indicating limited output diversity. Our findings have significant implications for marketers who rely on LLMs for creative tasks such as copywriting, ad creation, and customer persona generation. The trade-off between consistency and creativity in aligned models should be carefully considered when selecting the appropriate model for a given application. We also discuss the importance of prompt engineering in harnessing the creative potential of base models.

[Arxiv](https://arxiv.org/abs/2406.05587)