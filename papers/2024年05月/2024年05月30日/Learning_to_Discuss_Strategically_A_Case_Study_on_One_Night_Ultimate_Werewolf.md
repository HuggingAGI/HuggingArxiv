# 策略性讨论学习：《一夜终极狼人》案例分析

发布时间：2024年05月30日

`Agent

这篇论文主要探讨了基于大型语言模型（LLMs）的代理在处理沟通和游戏场景中的讨论策略问题。研究以“一夜终极狼人”游戏为例，分析了讨论策略对玩家信念和效用的影响，并开发了一个由强化学习（RL）驱动的语言代理框架，以指导代理采取恰当的讨论策略。因此，这篇论文更符合Agent分类，因为它专注于开发和应用代理技术来解决特定的沟通和游戏策略问题。` `人工智能`

> Learning to Discuss Strategically: A Case Study on One Night Ultimate Werewolf

# 摘要

> 沟通是人类社会不可或缺的一环，它促进了信息和信仰的交流。尽管大型语言模型（LLMs）技术日新月异，但基于这些模型的代理在处理讨论策略时往往显得力不从心，这在沟通和游戏场景中尤为关键。以“狼人”游戏为蓝本的变种——“一夜终极狼人”（ONUW），要求玩家因游戏中的角色变动而灵活制定讨论策略，这无疑增加了游戏的不确定性和复杂度。本研究首先揭示了ONUW游戏中两种情景下的完美贝叶斯均衡（PBEs）：讨论与否的对比。结果凸显了讨论策略通过影响玩家信念对效用的巨大影响，强调了讨论策略的重要性。基于这些发现，我们开发了一个由强化学习（RL）驱动的语言代理框架，该框架通过RL训练的讨论政策来指导代理采取恰当的讨论策略。实验结果显示，该框架在多个ONUW游戏场景中均表现出色，证明了其有效性和广泛适用性。

> Communication is a fundamental aspect of human society, facilitating the exchange of information and beliefs among people. Despite the advancements in large language models (LLMs), recent agents built with these often neglect the control over discussion tactics, which are essential in communication scenarios and games. As a variant of the famous communication game Werewolf, One Night Ultimate Werewolf (ONUW) requires players to develop strategic discussion policies due to the potential role changes that increase the uncertainty and complexity of the game. In this work, we first present the existence of the Perfect Bayesian Equilibria (PBEs) in two scenarios of the ONUW game: one with discussion and one without. The results showcase that the discussion greatly changes players' utilities by affecting their beliefs, emphasizing the significance of discussion tactics. Based on the insights obtained from the analyses, we propose an RL-instructed language agent framework, where a discussion policy trained by reinforcement learning (RL) is employed to determine appropriate discussion tactics to adopt. Our experimental results on several ONUW game settings demonstrate the effectiveness and generalizability of our proposed framework.

[Arxiv](https://arxiv.org/abs/2405.19946)