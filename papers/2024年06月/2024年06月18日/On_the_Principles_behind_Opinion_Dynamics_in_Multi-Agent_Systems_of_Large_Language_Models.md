# 大规模语言模型多代理系统中意见动态的原理探究

发布时间：2024年06月18日

`Agent

这篇论文探讨了大型语言模型（LLMs）在群体中意见的演变过程，特别是在资金分配决策中的交互行为。研究关注了LLMs如何通过交流达成共识，考虑伦理因素，并受到多种因素如意见改变理由的感知、讨论参与意愿及资金分配值分布的影响。这种对LLMs作为决策代理的行为研究，以及它们在群体中的交互和决策过程，符合Agent分类的定义，即研究智能体（如LLMs）在特定环境中的行为和决策机制。` `人工智能`

> On the Principles behind Opinion Dynamics in Multi-Agent Systems of Large Language Models

# 摘要

> 我们探讨了大型语言模型（LLMs）群体中意见如何随交互而演变。每个LLM面临资金分配的抉择：全额、部分或不资助。我们发现，LLMs在交流意见时，会倾向于与其他模型达成共识、在资金分配上谨慎行事，并考虑伦理因素。这些行为偏见受到对意见改变理由的感知、讨论参与意愿及资金分配值分布的影响。偏见间的张力有时会导致负面项目的资金得以保留。当LLM自由形成意见时，资金分配的意见更为多元；而在多选情况下，则易形成共识或极化。若LLMs知晓过往意见，它们会追求一致性，并采用更多样的更新策略。本研究采用Llama 3 LLM进行。

> We study the evolution of opinions inside a population of interacting large language models (LLMs). Every LLM needs to decide how much funding to allocate to an item with three initial possibilities: full, partial, or no funding. We identify biases that drive the exchange of opinions based on the LLM's tendency to (i) find consensus with the other LLM's opinion, (ii) display caution when specifying funding, and (iii) consider ethical concerns in its opinion. We find these biases are affected by the perceived absence of compelling reasons for opinion change, the perceived willingness to engage in discussion, and the distribution of allocation values. Moreover, tensions among biases can lead to the survival of funding for items with negative connotations. We also find that the final distribution of full, partial, and no funding opinions is more diverse when an LLM freely forms its opinion after an interaction than when its opinion is a multiple-choice selection among the three allocation options. In the latter case, consensus or polarization is generally attained. When agents are aware of past opinions, they seek to maintain consistency with them, and more diverse updating rules emerge. Our study is performed using a Llama 3 LLM.

[Arxiv](https://arxiv.org/abs/2406.15492)