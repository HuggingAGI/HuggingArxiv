# 随机猴子在玩耍：随机增强轻松打破大型语言模型的安全对齐

发布时间：2024年11月04日

`LLM应用` `语言模型` `安全研究`

> Stochastic Monkeys at Play: Random Augmentations Cheaply Break LLM Safety Alignment

# 摘要

> 大型语言模型（LLM）的安全对齐最近已成为模型开发者的关键目标。作为回应，越来越多的工作一直在研究如何通过各种越狱方法（如对抗性攻击）绕过安全对齐。然而，这些越狱方法可能相当昂贵，或者需要大量的创造力和努力，这引入了恶意用户是高资源或复杂的假设。在本文中，我们研究了对输入提示的简单随机扩充如何影响最先进的 LLM（如 Llama 3 和 Qwen 2）中的安全对齐效果。我们对 17 种不同的模型进行了深入评估，并研究了随机扩充下安全与多个维度的交集：扩充类型、模型大小、量化、基于微调的防御和解码策略（例如，采样温度）。我们表明，低资源和不复杂的攻击者，即“随机猴子”，只需每个提示 25 次随机扩充，就能显著提高绕过对齐的机会。

> Safety alignment of Large Language Models (LLMs) has recently become a critical objective of model developers. In response, a growing body of work has been investigating how safety alignment can be bypassed through various jailbreaking methods, such as adversarial attacks. However, these jailbreak methods can be rather costly or involve a non-trivial amount of creativity and effort, introducing the assumption that malicious users are high-resource or sophisticated. In this paper, we study how simple random augmentations to the input prompt affect safety alignment effectiveness in state-of-the-art LLMs, such as Llama 3 and Qwen 2. We perform an in-depth evaluation of 17 different models and investigate the intersection of safety under random augmentations with multiple dimensions: augmentation type, model size, quantization, fine-tuning-based defenses, and decoding strategies (e.g., sampling temperature). We show that low-resource and unsophisticated attackers, i.e. $\textit{stochastic monkeys}$, can significantly improve their chances of bypassing alignment with just 25 random augmentations per prompt.

[Arxiv](https://arxiv.org/abs/2411.02785)