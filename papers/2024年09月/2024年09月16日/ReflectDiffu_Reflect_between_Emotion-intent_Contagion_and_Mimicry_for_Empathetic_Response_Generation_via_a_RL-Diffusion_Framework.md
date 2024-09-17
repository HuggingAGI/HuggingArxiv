# ReflectDiffu：借助 RL-Diffusion 框架，在情感与意图的传染和模仿之间进行反思，从而生成共情回应。

发布时间：2024年09月16日

`LLM应用` `人工智能` `情感计算`

> ReflectDiffu: Reflect between Emotion-intent Contagion and Mimicry for Empathetic Response Generation via a RL-Diffusion Framework

# 摘要

> 共情响应生成需要情感与意图的深度融合，以实现更真实的互动。现有研究要么忽视了情感与意图的微妙关系，导致共情控制不佳，要么依赖计算成本高昂的大型语言模型。本文提出 ReflectDiffu，一个轻量且全面的共情响应生成框架。它通过情感传染增强表达，用情感推理掩码精准定位情感元素，并在强化学习中融入意图模仿以优化扩散过程。借助意图双重反射机制，ReflectDiffu 将情感决策转化为精准意图行动，有效解决情感误识别导致的共情偏差。通过情感与意图的映射，该框架大幅提升了响应的共情度和灵活性。实验证明，ReflectDiffu 在相关性、可控性和信息量上超越现有模型，在自动和人工评估中均达到顶尖水平。

> Empathetic response generation necessitates the integration of emotional and intentional dynamics to foster meaningful interactions. Existing research either neglects the intricate interplay between emotion and intent, leading to suboptimal controllability of empathy, or resorts to large language models (LLMs), which incur significant computational overhead. In this paper, we introduce ReflectDiffu, a lightweight and comprehensive framework for empathetic response generation. This framework incorporates emotion contagion to augment emotional expressiveness and employs an emotion-reasoning mask to pinpoint critical emotional elements. Additionally, it integrates intent mimicry within reinforcement learning for refinement during diffusion. By harnessing an intent twice reflect the mechanism of Exploring-Sampling-Correcting, ReflectDiffu adeptly translates emotional decision-making into precise intent actions, thereby addressing empathetic response misalignments stemming from emotional misrecognition. Through reflection, the framework maps emotional states to intents, markedly enhancing both response empathy and flexibility. Comprehensive experiments reveal that ReflectDiffu outperforms existing models regarding relevance, controllability, and informativeness, achieving state-of-the-art results in both automatic and human evaluations.

[Arxiv](https://arxiv.org/abs/2409.10289)