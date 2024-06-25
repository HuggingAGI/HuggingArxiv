# 大规模语言模型多代理系统中意见动态的原则探究

发布时间：2024年06月18日

`Agent

这篇论文探讨了大型语言模型（LLMs）在交互中的意见演变，特别是在资金分配决策中的行为和偏见。研究关注的是LLMs作为决策代理的行为，包括它们如何受到偏见的影响、如何与其他LLMs交互以及这些交互如何影响最终的决策。这种研究属于Agent的范畴，因为它涉及LLMs作为自主实体在特定环境中的行为和决策过程。` `人工智能`

> On the Principles behind Opinion Dynamics in Multi-Agent Systems of Large Language Models

# 摘要

> 我们探讨了大型语言模型（LLMs）群体中意见如何随交互而演变。每个LLM面临为项目分配资金的选择：全额、部分或不资助。我们发现，LLMs在交换意见时受到特定偏见的影响，如倾向于与其他LLM达成共识、在资金分配上谨慎，以及考虑伦理因素。这些偏见受到对意见改变理由的感知、讨论参与意愿及资金分配方式的影响。偏见间的冲突可能导致负面项目的资金得以保留。我们还观察到，当LLM自由形成意见时，资金分配的意见更加多元，而在有限选择中，往往导致共识或极化。当LLMs回顾过去意见时，它们倾向于保持一致性，并采用更多样化的更新策略。本研究采用Llama 3 LLM进行。

> We study the evolution of opinions inside a population of interacting large language models (LLMs). Every LLM needs to decide how much funding to allocate to an item with three initial possibilities: full, partial, or no funding. We identify biases that drive the exchange of opinions based on the LLM's tendency to (i) find consensus with the other LLM's opinion, (ii) display caution when specifying funding, and (iii) consider ethical concerns in its opinion. We find these biases are affected by the perceived absence of compelling reasons for opinion change, the perceived willingness to engage in discussion, and the distribution of allocation values. Moreover, tensions among biases can lead to the survival of funding for items with negative connotations. We also find that the final distribution of full, partial, and no funding opinions is more diverse when an LLM freely forms its opinion after an interaction than when its opinion is a multiple-choice selection among the three allocation options. In the latter case, consensus or polarization is generally attained. When agents are aware of past opinions, they seek to maintain consistency with them, and more diverse updating rules emerge. Our study is performed using a Llama 3 LLM.

[Arxiv](https://arxiv.org/abs/2406.15492)