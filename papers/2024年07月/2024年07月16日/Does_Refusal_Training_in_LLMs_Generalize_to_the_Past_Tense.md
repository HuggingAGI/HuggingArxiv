# LLMs 的拒绝训练能否适用于过去时态？

发布时间：2024年07月16日

`LLM应用` `网络安全` `人工智能`

> Does Refusal Training in LLMs Generalize to the Past Tense?

# 摘要

> 拒绝训练广泛用于防止 LLM 生成有害输出。我们发现，简单地将有害请求改写为过去时态（如“如何制作莫洛托夫鸡尾酒？”改为“人们是如何制作莫洛托夫鸡尾酒的？”），就能破解许多最先进的 LLM。我们测试了这种方法在多个模型上的效果，发现改写为过去时态的请求成功率显著提高。有趣的是，未来时态的改写效果较差，表明拒绝机制更倾向于认为过去的问题比未来的问题更安全。我们还通过微调 GPT-3.5 Turbo 发现，明确包含过去时态例子的数据可以有效防御这种改写攻击。总体而言，我们的研究揭示了现有对齐技术的脆弱性，并提供了防御策略。相关代码和破解工件已公开。

> 
Abstract:Refusal training is widely used to prevent LLMs from generating harmful, undesirable, or illegal outputs. We reveal a curious generalization gap in the current refusal training approaches: simply reformulating a harmful request in the past tense (e.g., "How to make a Molotov cocktail?" to "How did people make a Molotov cocktail?") is often sufficient to jailbreak many state-of-the-art LLMs. We systematically evaluate this method on Llama-3 8B, Claude-3.5 Sonnet, GPT-3.5 Turbo, Gemma-2 9B, Phi-3-Mini, GPT-4o mini, GPT-4o, and R2D2 models using GPT-3.5 Turbo as a reformulation model. For example, the success rate of this simple attack on GPT-4o increases from 1% using direct requests to 88% using 20 past tense reformulation attempts on harmful requests from JailbreakBench with GPT-4 as a jailbreak judge. Interestingly, we also find that reformulations in the future tense are less effective, suggesting that refusal guardrails tend to consider past historical questions more benign than hypothetical future questions. Moreover, our experiments on fine-tuning GPT-3.5 Turbo show that defending against past reformulations is feasible when past tense examples are explicitly included in the fine-tuning data. Overall, our findings highlight that the widely used alignment techniques -- such as SFT, RLHF, and adversarial training -- employed to align the studied models can be brittle and do not always generalize as intended. We provide code and jailbreak artifacts at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2407.11969)