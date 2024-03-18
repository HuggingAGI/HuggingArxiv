# [Gradient Cuff 技术，通过深入探究大型语言模型中拒绝损失的地形特征，来实现对模型遭受越狱攻击的有效识别。]

发布时间：2024年02月29日

`LLM安全`

> Gradient Cuff: Detecting Jailbreak Attacks on Large Language Models by Exploring Refusal Loss Landscapes

> 现今，LLMs作为强大的生成式AI工具大放异彩，用户提问后由LLM生成回答。为防止其滥用和造成不良影响，科研人员采用 RLHF 等先进技术训练LLMs以契合人类价值体系。但最新的研究表明，LLMs在面对旨在破坏内嵌安全屏障的对抗性越狱攻击时显得尤为脆弱。为应对这一挑战，本篇论文首先明确了LLMs的拒绝损失概念，并进而创新提出了一个名为“梯度手铐”的方法，用于探测越狱攻击行为。此方法巧妙运用拒绝损失曲线上独特的函数值和平滑性特征，构建了一个高效的分两步走的检测方案。实验证明，在分别针对两种已对齐LLMs（LLaMA-2-7B-Chat和Vicuna-7B-V1.5）及六类越狱攻击（包括GCG、AutoDAN、PAIR、TAP、Base64和LRL）的情况下，“梯度手铐”成功大幅提升了LLM识别并拒绝恶意越狱查询的能力，与此同时，通过灵活调节检测阈值，确保了模型在处理正常用户查询时仍能保持良好性能。

> Large Language Models (LLMs) are becoming a prominent generative AI tool, where the user enters a query and the LLM generates an answer. To reduce harm and misuse, efforts have been made to align these LLMs to human values using advanced training techniques such as Reinforcement Learning from Human Feedback (RLHF). However, recent studies have highlighted the vulnerability of LLMs to adversarial jailbreak attempts aiming at subverting the embedded safety guardrails. To address this challenge, this paper defines and investigates the Refusal Loss of LLMs and then proposes a method called Gradient Cuff to detect jailbreak attempts. Gradient Cuff exploits the unique properties observed in the refusal loss landscape, including functional values and its smoothness, to design an effective two-step detection strategy. Experimental results on two aligned LLMs (LLaMA-2-7B-Chat and Vicuna-7B-V1.5) and six types of jailbreak attacks (GCG, AutoDAN, PAIR, TAP, Base64, and LRL) show that Gradient Cuff can significantly improve the LLM's rejection capability for malicious jailbreak queries, while maintaining the model's performance for benign user queries by adjusting the detection threshold.

[Arxiv](https://arxiv.org/abs/2403.00867)