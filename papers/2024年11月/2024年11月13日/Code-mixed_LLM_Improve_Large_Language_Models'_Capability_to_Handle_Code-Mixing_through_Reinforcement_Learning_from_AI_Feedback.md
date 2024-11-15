# 代码混合的 LLM ：借助来自 AI 反馈的强化学习，提升大型语言模型处理代码混合的能力

发布时间：2024年11月13日

`LLM应用` `多语言模型`

> Code-mixed LLM: Improve Large Language Models' Capability to Handle Code-Mixing through Reinforcement Learning from AI Feedback

# 摘要

> 代码混合（CM）或代码切换（CSW）指的是在对话中甚至单个表述里，两种及以上语言的语言单位并列出现。代码混合在日常生活中带来了独特挑战，像句法不匹配和语义融合，这些在单语环境中鲜少碰到。大型语言模型（LLM）凭借在理解人类语言上的超强能力，给自然语言处理（NLP）领域带来了变革。但当下最先进的多语言 LLM 在 CM 场景中的效果还未被充分挖掘。为弥补这一空缺，我们先是在各类代码混合的 NLP 任务上对多语言 LLM 的性能进行基准测试。接着，我们提议通过从人类反馈的强化学习（RLHF）和代码混合机器翻译任务来增强多语言 LLM 理解代码混合的能力。鉴于偏好标注过程成本高又耗时，我们利用 LLM 作为标注者，进行从 AI 反馈的强化学习（RLAIF）来加以改进。实验证明了所提方法的有效性。

> Code-mixing(CM) or code-switching(CSW) refers to the juxtaposition of linguistic units from two or more languages during the conversation or sometimes even a single utterance. Code-mixing introduces unique challenges in daily life, such as syntactic mismatches and semantic blending, that are rarely encountered in monolingual settings. Large language models (LLMs) have revolutionized the field of natural language processing (NLP) by offering unprecedented capabilities in understanding human languages. However, the effectiveness of current state-of-the-art multilingual LLMs has not yet been fully explored in the CM scenario. To fill this gap, we first benchmark the performance of multilingual LLMs on various code-mixing NLP tasks. Then we propose to improve the multilingual LLMs' ability to understand code-mixing through reinforcement learning from human feedback (RLHF) and code-mixed machine translation tasks. Given the high-cost and time-consuming preference labeling procedure, we improve this by utilizing LLMs as annotators to perform the reinforcement learning from AI feedback (RLAIF). The experiments show the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2411.09073)