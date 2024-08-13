# 探究大型语言模型遗忘过程中潜在表示的引导效应

发布时间：2024年08月12日

`LLM理论` `人工智能` `网络安全`

> On Effects of Steering Latent Representation for Large Language Model Unlearning

# 摘要

> RMU 是一种高效的大语言模型遗忘技术，通过引导中间层表示至随机目标来实现。尽管效果显著，其原理仍待深入探究。本文首先理论阐释了中间层遗忘表示引导降低令牌信心，进而引发错误或无意义响应的现象。接着，我们探讨了系数对遗忘样本与随机方向对齐的影响，并指出了各层最佳系数值。此外，RMU 遗忘模型展现出对抗越狱攻击的强健性。然而，实证显示 RMU 在模型中后期层效果减弱。为此，我们提出 Adaptive RMU，一种简便且高效的遗忘方法，适用于多数层。实验证实，Adaptive RMU 在提升遗忘性能的同时，不增加计算负担，超越了现有技术。

> Representation Misdirection for Unlearning (RMU), which steers model representation in the intermediate layer to a target random representation, is an effective method for large language model (LLM) unlearning. Despite its high performance, the underlying cause and explanation remain underexplored. In this paper, we first theoretically demonstrate that steering forget representations in the intermediate layer reduces token confidence, causing LLMs to generate wrong or nonsense responses. Second, we investigate how the coefficient influences the alignment of forget-sample representations with the random direction and hint at the optimal coefficient values for effective unlearning across different network layers. Third, we show that RMU unlearned models are robust against adversarial jailbreak attacks. Last, our empirical analysis shows that RMU is less effective when applied to the middle and later layers in LLMs. To resolve this drawback, we propose Adaptive RMU -- a simple yet effective alternative method that makes unlearning effective with most layers. Extensive experiments demonstrate that Adaptive RMU significantly improves the unlearning performance compared to prior art while incurring no additional computational cost.

[Arxiv](https://arxiv.org/abs/2408.06223)