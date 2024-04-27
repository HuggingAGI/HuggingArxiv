# 大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。

发布时间：2024年04月13日

`Agent` `人工智能` `决策过程`

> Do LLMs Play Dice? Exploring Probability Distribution Sampling in Large Language Models for Behavioral Simulation

# 摘要

> 大型语言模型（LLMs）在处理复杂语言任务上的显著进步，促使众多研究将其作为模拟人类顺序决策过程（常以马尔可夫决策过程，MDPs表示）的代理。这些决策过程中的行动基于特定的概率分布，需通过迭代抽样来确定。这引发了我们对LLM代理能否理解概率分布，并以此指导其行为决策和生成行为序列的兴趣。为探究此问题，我们将研究分为两个方面：一是在已知确切概率分布的模拟中，代理需根据问题描述确定概率分布的类型和参数，然后生成抽样序列；二是在概率分布不明确的情况下生成序列。在第一种情况下，尽管LLM代理表现不佳，但通过编程工具可以提升其抽样成功率。然而，在第二种情况下，即使借助编程工具，LLM代理也无法准确抽样概率分布。因此，在将LLM代理直接应用于模拟人类行为之前，我们必须审慎考虑。

> With the rapid advancement of large language models (LLMs) and their remarkable capabilities in handling complex language tasks, an increasing number of studies are employing LLMs as agents to emulate the sequential decision-making processes of humans often represented as Markov decision-making processes (MDPs). The actions within this decision-making framework adhere to specific probability distributions and require iterative sampling. This arouses our curiosity regarding the capacity of LLM agents to comprehend probability distributions, thereby guiding the agent's behavioral decision-making through probabilistic sampling and generating behavioral sequences. To answer the above question, we divide the problem into two main aspects: simulation where the exact probability distribution is known, and generation of sequences where the probability distribution is ambiguous. In the first case, the agent is required to give the type and parameters of the probability distribution through the problem description, and then give the sampling sequence. However, our analysis shows that LLM agents perform poorly in this case, but the sampling success rate can be improved through programming tools. Real-world scenarios often entail unknown probability distributions. Thus, in the second case, we ask the agents to change the activity level in online social networks and analyze the frequency of actions. Ultimately, our analysis shows that LLM agents cannot sample probability distributions even using programming tools. Therefore, careful consideration is still required before directly applying LLM agents as agents to simulate human behavior.

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x1.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x2.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x3.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x4.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x5.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x6.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x7.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x8.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x9.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x10.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x11.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x12.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x13.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x14.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x15.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x16.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x17.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x18.png)

![大型语言模型（LLM）是否遵循随机性原则？本文深入探讨了在这些模型中运用概率分布抽样技术以进行行为模拟的可能性。](../../../paper_images/2404.09043/x19.png)

[Arxiv](https://arxiv.org/abs/2404.09043)