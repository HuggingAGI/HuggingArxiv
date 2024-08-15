# 利用情景记忆对大型语言模型进行提示

发布时间：2024年08月14日

`LLM应用` `机器学习`

> Large Language Models Prompting With Episodic Memory

# 摘要

> 提示优化对于提升大型语言模型（LLM）在自然语言处理（NLP）任务中的表现至关重要，尤其是在少样本学习场景中。尽管对少样本示例优化提示的兴趣日益增长，但现有方法往往资源密集或效果不佳。为此，我们提出了POEM（带有情景记忆的提示优化），这是一种简单、高效且泛化能力强的创新技术。我们将提示优化视为强化学习挑战，利用情景记忆存储输入数据组合、示例排列及训练奖励。在测试时，我们根据情景记忆中与测试查询最相似的前k个示例，选择总奖励最高的序列进行优化。实验表明，POEM在文本分类任务中超越了TEMPERA和RLPrompt等技术5.3%以上，并能有效适应更广泛的语言理解任务，持续优于传统启发式方法。

> Prompt optimization is essential for enhancing the performance of Large Language Models (LLMs) in a range of Natural Language Processing (NLP) tasks, particularly in scenarios of few-shot learning where training examples are incorporated directly into the prompt. Despite the growing interest in optimizing prompts with few-shot examples, existing methods for prompt optimization are often resource-intensive or perform inadequately. In this work, we propose PrOmpting with Episodic Memory (POEM), a novel prompt optimization technique that is simple, efficient, and demonstrates strong generalization capabilities. We approach prompt optimization as a Reinforcement Learning (RL) challenge, using episodic memory to archive combinations of input data, permutations of few-shot examples, and the rewards observed during training. In the testing phase, we optimize the sequence of examples for each test query by selecting the sequence that yields the highest total rewards from the top-k most similar training examples in the episodic memory. Our results show that POEM outperforms recent techniques like TEMPERA and RLPrompt by over 5.3% in various text classification tasks. Furthermore, our approach adapts well to broader language understanding tasks, consistently outperforming conventional heuristic methods for ordering examples.

[Arxiv](https://arxiv.org/abs/2408.07465)