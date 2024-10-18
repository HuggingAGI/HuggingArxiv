# SPIN：自监督提示注入技术

发布时间：2024年10月17日

`LLM应用` `网络安全` `人工智能`

> SPIN: Self-Supervised Prompt INjection

# 摘要

> 尽管 LLM 在众多重要应用中日益普及，但其安全性和可靠性仍是关键问题。为绕过安全机制，多种对抗性和越狱攻击层出不穷，导致模型输出有害内容。为此，我们推出了自监督提示注入 (SPIN)，能有效识别并反击这些攻击。由于 SPIN 在推理阶段进行防御，因此与现有安全机制无缝对接，进一步提升防御能力。测试显示，SPIN 能将攻击成功率降低 87.9%，同时不影响正常用户请求的处理。此外，面对自适应攻击者，SPIN 仍能保持防御效果，确保 LLM 的安全运行。

> Large Language Models (LLMs) are increasingly used in a variety of important applications, yet their safety and reliability remain as major concerns. Various adversarial and jailbreak attacks have been proposed to bypass the safety alignment and cause the model to produce harmful responses. We introduce Self-supervised Prompt INjection (SPIN) which can detect and reverse these various attacks on LLMs. As our self-supervised prompt defense is done at inference-time, it is also compatible with existing alignment and adds an additional layer of safety for defense. Our benchmarks demonstrate that our system can reduce the attack success rate by up to 87.9%, while maintaining the performance on benign user requests. In addition, we discuss the situation of an adaptive attacker and show that our method is still resilient against attackers who are aware of our defense.

[Arxiv](https://arxiv.org/abs/2410.13236)